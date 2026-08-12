---
title: "System::Drawing::Graphics::BeginContainer метод"
linktitle: "BeginContainer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Graphics::BeginContainer method. Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер в C++."
type: docs
weight: 600
url: /ru/cpp/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() method


Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) method


Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dstrect | Rectangle | Прямоугольник, задающий масштабное преобразование нового контейнера. Используется вместе с **srcrect** |
| srcrect | Rectangle | Прямоугольник, задающий масштабное преобразование нового контейнера. Используется вместе с **dstrect** |
| unit | GraphicsUnit | Значение, определяющее единицу измерения нового контейнера |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Rectangle](../../rectangle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) method


Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dstrect | RectangleF | Прямоугольник, задающий масштабное преобразование нового контейнера. Используется вместе с **srcrect** |
| srcrect | RectangleF | Прямоугольник, задающий масштабное преобразование нового контейнера. Используется вместе с **dstrect** |
| unit | GraphicsUnit | Значение, определяющее единицу измерения нового контейнера |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [RectangleF](../../rectanglef/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
