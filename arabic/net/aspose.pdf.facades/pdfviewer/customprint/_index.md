---
title: "PdfViewer.CustomPrint"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "حدث PdfViewer. يحدث قبل بدء الطباعة ويسمح بتوفير معالجات طباعة مخصصة بدلاً من المعالج الافتراضي"
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

يحدث قبل بدء الطباعة ويسمح بتوفير معالجات طباعة مخصصة بدلاً من المعالج الافتراضي.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## أمثلة

يوضح المثال كيفية الطباعة من Aspose.PDF على أنظمة Linux. يهدف الشيفرة التالية أساسًا إلى الطباعة من Aspose.PDF على أنظمة Linux. يمكن لمستخدمي أنظمة Windows الاستمرار في استخدام تنفيذ الطباعة الافتراضي لـ PdfViewer دون توفير معالج CustomPrint.

### Prerequisites

1. على نظام خادم الطباعة يجب تثبيت CUPS وتكوينه:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. يمكن إعداد طابعة باستخدام واجهة الويب الخاصة بـ CUPS. بدلاً من ذلك، يمكنك استخدام طابعة PDF افتراضية:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. إذا كان نظام العميل الخاص بك (حيث يعمل التطبيق المدعوم بـ Aspose.PDF) مختلفًا عن خادم الطباعة، فستحتاج إلى تثبيت وتشغيل CUPS هناك أيضًا:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// قم بتعيين معالج طباعة مخصص يبني أمر lp ويشغله باستخدام bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// أرسل المستند إلى طابعة PDF الافتراضية المثبتة مع حزمة printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// سيتم طباعة المستند باستخدام معالج الطباعة المقدم
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// معالج طباعة مخصص
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // حدد اسم الطابعة التي ستتم الطباعة عليها
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // حدد عدد النسخ
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // حدد نطاق الصفحات للطباعة
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // حدد حجم الورق
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // حدد الاتجاه الأفقي إذا طُلب ذلك
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // حدد دقة الطابعة
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

    // حدد الطباعة ذات الوجهين إذا طُلب ذلك
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

    // اسم الملف المراد طباعته
    sb.AppendFormat("-- {0} ", e.FileName);

    // شغّل أمر lp المُعد باستخدام bash
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

// قم بتعيين معالج طباعة مخصص يبني ملف مهمة ipptool ويشغله باستخدام ipptool وbash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// أرسل المستند إلى طابعة PDF الافتراضية المثبتة مع حزمة printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// سيتم طباعة المستند باستخدام معالج الطباعة المقدم
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// معالج طباعة مخصص
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // اسم الملف المراد طباعته
    command.AppendFormat("-f {0} ", e.FileName);

    // حدد URI للطابعة التي ستتم الطباعة عليها
    command.Append(e.PrinterSettings.PrinterUri);

    // احصل على اسم الملف المؤقت لملف مهمة ipptool
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // حدد اسم المهمة ونوع المهمة
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // حدد إعدادات المهمة الافتراضية
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // حدد عدد النسخ
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // حدد حجم الورق
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET يستخدم 1/100 من البوصة لتمثيل حجم الورق بينما IPP يتطلب 1/1000 من المليمتر - يلزم التحويل
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // حدد الهوامش
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

    // أنشئ ملف مهمة ipptool
    File.WriteAllText(jobFile, sb.ToString());

    // مرّر ملف المهمة إلى ipptool
    command.AppendFormat(" {0}", jobFile);

    // شغّل أمر ipptool المُعد باستخدام bash
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

    // احذف ملف المهمة المؤقت بعد طباعة المستند
    File.Delete(jobFile);
}
```

### انظر أيضًا

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


