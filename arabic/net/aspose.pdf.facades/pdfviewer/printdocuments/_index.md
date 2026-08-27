---
title: "PdfViewer.PrintDocuments"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfViewer. تطبع عدة مستندات PDF باستخدام الطابعة الافتراضية وإعدادات الصفحة"
type: docs
weight: 370
url: /ar/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

يطبع عدة مستندات PDF باستخدام الطابعة الافتراضية وإعدادات Page.

```csharp
public static void PrintDocuments(params Document[] documents)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| documents | Document[] | مصفوفة من كائنات [`Document`](../../../aspose.pdf/document/) تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في مهمة طباعة واحدة.

## أمثلة

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3)
End Using
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

يطبع عدة مستندات PDF باستخدام الطابعة الافتراضية وإعدادات Page.

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filePaths | String[] | مصفوفة من مسارات الملفات تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في مهمة طباعة واحدة. تأكد من أن مسارات الملفات المقدمة صالحة ويمكن الوصول إليها.

## أمثلة

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3)
```

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

يطبع عدة مستندات PDF من التدفقات المقدمة باستخدام الطابعة الافتراضية وإعدادات Page.

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| documentStreams | Stream[] | مصفوفة من التدفقات التي تحتوي على مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في عملية واحدة. تأكد من أن التدفقات المقدمة صالحة ويمكن الوصول إليها أثناء عملية الطباعة.

## أمثلة

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3)
End Using
```

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

يطبع عدة مستندات PDF باستخدام إعدادات الطابعة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | الكائن [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) الذي يحدد إعدادات الطابعة لاستخدامها في الطباعة. |
| documents | Document[] | مصفوفة من كائنات [`Document`](../../../aspose.pdf/document/) تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF باستخدام إعدادات طابعة مخصصة.

## أمثلة

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3)
End Using
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

يطبع عدة مستندات PDF باستخدام إعدادات الطابعة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | الكائن [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) الذي يحتوي على تفاصيل تكوين الطابعة. |
| filePaths | String[] | مصفوفة من مسارات الملفات تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في مهمة طباعة واحدة. تأكد من أن مسارات الملفات المقدمة صالحة ويمكن الوصول إليها.

## أمثلة

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3)
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

يطبع مستندات PDF متعددة من التدفقات المقدمة باستخدام إعدادات الطابعة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | إعدادات الطابعة التي سيتم تطبيقها أثناء عملية الطباعة. |
| documentStreams | Stream[] | مصفوفة من التدفقات التي تحتوي على مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في عملية واحدة. تأكد من أن التدفقات المقدمة صالحة ويمكن الوصول إليها أثناء عملية الطباعة.

## أمثلة

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3)
End Using
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

يطبع مستندات PDF متعددة باستخدام الطابعة وإعدادات الصفحة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | الكائن [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) الذي يحدد إعدادات الطابعة لاستخدامها في الطباعة. |
| pageSettings | PageSettings | الكائن [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) الذي يحدد إعدادات الصفحة لاستخدامها في الطباعة. |
| documents | Document[] | مصفوفة من كائنات [`Document`](../../../aspose.pdf/document/) تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF باستخدام إعدادات طابعة وصفحة مخصصة.

## أمثلة

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
     pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
     pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3)
End Using
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

يطبع مستندات PDF متعددة باستخدام الطابعة وإعدادات الصفحة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | الكائن [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) الذي يحتوي على تفاصيل تكوين الطابعة. |
| pageSettings | PageSettings | الكائن [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) الذي يحدد تخطيط الصفحة وإعداداتها. |
| filePaths | String[] | مصفوفة من مسارات الملفات تمثل مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في مهمة طباعة واحدة. تأكد من أن مسارات الملفات المقدمة صالحة ويمكن الوصول إليها.

## أمثلة

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3)
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

يطبع مستندات PDF متعددة من التدفقات المقدمة باستخدام الطابعة وإعدادات الصفحة المحددة.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| printerSettings | PrinterSettings | إعدادات الطابعة التي سيتم تطبيقها أثناء عملية الطباعة. |
| pageSettings | PageSettings | إعدادات الصفحة التي سيتم تطبيقها على كل مستند أثناء الطباعة. |
| documentStreams | Stream[] | مصفوفة من التدفقات التي تحتوي على مستندات PDF التي سيتم طباعتها. |

## ملاحظات

تسمح هذه الطريقة بطباعة عدة مستندات PDF في عملية واحدة. تأكد من أن التدفقات المقدمة صالحة ويمكن الوصول إليها أثناء عملية الطباعة.

## أمثلة

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
    pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3)
End Using
```

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


