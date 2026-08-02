---
title: "PdfViewer.PrintDocuments"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfViewer method. Печатает несколько PDF‑документов, используя принтер по умолчанию и настройки страницы"
type: docs
weight: 370
url: /ru/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

Печатает несколько PDF документов, используя принтер по умолчанию и настройки страницы.

```csharp
public static void PrintDocuments(params Document[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documents | Document[] | Массив объектов [`Document`](../../../aspose.pdf/document/), представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов в одном задании печати.

## Примеры

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

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

Печатает несколько PDF документов, используя принтер по умолчанию и настройки страницы.

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePaths | String[] | Массив путей к файлам, представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов в одном задании печати. Убедитесь, что указанные пути к файлам действительны и доступны.

## Примеры

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

### См. также

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

Печатает несколько PDF документов из предоставленных потоков, используя принтер по умолчанию и настройки страницы.

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentStreams | Stream[] | Массив потоков, содержащих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов за одну операцию. Убедитесь, что предоставленные потоки действительны и доступны в процессе печати.

## Примеры

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

### См. также

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

Печатает несколько PDF документов, используя указанные настройки принтера.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Объект [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/), который определяет настройки принтера для печати. |
| documents | Document[] | Массив объектов [`Document`](../../../aspose.pdf/document/), представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов с пользовательскими настройками принтера.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

Печатает несколько PDF документов, используя указанные настройки принтера.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Объект [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/), содержащий детали конфигурации принтера. |
| filePaths | String[] | Массив путей к файлам, представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов в одном задании печати. Убедитесь, что указанные пути к файлам действительны и доступны.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

Печатает несколько PDF‑документов из предоставленных потоков, используя указанные настройки принтера.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Настройки принтера, которые будут применены во время процесса печати. |
| documentStreams | Stream[] | Массив потоков, содержащих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов за одну операцию. Убедитесь, что предоставленные потоки действительны и доступны в процессе печати.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

Печатает несколько PDF‑документов, используя указанные настройки принтера и страницы.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Объект [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/), который определяет настройки принтера для печати. |
| pageSettings | PageSettings | Объект [`PageSettings`](../../../aspose.pdf.printing/pagesettings/), который определяет настройки страницы для печати. |
| documents | Document[] | Массив объектов [`Document`](../../../aspose.pdf/document/), представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов с пользовательскими настройками принтера и страницы.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

Печатает несколько PDF‑документов, используя указанные настройки принтера и страницы.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Объект [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/), содержащий детали конфигурации принтера. |
| pageSettings | PageSettings | Объект [`PageSettings`](../../../aspose.pdf.printing/pagesettings/), определяющий макет и настройки страницы. |
| filePaths | String[] | Массив путей к файлам, представляющих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов в одном задании печати. Убедитесь, что указанные пути к файлам действительны и доступны.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

Печатает несколько PDF‑документов из предоставленных потоков, используя указанные настройки принтера и страницы.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | PrinterSettings | Настройки принтера, которые будут применены во время процесса печати. |
| pageSettings | PageSettings | Настройки страницы, которые будут применены к каждому документу при печати. |
| documentStreams | Stream[] | Массив потоков, содержащих PDF‑документы для печати. |

## Примечания

Этот метод позволяет печатать несколько PDF‑документов за одну операцию. Убедитесь, что предоставленные потоки действительны и доступны в процессе печати.

## Примеры

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

### См. также

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


