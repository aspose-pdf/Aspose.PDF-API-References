---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию вложения файла
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Создает аннотацию вложения файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| filePath | String | Путь к файлу, который будет прикреплен. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| name | String | Имя значка, которое будет использоваться для отображения аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Создает аннотацию вложения файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| filePath | String | Путь к файлу, который будет прикреплен. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| name | String | Имя значка, которое будет использоваться для отображения аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Непрозрачность значка от 0 до 1: 0 - полностью прозрачный, 1 - полностью непрозрачный. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Создает аннотацию вложения файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| attachmentStream | Stream | Поток файла вложения. |
| attachmentName | String | Имя вложения. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| name | String | Имя значка, которое будет использоваться для отображения аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |

## Примеры

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

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Создает аннотацию вложения файла.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| attachmentStream | Stream | Поток файла вложения. |
| attachmentName | String | Имя вложения. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| name | String | Имя значка, которое будет использоваться для отображения аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Непрозрачность значка от 0 до 1: 0 - полностью прозрачный, 1 - полностью непрозрачный. |

## Примеры

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

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)