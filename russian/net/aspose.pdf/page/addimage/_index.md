---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Метод Page. Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения
type: docs
weight: 350
url: /ru/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток изображения. |
| imageRect | Rectangle | Позиция изображения. |
| bbox | Rectangle | Ограничивающий прямоугольник изображения. |
| autoAdjustRectangle | Boolean | Центрировать изображение в пределах входного прямоугольника. |

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Добавляет поисковое изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| hocr | String | HOCR изображения. |
| imageStream | Stream | Поток изображения. |
| imageRect | Rectangle | Позиция изображения. |
| bbox | Rectangle | Ограничивающий прямоугольник изображения. |

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Добавляет изображение на страницу и размещает его в зависимости от позиции прямоугольника изображения.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток изображения. |
| imageRect | Rectangle | Позиция изображения по умолчанию на странице. |
| imageWidth | Int32 | Ширина изображения. |
| imageHeight | Int32 | Высота изображения. |
| saveImageProportions | Boolean | Если флаг установлен в true, изображение размещается в позиции прямоугольника; в противном случае размер прямоугольника становится равным размеру изображения. |
| bbox | Rectangle | Ограничивающий прямоугольник изображения. |

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | String | Путь к изображению. |
| rectangle | Rectangle | Позиция изображения. |

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)