---
title: AddImage
second_title: Aspose.PDF для справочника API .NET
description: Добавляет изображение на указанную страницу документа PDF с указанными координатами.
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Добавляет изображение на указанную страницу документа PDF с указанными координатами.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNum | Int32 | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Смотрите также

* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Добавляет изображение на указанную страницу документа PDF с указанными координатами.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNum | Int32 | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры компоновки графики для изображения. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Смотрите также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Добавляет изображение на указанные страницы документа PDF с указанными координатами.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Смотрите также

* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Добавляет изображение на указанные страницы документа PDF с указанными координатами.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Входной поток изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры компоновки графики для изображений. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Смотрите также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Добавляет изображение на указанную страницу документа PDF с указанными координатами.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNum | Int32 | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Смотрите также

* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Добавляет изображение на указанную страницу документа PDF с указанными координатами.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNum | Int32 | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры компоновки графики для изображений. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Смотрите также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Добавляет изображение на указанные страницы документа PDF с указанными координатами.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Смотрите также

* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Добавляет изображение на указанные страницы документа PDF с указанными координатами.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | String | Путь к входному файлу изображения. |
| pageNums | Int32[] | Количество страниц, которые получат изображение. |
| lowerLeftX | Single | Нижний левый x прямоугольника изображения. |
| lowerLeftY | Single | Нижний левый угол y прямоугольника изображения. |
| upperRightX | Single | Верхний правый x прямоугольника изображения. |
| upperRightY | Single | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | CompositingParameters | Параметры компоновки графики для изображений. |

### Возвращаемое значение

Истинно, если успех ложен, в противном случае.

### Примеры

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Смотрите также

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* пространство имен [Aspose.Pdf.Facades](../../pdffilemend)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
