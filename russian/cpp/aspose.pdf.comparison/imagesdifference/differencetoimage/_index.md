---
title: "Метод Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage"
linktitle: "DifferenceToImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage. Преобразует массив различий в битмап-изображение с использованием указанных цветов в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/imagesdifference/differencetoimage/
---
## ImagesDifference::DifferenceToImage method


Преобразует массив различий в растровое изображение, используя указанные цвета.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage(const System::SharedPtr<Color> &color, const System::SharedPtr<Color> &backgroundColor)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| color | const System::SharedPtr\<Color\>\& | Цвет для ненулевых различий. |
| backgroundColor | const System::SharedPtr\<Color\>\& | Фоновый цвет для нулевых различий. |

### ReturnValue

Битмап-изображение, представляющее массив различий.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Color](../../../aspose.pdf/color/)
* Class [ImagesDifference](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
