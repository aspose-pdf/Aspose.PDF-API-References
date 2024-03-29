---
title: ResizeContents
second_title: Aspose.PDF для справочника API .NET
description: Изменяет размер содержимого страниц в документе. Если страница сжата вокруг страницы добавляются пустые поля.
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному документу. |
| destination | String | Путь к целевому документу. |
| pages | Int32[] | Массив индексов страниц (индекс страницы начинается с 1). |
| parameters | ContentsResizeParameters | Параметры изменения размера страницы. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левое поле = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
    null,
    //правое поле 10% страницы 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхнее поле = 10% от высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Document | Исходный документ. |
| pages | Int32[] | Список индексов страниц. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левое поле = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
    null,
    //правое поле 10% страницы 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхнее поле = 10% от высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Document | Исходный документ. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левое поле = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
    null,
    //правое поле 10% страницы 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхнее поле = 10% от высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Изменяет размеры содержимого страниц документа.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток с исходным документом. |
| destination | Stream | Потоковая передача с целевым документом. |
| pages | Int32[] | Массив индексов страниц. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |

### Возвращаемое значение

Возвращает true в случае успеха.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левое поле = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
    null,
    //правое поле 10% страницы 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхнее поле = 10% от высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, где результирующий документ будет сохранен. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | Double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

### Возвращаемое значение

Истинно, если изменение размера прошло успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//изменить размер всех страниц документа
null, 
//ширина нового содержимого = 200
200, 
// высота нового содержимого = 300
300);
// остальная часть страницы будет пустой
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному документу. |
| destination | String | Путь, по которому будет сохранен результирующий документ. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | Double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//изменить размер всех страниц документа
null, 
//ширина нового содержимого = 200
200, 
// высота нового содержимого = 300
300);
// остальная часть страницы будет пустой
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному файлу. |
| pages | Int32[] | Массив страниц, размер которых нужно изменить. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток исходного файла. |
| pages | Int32[] | Массив страниц, размер которых нужно изменить. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
