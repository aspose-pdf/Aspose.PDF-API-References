---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfViewer. Открывает и печатает большой Pdf файл. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Открывает и печатает большой Pdf файл. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к Pdf файлу. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //print the file with adjusted size
iewer.AutoRotate = true;     //print the file with adjusted rotation
iewer.PrintPageDialog=false; //do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf");
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.Close()
```

### См. также

* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Открывает и печатает большой Pdf поток. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Pdf поток, который нужно открыть и напечатать. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //print the file with adjusted size
iewer.AutoRotate = true;        //print the file with adjusted rotation
iewer.PrintPageDialog=false;    //do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True         'print the file with adjusted size
iewer.AutoRotate = True         'print the file with adjusted rotation
iewer.PrintPageDialog = False   'do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.Close()
```

### См. также

* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Открывает и печатает большой Pdf файл с заданными настройками принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к Pdf файлу. |
| printerSettings | PrinterSettings | Настройки принтера. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.Close()
```

### См. также

* класс [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Открывает и печатает большой Pdf поток с заданными настройками принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Pdf поток, который нужно открыть и напечатать. |
| printerSettings | PrinterSettings | Настройки принтера. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.Close()
```

### См. также

* класс [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Открывает и печатает большой Pdf файл с заданными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к Pdf файлу. |
| pageSettings | PageSettings | Настройки страницы. |
| printerSettings | PrinterSettings | Настройки принтера. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.Close()
```

### См. также

* класс [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* класс [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Открывает и печатает большой Pdf поток с заданными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Pdf поток, который нужно открыть и напечатать. |
| pageSettings | PageSettings | Настройки страницы. |
| printerSettings | PrinterSettings | Настройки принтера. |

## Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать BindPdf().

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.Close()
```

### См. также

* класс [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* класс [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)