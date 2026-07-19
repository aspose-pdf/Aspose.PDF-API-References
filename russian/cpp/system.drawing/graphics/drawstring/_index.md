---
title: "System::Drawing::Graphics::DrawString метод"
linktitle: "DrawString"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Graphics::DrawString метод. Рисует указанную строку в указанном месте, используя указанный шрифт и кисть в C++."
type: docs
weight: 2800
url: /ru/cpp/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Отрисовывает указанную строку в указанном месте, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Строка для рисования |
| шрифт | const SharedPtr\<Font\>\& | Шрифт для использования |
| brush | const SharedPtr\<Brush\>\& | Объект [Brush](../../brush/) для использования при рисовании |
| x | float | Координата X положения верхнего левого угла нарисованной строки |
| y | float | Координата Y положения верхнего левого угла нарисованной строки |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Указан формат строки |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Отрисовывает указанную строку в указанном месте, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Строка для рисования |
| шрифт | const SharedPtr\<Font\>\& | Шрифт для использования |
| brush | const SharedPtr\<Brush\>\& | Объект [Brush](../../brush/) для использования при рисовании |
| topLeft | PointF | Указывает положение верхнего левого угла нарисованной строки |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Указан формат строки |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Отрисовывает указанную строку в указанном прямоугольнике, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Строка для рисования |
| шрифт | const SharedPtr\<Font\>\& | Шрифт для использования |
| brush | const SharedPtr\<Brush\>\& | Объект [Brush](../../brush/) для использования при рисовании |
| layoutRectangle | RectangleF | Указывает прямоугольник, в котором будет рисоваться строка |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Указан формат строки |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
