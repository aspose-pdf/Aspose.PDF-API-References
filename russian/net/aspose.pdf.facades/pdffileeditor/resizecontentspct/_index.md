---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в процентах."
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в процентах.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | Stream | Поток, содержащий исходный документ. |
| destination | Stream | Поток, в котором будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в процентах. |
| newHeight | Double | Новая высота содержимого страницы в процентах. |

### Возвращаемое значение

true, если изменение размера выполнено успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//изменить размер всех страниц документа
null, 
//новая ширина содержимого = 60 % от исходного размера
60, 
//новая высота содержимого = 60 % от исходного размера
60);
// Оставшаяся область страницы будет пустой (поля страницы). Размер левого и правого полей равен (100 % - 60 %) / 2 = 20 %.
// То же самое для верхних и нижних полей.
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в процентах.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | String | Путь к исходному документу. |
| destination | String | Путь, где будет сохранён результирующий документ. |
| страницы | Int32[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | Double | Новая ширина содержимого страницы в процентах. |
| newHeight | Double | Новая высота содержимого страницы в процентах. |

### Возвращаемое значение

true, если изменение размера прошло успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//изменить размер всех страниц документа
null, 
//новая ширина содержимого = 60 % от исходного размера
60, 
//новая высота содержимого = 60 % от исходного размера
60);
// Оставшаяся область страницы будет пустой (поля страницы). Размер левого и правого полей равен (100 % - 60 %) / 2 = 20 %.
// То же самое для верхних и нижних полей.
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


