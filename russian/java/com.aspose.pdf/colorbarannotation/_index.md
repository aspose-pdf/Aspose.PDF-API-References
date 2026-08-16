---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс, представляющий аннотацию ColorBarAnnotation. Свойство Color игнорируется, вместо него используется цвет ColorsOfCMYK. При создании соотношение ширины и высоты определяет ориентацию."
type: docs
weight: 680
url: /ru/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Класс, представляющий аннотацию ColorBarAnnotation. Свойство Color игнорируется, вместо него используется цвет ColorsOfCMYK. При создании соотношение ширины и высоты определяет ориентацию аннотации — горизонтальную или вертикальную. Затем проверяется, находится ли прямоугольник аннотации за пределами TrimBox, и если нет, он смещается к ближайшему месту за пределами TrimBox с учётом ориентации аннотации. Возможно уменьшить ширину (высоту), чтобы аннотация помещалась за пределами TrimBox. Если места для размещения нет, ширина/высота могут быть установлены в ноль (в этом случае аннотация присутствует на странице, но не отображается).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Создаёт новую аннотацию ColorBar на указанной странице. По умолчанию ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Создаёт новую аннотацию ColorBar на указанной странице. |

## Методы

| Метод | Описание |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает объект‑посетитель для обработки аннотации. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием и перемещением за пределы TrimBox при необходимости. |
| [getAnnotationType](#getAnnotationType--) | Получает тип аннотации. |
| [getColorOfCMYK](#getColorOfCMYK--) | Получает или задает цвет (один из циан, магента, желтый, черный), для которого аннотация рисуется. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Получает или задает цвет (один из циан, магента, желтый, черный), для которого аннотация рисуется. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Создаёт новую аннотацию ColorBar на указанной странице. По умолчанию ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Создаёт новую аннотацию ColorBar на указанной странице.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Принимает объект‑посетитель для обработки аннотации.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Обновляет параметры и внешний вид в соответствии с матричным преобразованием и перемещением за пределы TrimBox при необходимости.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Получает тип аннотации.

**Returns:**
int значение

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Получает или задает цвет (один из циан, магента, желтый, черный), для которого аннотация рисуется.

**Returns:**
Элемент ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Получает или задает цвет (один из циан, магента, желтый, черный), для которого аннотация рисуется.
