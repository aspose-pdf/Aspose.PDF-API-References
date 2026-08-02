---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfContentEditor метод. Создает аннотацию‑штамп."
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Создаёт аннотацию‑штамп.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| icon | String | Значок будет использоваться при отображении аннотации. Значение по умолчанию: 'Draft'. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Создаёт аннотацию‑штамп.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Создаёт аннотацию‑штамп.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


