---
title: CreateFileAttachment
second_title: Aspose.PDF для справочника API .NET
description: Создает аннотацию вложенного файла.
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Создает аннотацию вложенного файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| filePath | String | Будет прикреплен путь к файлу. |
| page | Int32 | Номер исходной страницы, на которой будет создана аннотация. |
| name | String | Имя значка будет использоваться при отображении аннотации. Это значение может быть:"График", "Кнопка", "Скрепка", "Тег". |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Создает аннотацию вложенного файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| filePath | String | Будет прикреплен путь к файлу. |
| page | Int32 | Номер исходной страницы, на которой будет создана аннотация. |
| name | String | Имя значка будет использоваться при отображении аннотации. Это значение может быть:"График", "Кнопка", "Скрепка", "Тег". |
| opacity | Double | Непрозрачность иконки от 0 до 1:0 - полностью прозрачная, 1 - полностью непрозрачная. |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Создает аннотацию вложенного файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| attachmentStream | Stream | Поток файла вложения. |
| имя_вложения | String | Имя вложения. |
| page | Int32 | Номер исходной страницы, на которой будет создана аннотация. |
| name | String | Имя значка будет использоваться при отображении аннотации. Это значение может быть:"График", "Кнопка", "Скрепка", "Тег". |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Создает аннотацию вложенного файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| attachmentStream | Stream | Поток файла вложения. |
| имя_вложения | String | Имя вложения. |
| page | Int32 | Номер исходной страницы, на которой будет создана аннотация. |
| name | String | Имя значка будет использоваться при отображении аннотации. Это значение может быть:"График", "Кнопка", "Скрепка", "Тег". |
| opacity | Double | Непрозрачность иконки от 0 до 1:0 - полностью прозрачная, 1 - полностью непрозрачная. |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
