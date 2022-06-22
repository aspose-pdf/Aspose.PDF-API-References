---
title: PrintLargePdf
second_title: Aspose.PDF для справочника API .NET
description: Открывает и печатает большой файл PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ рекомендуется использовать этот метод для повышения производительности.
type: docs
weight: 320
url: /ru/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Открывает и печатает большой файл PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу Pdf. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;      //печатать файл с измененным размером
iewer.AutoRotate = true;      //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'print the file with adjusted size
iewer.AutoRotate = true      'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Открывает и печатает большой поток PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток PDF для открытия и печати.. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;         //печатать файл с измененным размером
iewer.AutoRotate = true;         //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'print the file with adjusted size
iewer.AutoRotate = true         'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Открывает и печатает большой файл PDF с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу Pdf. |
| printerSettings | PrinterSettings | Настройки принтера. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //печатать файл с измененным размером
iewer.AutoRotate = true;        //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'print the file with adjusted size
iewer.AutoRotate = true        'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Открывает и печатает большой поток Pdf с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток PDF для открытия и печати.. |
| printerSettings | PrinterSettings | Настройки принтера. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //печатать файл с измененным размером
iewer.AutoRotate = true;        //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'print the file with adjusted size
iewer.AutoRotate = true        'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Открывает и печатает большой файл Pdf с указанными настройками страницы и настройками принтера. Если ваш файл Pdf содержит сотни страниц и более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности .

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу Pdf. |
| pageSettings | PageSettings | Настройки страницы. |
| printerSettings | PrinterSettings | Настройки принтера. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //печатать файл с измененным размером
iewer.AutoRotate = true;        //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'print the file with adjusted size
iewer.AutoRotate = true       'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Открывает и печатает большой поток PDF с указанными настройками страницы и настройками принтера. Если ваш файл Pdf содержит сотни страниц и более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности .

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток PDF, который нужно открыть и распечатать. |
| pageSettings | PageSettings | Настройки страницы. |
| printerSettings | PrinterSettings | Настройки принтера. |

### Примечания

Этот метод объединяет открытие и печать файла, и вам не нужно вызывать OpenPdfFile( ) явно.

### Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //печатать файл с измененным размером
iewer.AutoRotate = true;        //печатаем файл с настроенным rotate
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'print the file with adjusted size
iewer.AutoRotate = true       'print the file with adjusted rotation
iewer.PrintPageDialog=false; // не создавать диалоговое окно номера страницы при печати
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Смотрите также

* class [PdfViewer](../../pdfviewer)
* пространство имен [Aspose.Pdf.Facades](../../pdfviewer)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
