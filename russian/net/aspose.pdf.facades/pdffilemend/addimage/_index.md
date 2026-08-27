---
title: "PdfFileMend.AddImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileMend. Добавляет изображение на указанную страницу PDF‑документа в заданных координатах"
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNum | Int32 | Номер страницы, которая получит изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### См. также

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNum | Int32 | Номер страницы, которая получит изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры графического композитинга для изображения. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### См. также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### См. также

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры графического композитинга для изображений. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### См. также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNum | Int32 | Номер страницы, которая получит изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### См. также

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNum | Int32 | Номер страницы, которая получит изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры графического композитинга для изображений. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### См. также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### См. также

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры графического композитинга для изображений. |

### Возвращаемое значение

True если успешно, false в противном случае.

## Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### См. также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


