---
title: "Page.AddImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Page. Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения."
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
| bbox | Rectangle | Bbox изображения. |
| autoAdjustRectangle | Boolean | Отрегулировать изображение в центре входного прямоугольника. |

### См. также

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Добавляет поисковое изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| hocr | String | hocr изображения. |
| imageStream | Stream | Поток изображения. |
| imageRect | Rectangle | Позиция изображения. |
| bbox | Rectangle | bbox изображения. |

### См. также

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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
| saveImageProportions | Boolean | Если флаг установлен в true, изображение размещается в позиции прямоугольника; иначе размер прямоугольника становится равным размеру изображения. |
| bbox | Rectangle | bbox изображения. |

### См. также

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


