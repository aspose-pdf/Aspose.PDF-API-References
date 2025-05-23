---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию резинового штампа
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Создает аннотацию резинового штампа.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| icon | String | Иконка, которая будет использоваться для отображения аннотации. Значение по умолчанию: 'Draft'. |
| annotContents | String | Содержимое аннотации. |
| color | Color | Цвет аннотации. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Создает аннотацию резинового штампа.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| annotContents | String | Содержимое аннотации. |
| color | Color | Цвет аннотации. |
| appearanceFile | String | Путь к файлу внешнего вида. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Создает аннотацию резинового штампа.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| annotContents | String | Содержимое аннотации. |
| color | Color | Цвет аннотации. |
| appearanceStream | Stream | Поток файла внешнего вида. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)