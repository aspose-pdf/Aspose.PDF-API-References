---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает ссылку для запуска приложения в PDF документе
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Создает ссылку для запуска приложения в PDF документе.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник для активного клика. |
| application | String | Путь к приложению, которое будет запущено. |
| page | Int32 | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный со ссылкой. |
| clr | Color | Цвет прямоугольника для активного клика. |
| actionName | Enum[] | Массив действий (члены перечисления PredefinedAction), соответствующий выполняемым пунктам меню в просмотрщике Acrobat. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Создает ссылку для запуска приложения в PDF документе.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник для активного клика. |
| application | String | Путь к приложению, которое будет запущено. |
| page | Int32 | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный со ссылкой. |
| clr | Color | Цвет прямоугольника для активного клика. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Создает ссылку для запуска приложения в PDF документе.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник для активного клика. |
| application | String | Путь к приложению, которое будет запущено. |
| page | Int32 | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный со ссылкой. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)