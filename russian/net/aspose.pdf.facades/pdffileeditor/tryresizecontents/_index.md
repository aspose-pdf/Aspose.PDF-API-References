---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Изменяет размер содержимого страниц документа
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному файлу. |
| pages | Int32[] | Массив страниц, которые нужно изменить. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не вызывает исключение, если операция не удалась.

### См. также

* класс [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток исходного файла. |
| pages | Int32[] | Массив страниц, которые нужно изменить. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не вызывает исключение, если операция не удалась.

### См. также

* класс [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Изменяет размер содержимого страниц документа.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток с исходным документом. |
| destination | Stream | Поток с целевым документом. |
| pages | Int32[] | Массив индексов страниц. |
| parameters | ContentsResizeParameters | Параметры изменения размера. |

### Возвращаемое значение

Возвращает true, если успешно.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### См. также

* класс [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в единицах пространства по умолчанию.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в который будет сохранен результирующий документ. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в единицах пространства по умолчанию. |
| newHeight | Double | Новая высота содержимого страницы в единицах пространства по умолчанию. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг страницы добавляются пустые поля.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### См. также

* класс [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)