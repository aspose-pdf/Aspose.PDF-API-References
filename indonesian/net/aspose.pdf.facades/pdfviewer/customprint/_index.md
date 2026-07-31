---
title: "PdfViewer.CustomPrint"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfViewer event. Terjadi sebelum pencetakan dimulai dan memungkinkan menyediakan penangan cetak khusus alih-alih yang default"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

Terjadi sebelum pencetakan dimulai dan memungkinkan menyediakan penangan cetak khusus alih-alih yang default.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## Contoh

Contoh ini menunjukkan cara mencetak dari Aspose.PDF pada sistem Linux. Kode berikut ditujukan terutama untuk mencetak dari Aspose.PDF pada sistem Linux. Pengguna sistem Windows dapat terus menggunakan implementasi pencetakan PdfViewer default tanpa menyediakan penangan CustomPrint.

### Prerequisites

1. Pada sistem server cetak, CUPS harus diinstal dan dikonfigurasi:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. Printer dapat disiapkan menggunakan antarmuka web CUPS. Secara opsional, Anda dapat menggunakan printer PDF virtual:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. Jika sistem klien Anda (tempat aplikasi yang mendukung Aspose.PDF berjalan) berbeda dari server cetak, Anda perlu menginstal dan menjalankan CUPS di sana juga:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Atur penangan cetak khusus yang membangun perintah lp dan menjalankannya dengan bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Kirim dokumen ke printer PDF virtual yang diinstal dengan paket printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Dokumen akan dicetak menggunakan penangan cetak yang disediakan
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Penangan cetak khusus
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Atur nama printer untuk mencetak
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Atur jumlah salinan
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Atur rentang halaman untuk dicetak
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Atur ukuran kertas
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Atur orientasi lanskap jika diminta
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Atur resolusi printer
    switch (e.PageSettings.PrinterResolution.Kind)
    {
        case PrinterResolutionKind.High:
            sb.Append("-o print-quality=5 ");
            break;

        case PrinterResolutionKind.Medium:
            sb.Append("-o print-quality=4 ");
            break;

        case PrinterResolutionKind.Draft:
            sb.Append("-o print-quality=3 ");
            break;
    }

    // Atur pencetakan dua sisi jika diminta
    switch (e.PrinterSettings.Duplex)
    {
        case Duplex.Simplex:
            sb.Append("-o sides=one-sided ");
            break;

        case Duplex.Vertical:
            sb.Append("-o sides=two-sided-short-edge ");
            break;

        case Duplex.Horizontal:
            sb.Append("-o sides=two-sided-long-edge ");
            break;
    }

    // Nama file yang akan dicetak
    sb.AppendFormat("-- {0} ", e.FileName);

    // Jalankan perintah lp yang disiapkan dengan bash
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", sb.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }
}
```

### How to print a document using the ipptool

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Atur penangan cetak khusus yang membangun file pekerjaan ipptool dan menjalankan ipptool dengan bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Kirim dokumen ke printer PDF virtual yang diinstal dengan paket printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Dokumen akan dicetak menggunakan penangan cetak yang disediakan
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Penangan cetak khusus
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // Nama file yang akan dicetak
    command.AppendFormat("-f {0} ", e.FileName);

    // Atur URI printer untuk mencetak
    command.Append(e.PrinterSettings.PrinterUri);

    // Dapatkan nama file sementara untuk file pekerjaan ipptool
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Atur nama pekerjaan dan tipe pekerjaan
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Atur pengaturan pekerjaan default
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Atur jumlah salinan
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Atur ukuran kertas
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET menggunakan 1/100 inci untuk merepresentasikan ukuran kertas sementara IPP memerlukan 1/1000 milimeter - konversi diperlukan
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Atur margin
    if (pageSettings.Margins != null)
    {
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Top * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-bottom-margin {0}{1}", (int) (e.PageSettings.Margins.Bottom * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-left-margin {0}{1}", (int) (e.PageSettings.Margins.Left * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Right * 25.4),
            Environment.NewLine);
    }

    sb.AppendLine("    MEMBER keyword media-source \"main\"");
    sb.AppendLine("    MEMBER keyword media-type \"stationery\"");
    sb.AppendLine("  }");

    sb.AppendLine("  FILE $filename");
    sb.AppendLine("  STATUS successful-ok");
    sb.AppendLine("  STATUS successful-ok-ignored-or-substituted-attributes");
    sb.AppendLine("  EXPECT job-id");
    sb.AppendLine("  EXPECT job-uri");
    sb.AppendLine("}");

    // Buat file pekerjaan ipptool
    File.WriteAllText(jobFile, sb.ToString());

    // Berikan file pekerjaan ke ipptool
    command.AppendFormat(" {0}", jobFile);

    // Jalankan perintah ipptool yang disiapkan dengan bash
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", command.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }

    // Hapus file pekerjaan sementara setelah dokumen dicetak
    File.Delete(jobFile);
}
```

### Lihat Juga

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


