---
title: "PdfViewer.CustomPrint"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Событие PdfViewer. Происходит перед началом печати и позволяет предоставить пользовательские обработчики печати вместо обработчика по умолчанию"
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

Происходит до начала печати и позволяет предоставить пользовательские обработчики печати вместо стандартного.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## Примеры

Пример демонстрирует, как печатать из Aspose.PDF в системах Linux. Следующий код в основном предназначен для печати из Aspose.PDF в системах Linux. Пользователи систем Windows могут продолжать использовать реализацию печати по умолчанию в PdfViewer без предоставления обработчика CustomPrint.

### Prerequisites

1. На системе сервера печати CUPS должен быть установлен и настроен:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. Принтер можно настроить с помощью веб-интерфейса CUPS. При желании можно использовать виртуальный PDF принтер:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. Если ваша клиентская система (где запущено приложение с поддержкой Aspose.PDF) отличается от сервера печати, вам также необходимо установить и запустить CUPS там:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Установите пользовательский обработчик печати, который формирует команду lp и запускает её с помощью bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Отправьте документ на виртуальный PDF‑принтер, установленный пакетом printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Документ будет напечатан с использованием предоставленного обработчика печати
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Пользовательский обработчик печати
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Установите имя принтера, на котором будет печататься
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Установите количество копий
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Установите диапазон страниц для печати
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Установите размер бумаги
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Установите альбомную ориентацию, если требуется
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Установите разрешение принтера
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

    // Установите двустороннюю печать, если требуется
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

    // Имя файла для печати
    sb.AppendFormat("-- {0} ", e.FileName);

    // Запустите подготовленную команду lp с помощью bash
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

// Установите пользовательский обработчик печати, который создает файл задания ipptool и запускает ipptool с помощью bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Отправьте документ на виртуальный PDF‑принтер, установленный пакетом printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Документ будет напечатан с использованием предоставленного обработчика печати
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Пользовательский обработчик печати
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // Имя файла для печати
    command.AppendFormat("-f {0} ", e.FileName);

    // Установите URI принтера, на котором будет печататься
    command.Append(e.PrinterSettings.PrinterUri);

    // Получите временное имя файла для файла задания ipptool
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Установите имя задания и тип задания
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Установите настройки задания по умолчанию
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Установите количество копий
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Установите размер бумаги
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET использует 1/100 дюйма для представления размера бумаги, тогда как IPP требует 1/1000 миллиметра — требуется преобразование
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Установите поля
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

    // Создайте файл задания ipptool
    File.WriteAllText(jobFile, sb.ToString());

    // Передайте файл задания ipptool
    command.AppendFormat(" {0}", jobFile);

    // Запустите подготовленную команду ipptool с помощью bash
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

    // Удалите временный файл задания после печати документа
    File.Delete(jobFile);
}
```

### См. также

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


