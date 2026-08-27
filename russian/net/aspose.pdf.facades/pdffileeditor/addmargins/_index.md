---
title: "PdfFileEditor.AddMargins"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию."
type: docs
weight: 220
url: /ru/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в котором будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левый отступ. |
| rightMargin | Double | Правый отступ. |
| topMargin | Double | Верхний отступ. |
| bottomMargin | Double | Нижний отступ. |

### Возвращаемое значение

true, если операция была успешной.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //обработать страницы 1, 2, 3
    new int[] { 1, 2, 3}, 
    //левый отступ равен 10 единиц
    10, 
    //правый отступ равен 5 единиц
    5, 
    //верхний отступ равен 5 единиц
    5, 
    //нижний отступ равен 5 единиц
    5);
    dest.Close();
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | String | Путь к исходному документу. |
| destination | String | Путь, где будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | Double | Левый отступ. |
| rightMargin | Double | Правый отступ. |
| topMargin | Double | Верхний отступ. |
| bottomMargin | Double | Нижний отступ. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //обработать страницы 1, 2, 3
    new int[] { 1, 2, 3}, 
    //левый отступ равен 10 единиц
    10, 
    //правый отступ равен 5 единиц
    5, 
    //верхний отступ равен 5 единиц
    5, 
    //нижний отступ равен 5 единиц
    5);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


