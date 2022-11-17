---
title: PageNumberStamp
second_title: Aspose.PDF для справки по Java API
description: Представляет штамп номера страницы и используется для нумерации страниц.
type: docs
weight: 267
url: /ru/java/com.aspose.pdf/pagenumberstamp/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp), [com.aspose.pdf.TextStamp](../../com.aspose.pdf/textstamp)
```
public final class PageNumberStamp extends TextStamp
```

Представляет штамп номера страницы и используется для нумерации страниц.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageNumberStamp(String format)](#PageNumberStamp-java.lang.String-) | Инициализирует новый экземпляр класса PageNumberStamp. |
| [PageNumberStamp()](#PageNumberStamp--) | Инициализирует новый экземпляр класса PageNumberStamp. |
| [PageNumberStamp(FormattedText formattedText)](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Создает PageNumberStamp по форматированному тексту. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Получает нижнее поле штампа. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Возвращает шрифт по умолчанию |
| [getDefaultFontSize()](#getDefaultFontSize--) | Размер шрифта по умолчанию |
| [getDraw()](#getDraw--) | Это свойство определяет способ рисования штампа на странице. |
| [getFormat()](#getFormat--) | Получает строковое значение для штамповки номеров страниц. |
| [getHeight()](#getHeight--) | Желаемая высота штампа на странице. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание штампа на странице. |
| [getLeftMargin()](#getLeftMargin--) | Получает левое поле штампа. |
| [getMaxRowWidth()](#getMaxRowWidth--) | Максимальная высота строки для параметра WordWrap. |
| [getNumberingStyle()](#getNumberingStyle--) | Стиль нумерации, используемый этой маркой. |
| [getOpacity()](#getOpacity--) | Получает значение, указывающее непрозрачность штампа. |
| [getOutlineOpacity()](#getOutlineOpacity--) | Получает значение, указывающее непрозрачность контура штампа. |
| [getOutlineWidth()](#getOutlineWidth--) | Получает значение ширины контура штампа. |
| [getRightMargin()](#getRightMargin--) | Получает правое поле штампа. |
| [getRotate()](#getRotate--) | Получает поворот содержимого штампа в соответствии со значениями поворота. |
| [getRotateAngle()](#getRotateAngle--) | Получает угол поворота штампа в градусах. |
| [getStampId()](#getStampId--) | Получает идентификатор штампа. |
| [getStartingNumber()](#getStartingNumber--) | Получает значение номера стартовой страницы. |
| [getTextAlignment()](#getTextAlignment--) | Выравнивание текста внутри штампа. |
| [getTextState()](#getTextState--) | Получает текстовые свойства штампа. |
| [getTopMargin()](#getTopMargin--) | Получить верхнее поле штампа. |
| [getTreatYIndentAsBaseLine()](#getTreatYIndentAsBaseLine--) | Определяет начало координат для размещения текста. |
| [getValue()](#getValue--) | Получает строковое значение, которое используется в качестве штампа на странице. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание штампа на странице. |
| [getWidth()](#getWidth--) | Желаемая ширина штампа на странице. |
| [getXIndent()](#getXIndent--) | Получить горизонтальную координату штампа, начиная слева. |
| [getYIndent()](#getYIndent--) | Получить вертикальную координату штампа, начиная снизу. |
| [getZoom()](#getZoom--) | Получает коэффициент масштабирования штампа. |
| [getZoomX()](#getZoomX--) | Получает горизонтальный коэффициент масштабирования штампа. |
| [getZoomY()](#getZoomY--) | Получает коэффициент масштабирования штампа по вертикали. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Получает логическое значение, указывающее, что содержимое помечается как фон. |
| [isJustify()](#isJustify--) | Определяет выравнивание текста. |
| [isScale()](#isScale--) | Определяет масштабирование текста. |
| [isWordWrap()](#isWordWrap--) | Определяет перенос слов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Добавляет номер страницы. |
| [setBackground(boolean value)](#setBackground-boolean-) | Задает логическое значение, указывающее, что содержимое помечается как фон. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Устанавливает нижнее поле штампа. |
| [setDraw(boolean value)](#setDraw-boolean-) | Это свойство определяет способ рисования штампа на странице. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Задает строковое значение для штамповки номеров страниц. |
| [setHeight(double value)](#setHeight-double-) | Желаемая высота штампа на странице. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает Горизонтальное выравнивание штампа на странице. |
| [setJustify(boolean value)](#setJustify-boolean-) | Определяет выравнивание текста. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Устанавливает левое поле штампа. |
| [setMaxRowWidth(double value)](#setMaxRowWidth-double-) | Максимальная высота строки для параметра WordWrap. |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | Стиль нумерации, используемый этой маркой. |
| [setOpacity(double value)](#setOpacity-double-) | Задает значение, указывающее непрозрачность штампа. |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | Задает значение, указывающее непрозрачность контура штампа. |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | Устанавливает значение ширины контура штампа. |
| [setRightMargin(double value)](#setRightMargin-double-) | Устанавливает правое поле штампа. |
| [setRotate(int value)](#setRotate-int-) | Устанавливает поворот содержимого штампа в соответствии со значениями поворота. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Устанавливает угол поворота штампа в градусах. |
| [setScale(boolean value)](#setScale-boolean-) | Определяет масштабирование текста. |
| [setStampId(int value)](#setStampId-int-) | Устанавливает идентификатор штампа. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Устанавливает значение номера стартовой страницы. |
| [setTextAlignment(int value)](#setTextAlignment-int-) | Выравнивание текста внутри штампа. |
| [setTopMargin(double value)](#setTopMargin-double-) | Устанавливает верхнее поле штампа. |
| [setTreatYIndentAsBaseLine(boolean value)](#setTreatYIndentAsBaseLine-boolean-) | Определяет начало координат для размещения текста. |
| [setValue(String value)](#setValue-java.lang.String-) | Задает строковое значение, которое используется в качестве штампа на странице. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание штампа на странице. |
| [setWidth(double value)](#setWidth-double-) | Желаемая ширина штампа на странице. |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | Определяет перенос слов. |
| [setXIndent(double value)](#setXIndent-double-) | Установите горизонтальную координату штампа, начиная слева. |
| [setYIndent(double value)](#setYIndent-double-) | Установите вертикальную координату штампа, начиная снизу. |
| [setZoom(double value)](#setZoom-double-) | Получает коэффициент масштабирования штампа. |
| [setZoomX(double value)](#setZoomX-double-) | Устанавливает коэффициент масштабирования штампа по горизонтали. |
| [setZoomY(double value)](#setZoomY-double-) | Устанавливает коэффициент масштабирования штампа по вертикали. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PageNumberStamp(String format) {#PageNumberStamp-java.lang.String-}
```
public PageNumberStamp(String format)
```


Инициализирует новый экземпляр класса PageNumberStamp.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | java.lang.String | Строковое значение, используемое для штамповки. Дополнительные сведения см. в разделе Свойство Format. |

### PageNumberStamp() {#PageNumberStamp--}
```
public PageNumberStamp()
```


Инициализирует новый экземпляр класса PageNumberStamp. Формат установлен "\#".

### PageNumberStamp(FormattedText formattedText) {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
```
public PageNumberStamp(FormattedText formattedText)
```


Создает PageNumberStamp по форматированному тексту.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Форматированный текст, используемый для создания штампа номера страницы. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Получает нижнее поле штампа.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Возвращает шрифт по умолчанию

**Возвращает:**
[Font](../../com.aspose.pdf/font) - объект com.aspose.pdf.Font
### getDefaultFontSize() {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```


Размер шрифта по умолчанию

**Возвращает:**
float - плавающее значение
### getDraw() {#getDraw--}
```
public boolean getDraw()
```


Это свойство определяет способ рисования штампа на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст.

**Возвращает:**
boolean - логическое значение
### getFormat() {#getFormat--}
```
public String getFormat()
```


Получает строковое значение для штамповки номеров страниц. Значение должно включать char '\#', который в процессе штамповки заменяется номером страницы.

**Возвращает:**
java.lang.String — строковое значение
### getHeight() {#getHeight--}
```
public double getHeight()
```


Желаемая высота штампа на странице.

**Возвращает:**
двойное - двойное значение
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание штампа на странице.

**Возвращает:**
int - значение HorizontalAlignment
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Получает левое поле штампа.

**Возвращает:**
двойное - двойное значение
### getMaxRowWidth() {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```


Максимальная высота строки для параметра WordWrap.

**Возвращает:**
двойное - двойное значение
### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


Стиль нумерации, используемый этой маркой.

**Возвращает:**
int — значение стиля нумерации
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Получает значение, указывающее непрозрачность штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


Получает значение, указывающее непрозрачность контура штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


Получает значение ширины контура штампа. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Получает правое поле штампа.

**Возвращает:**
двойное - двойное значение
### getRotate() {#getRotate--}
```
public int getRotate()
```


Получает поворот содержимого штампа в соответствии со значениями поворота. Примечание. Это свойство предназначено для заданных углов, кратных 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, заданный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None.

**Возвращает:**
int - Значение поворота
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Получает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота.

**Возвращает:**
двойное - двойное значение
### getStampId() {#getStampId--}
```
public int getStampId()
```


Получает идентификатор штампа.

**Возвращает:**
int - Идентификатор штампа.
### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


Получает значение номера стартовой страницы. Остальные страницы будут нумероваться, начиная с этого значения.

**Возвращает:**
интервал - целочисленное значение
### getTextAlignment() {#getTextAlignment--}
```
public int getTextAlignment()
```


Выравнивание текста внутри штампа.

**Возвращает:**
int - значение HorizontalAlignment
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Получает текстовые свойства штампа. Подробнее см. в TextState.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Элемент TextState
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Получить верхнее поле штампа.

**Возвращает:**
двойное - двойное значение
### getTreatYIndentAsBaseLine() {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```


Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (нисходящая линия) текста.

**Возвращает:**
boolean - логическое значение
### getValue() {#getValue--}
```
public String getValue()
```


Получает строковое значение, которое используется в качестве штампа на странице.

**Возвращает:**
java.lang.String — строковое значение
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание штампа на странице.

**Возвращает:**
int — значение вертикального выравнивания
### getWidth() {#getWidth--}
```
public double getWidth()
```


Желаемая ширина штампа на странице.

**Возвращает:**
двойное - двойное значение
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Получить горизонтальную координату штампа, начиная слева.

**Возвращает:**
двойное - двойное значение
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Получить вертикальную координату штампа, начиная снизу.

**Возвращает:**
двойное - двойное значение
### getZoom() {#getZoom--}
```
public double getZoom()
```


Получает коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY разные, то свойство Zoom возвращает значение ZoomX.

**Возвращает:**
двойное - двойное значение
### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


Получает горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали.

**Возвращает:**
двойное - двойное значение
### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


Получает коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Получает логическое значение, указывающее, что содержимое помечается как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение равно false, содержимое штампа откладывается вверху.

**Возвращает:**
boolean - логическое значение
### isJustify() {#isJustify--}
```
public boolean isJustify()
```


Определяет выравнивание текста. Если для этого свойства установлено значение true, выравниваются как левый, так и правый края текста. Значение по умолчанию: ложь.

**Возвращает:**
boolean - логическое значение
### isScale() {#isScale--}
```
public boolean isScale()
```


Определяет масштабирование текста. Если для этого свойства установлено значение true и указано значение ширины, текст будет масштабироваться, чтобы соответствовать указанной ширине.

**Возвращает:**
boolean - логическое значение
### isWordWrap() {#isWordWrap--}
```
public boolean isWordWrap()
```


Определяет перенос слов. Если для этого свойства установлено значение true и указано значение ширины, текст будет разбит на несколько строк, чтобы соответствовать указанной ширине. Значение по умолчанию: ложь.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Добавляет номер страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для стемпинга. |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Задает логическое значение, указывающее, что содержимое помечается как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение равно false, содержимое штампа располагается вверху.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Устанавливает нижнее поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setDraw(boolean value) {#setDraw-boolean-}
```
public void setDraw(boolean value)
```


Это свойство определяет способ рисования штампа на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFormat(String value) {#setFormat-java.lang.String-}
```
public void setFormat(String value)
```


Задает строковое значение для штамповки номеров страниц. Значение должно включать char '\#', который в процессе штамповки заменяется номером страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Желаемая высота штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает Горизонтальное выравнивание штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Определяет выравнивание текста. Если для этого свойства установлено значение true, выравниваются как левый, так и правый края текста. Значение по умолчанию: ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Устанавливает левое поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setMaxRowWidth(double value) {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```


Максимальная высота строки для параметра WordWrap.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


Стиль нумерации, используемый этой маркой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение стиля нумерации |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Задает значение, указывающее непрозрачность штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


Задает значение, указывающее непрозрачность контура штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


Устанавливает значение ширины контура штампа. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Устанавливает правое поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Устанавливает поворот содержимого штампа в соответствии со значениями поворота. Примечание. Это свойство предназначено для заданных углов, кратных 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, заданный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


Устанавливает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | угол поворота |

### setScale(boolean value) {#setScale-boolean-}
```
public void setScale(boolean value)
```


Определяет масштабирование текста. Если для этого свойства установлено значение true и указано значение ширины, текст будет масштабироваться, чтобы соответствовать указанной ширине.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Устанавливает идентификатор штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Новое значение идентификатора штампа. |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


Устанавливает значение номера стартовой страницы. Остальные страницы будут нумероваться, начиная с этого значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public void setTextAlignment(int value)
```


Выравнивание текста внутри штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Устанавливает верхнее поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setTreatYIndentAsBaseLine(boolean value) {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```


Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (нисходящая линия) текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Задает строковое значение, которое используется в качестве штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение вертикального выравнивания |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Желаемая ширина штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


Определяет перенос слов. Если для этого свойства установлено значение true и указано значение ширины, текст будет разбит на несколько строк, чтобы соответствовать указанной ширине. Значение по умолчанию: ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Установите горизонтальную координату штампа, начиная слева.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Установите вертикальную координату штампа, начиная снизу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


Получает коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY разные, то свойство Zoom возвращает значение ZoomX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


Устанавливает коэффициент масштабирования штампа по горизонтали. Позволяет масштабировать штамп по горизонтали.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


Устанавливает коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
