---
title: TryResizeContents
second_title: Aspose.PDF для справочника API .NET
description: Изменяет размер содержимого страниц в документе. Если страница сжата вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.
type: docs
weight: 480
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному файлу. |
| pages | Int32[] | Массив страниц для изменения размера. |
| parameters | ContentsResizeParameters | Изменить размер параметров. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryResizeContents подобен методу ResizeContents, за исключением того, что метод TryResizeContents не генерирует исключение, если операция не удалась.

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток исходного файла. |
| pages | Int32[] | Массив страниц для изменения размера. |
| parameters | ContentsResizeParameters | Изменить размер параметров. |
| response | HttpResponse | Объект HttpResponse, в котором сохраняется результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryResizeContents подобен методу ResizeContents, за исключением того, что метод TryResizeContents не генерирует исключение, если операция не удалась.

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
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
| parameters | ContentsResizeParameters | Изменить размер параметров. |

### Возвращаемое значение

В случае успеха возвращает true.

### Примечания

Метод TryResizeContents подобен методу ResizeContents, за исключением того, что метод TryResizeContents не генерирует исключение, если операция не удалась.

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
     //верхнее поле = 10% от height
    PdfFileEditor.ContentsResizeValue.Percents(10),
     //высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
     //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указан в пространственных единицах по умолчанию.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в котором будет сохранен результирующий документ. |
| pages | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | Double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryResizeContents подобен методу ResizeContents, за исключением того, что метод TryResizeContents не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
 //изменить размер всех страниц document
null, 
 // ширина нового содержимого = 200
200, 
 //высота нового содержимого = 300
300);
 // остальная часть страницы будет пустой
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | String | Путь к исходному документу. |
| destination | String | Путь документа назначения. |
| pages | Int32[] | Массив индексов страниц (индекс страниц начинается с 1). |
| parameters | ContentsResizeParameters | Параметры изменения размера страницы. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

### Примечания

Метод TryResizeContents подобен методу ResizeContents, за исключением того, что метод TryResizeContents не генерирует исключение, если операция не удалась.

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
     //верхнее поле = 10% от height
    PdfFileEditor.ContentsResizeValue.Percents(10),
     //высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
     //нижнее поле 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Смотрите также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
