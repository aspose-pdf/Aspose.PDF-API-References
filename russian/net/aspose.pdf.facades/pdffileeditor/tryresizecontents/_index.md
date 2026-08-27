---
title: "PdfFileEditor.TryResizeContents"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Изменяет размер содержимого страниц документа"
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Изменяет размер содержимого страниц документа.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | Stream | Поток с исходным документом. |
| destination | Stream | Поток с целевым документом. |
| страницы | Int32[] | Массив индексов страниц. |
| параметры | ContentsResizeParameters | Параметры изменения размера. |

### Возвращаемое значение

Возвращает true, если успешно.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левый отступ = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //новая ширина содержимого рассчитывается автоматически как ширина - левый отступ - правый отступ (100% - 10% - 10% = 80%)
    null,
    //правый отступ равен 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхний отступ = 10% высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижний отступ составляет 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### См. также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в единицах пространства по умолчанию.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в котором будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в единицах пространства по умолчанию. |
| newHeight | Double | Новая высота содержимого страницы в единицах пространства по умолчанию. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//изменить размер всех страниц документа
null, 
//новая ширина содержимого = 200
200, 
//новая высота содержимого = 300
300);
// оставшаяся часть страницы будет пустой
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | String | Путь к исходному документу. |
| destination | String | Путь к целевому документу. |
| страницы | Int32[] | Массив индексов страниц (индекс страницы начинается с 1). |
| параметры | ContentsResizeParameters | Параметры изменения размера страницы. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

## Примечания

Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //левый отступ = 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //новая ширина содержимого рассчитывается автоматически как ширина - левый отступ - правый отступ (100% - 10% - 10% = 80%)
    null,
    //правый отступ равен 10% ширины страницы
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //верхний отступ = 10% высоты
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //высота нового содержимого рассчитывается автоматически (аналогично ширине)
    null,
    //нижний отступ составляет 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### См. также

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


