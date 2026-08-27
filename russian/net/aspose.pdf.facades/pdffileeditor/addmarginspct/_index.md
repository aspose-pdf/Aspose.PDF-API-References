---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfFileEditor метод. Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в процентах от исходного размера страницы"
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в процентах от исходного размера страницы.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в котором будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | Double | Правое поле в процентах от исходного размера страницы. |
| topMargin | Double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | Double | Нижнее поле в процентах от исходного размера страницы. |

### Возвращаемое значение

true если действие выполнено успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //обработать страницы 1, 2, 3
    new int[] { 1, 2, 3}, 
    //левое поле составляет 15% от ширины страницы
    15, 
    //правое поле составляет 10% от ширины страницы
    10, 
    //верхнее поле составляет 20% от ширины страницы
    20, 
    //нижнее поле составляет 5% от ширины страницы
    5);
    dest.Close();
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в процентах от исходного размера страницы.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | String | Путь к исходному документу. |
| destination | String | Путь, где будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | Double | Правое поле в процентах от исходного размера страницы. |
| topMargin | Double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | Double | Нижнее поле в процентах от исходного размера страницы. |

### Возвращаемое значение

true если изменение размера прошло успешно

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //обработать страницы 1, 2, 3
    new int[] { 1, 2, 3}, 
    //левое поле составляет 15% от ширины страницы
    15, 
    //правое поле составляет 10% от ширины страницы
    10, 
    //верхнее поле составляет 20% от ширины страницы
    20, 
    //нижнее поле составляет 5% от ширины страницы
    5);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


