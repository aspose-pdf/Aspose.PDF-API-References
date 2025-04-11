---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в единицах измерения по умолчанию
type: docs
weight: 220
url: /ru/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в единицах измерения по умолчанию.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в который будет сохранен результирующий документ. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левое поле. |
| rightMargin | Double | Правое поле. |
| topMargin | Double | Верхнее поле. |
| bottomMargin | Double | Нижнее поле. |

### Возвращаемое значение

true, если операция была успешной.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в единицах измерения по умолчанию.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному документу. |
| destination | String | Путь, по которому будет сохранен результирующий документ. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левое поле. |
| rightMargin | Double | Правое поле. |
| topMargin | Double | Верхнее поле. |
| bottomMargin | Double | Нижнее поле. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)