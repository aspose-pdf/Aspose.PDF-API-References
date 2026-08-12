---
title: "Aspose::Pdf::Annotations::ColorBarAnnotation class"
linktitle: "ColorBarAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::ColorBarAnnotation class. Класс, представляющий аннотацию ColorBarAnnotation. Свойство Color игнорируется, вместо него используется цвет ColorsOfCMYK. При создании соотношение ширины и высоты определяет ориентацию аннотации — горизонтальную или вертикальную. Затем проверяется, находится ли прямоугольник аннотации за пределами TrimBox, и если нет, он смещается к ближайшему расположению за пределами TrimBox с учётом ориентации аннотации. Возможно уменьшить ширину (высоту), чтобы аннотация помещалась за пределами TrimBox. Если места для размещения нет, ширина/высота могут быть установлены в ноль (в этом случае аннотация присутствует на странице, но не отображается) в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class


Class representing [ColorBarAnnotation](./) annotation. Property [Color](../../aspose.pdf/color/) игнорируется, вместо него используется цвет [ColorsOfCMYK](../colorsofcmyk/). При создании соотношение ширины и высоты определяет ориентацию аннотации — горизонтальную или вертикальную. Затем проверяется, находится ли прямоугольник аннотации за пределами TrimBox, и если нет, он смещается к ближайшему расположению за пределами TrimBox с учётом ориентации аннотации. Возможно уменьшить ширину (высоту), чтобы аннотация помещалась за пределами TrimBox. Если места для размещения нет, ширина/высота могут быть установлены в ноль (в этом случае аннотация присутствует на странице, но не отображается).

```cpp
class ColorBarAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Обновите параметры и внешний вид в соответствии с матричным преобразованием и перемещением за пределы TrimBox, если необходимо. |
| [ColorBarAnnotation](./colorbarannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, ColorsOfCMYK) | Создаёт новую аннотацию ColorBar на указанной странице. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_ColorOfCMYK](./get_colorofcmyk/)() const | Получает цвет (один из cyan, magenta, yellow, black), которым рисуется аннотация. |
| [set_ColorOfCMYK](./set_colorofcmyk/)(ColorsOfCMYK) | Устанавливает цвет (один из cyan, magenta, yellow, black), которым рисуется аннотация. |
## См. также

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
