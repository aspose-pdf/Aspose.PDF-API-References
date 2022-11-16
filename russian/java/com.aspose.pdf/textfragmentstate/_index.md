---
title: TextFragmentState
second_title: Aspose.PDF для справки по Java API
description: Представляет текстовое состояние текстового фрагмента.
type: docs
weight: 375
url: /ru/java/com.aspose.pdf/textfragmentstate/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextState](../../com.aspose.pdf/textstate)
```
public final class TextFragmentState extends TextState
```

Представляет текстовое состояние текстового фрагмента.

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object.
 
  // Открыть документ
  Document doc = new Document("D:\\Tests\\input.pdf");
  
  // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «hello world».
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Принять поглотитель для первой страницы
  doc.getPages().get(1).accept(absorber);
  
  // Изменить цвет переднего плана первого вхождения текста
  absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
  // Изменить размер шрифта первого вхождения текста
  absorber.getTextFragments().get(1).getTextState().setFontSize ( 15);
  
  // Сохранить документ
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

Предоставляет возможность изменить следующие свойства текста: шрифт (свойство TextFragmentState.Font) размер шрифта (свойство TextFragmentState.FontSize) стиль шрифта (свойство TextFragmentState.FontStyle) цвет переднего плана (свойство TextFragmentState.ForegroundColor) цвет фона (свойство TextFragmentState.BackgroundColor) Обратите внимание, что изменение свойств TextFragmentState может привести к изменению внутренней коллекции TextFragment.Segments, поскольку TextFragment является агрегатным объектом и может переупорядочивать внутренние сегменты или объединять их в один сегмент. Если вам нужно оставить коллекцию TextFragment.Segments без изменений, измените внутренние сегменты по отдельности.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextFragmentState(TextFragment fragment)](#TextFragmentState-com.aspose.pdf.TextFragment-) | Инициализирует новый экземпляр объекта TextFragmentState с указанным объектом TextFragment. |
## Поля

| Поле | Описание |
| --- | --- |
| [TabTag](#TabTag) | Вы можете поместить этот тег в текст, чтобы объявить табуляцию. |
| [TabstopDefaultValue](#TabstopDefaultValue) | Значение табуляции по умолчанию в ширине пробела шрифта по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Применяет настройки из другого textState |
| [applyChangesFrom(TextState textState, boolean groupChangesOnly)](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Применяет настройки из другого textState |
| [calculateFontSize(String str, Rectangle rect)](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Вычисляет размер шрифта для прямоугольника. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Задает цвет фона текста, представленного объектом TextFragment. |
| [getCharacterSpacing()](#getCharacterSpacing--) | Получает межсимвольный интервал текста, представленный объектом TextFragment. |
| [getClass()](#getClass--) |  |
| [getDrawTextRectangleBorder()](#getDrawTextRectangleBorder--) | Получает флаг, если граница текстового прямоугольника нарисована. |
| [getFont()](#getFont--) | Получает шрифт текста, представленного объектом TextFragment. |
| [getFontSize()](#getFontSize--) | Получает размер шрифта текста, представленного объектом TextFragment. |
| [getFontStyle()](#getFontStyle--) | Задает стиль шрифта текста, представленного объектом TextFragment |
| [getForegroundColor()](#getForegroundColor--) | Получает цвет переднего плана текста, представленного объектом TextFragment. |
| [getFormattingOptions()](#getFormattingOptions--) | Получает или задает параметры форматирования. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Выравнивает текст по горизонтали. |
| [getHorizontalScaling()](#getHorizontalScaling--) | Получает горизонтальное масштабирование текста, представленного объектом TextFragment. |
| [getLineSpacing()](#getLineSpacing--) | Получает межстрочный интервал текста. |
| [getRenderingMode()](#getRenderingMode--) | Получает или задает режим рендеринга текста. |
| [getRotation()](#getRotation--) | Получает или задает угол поворота в градусах. |
| [getStrikeOut()](#getStrikeOut--) | Вычеркивает текст, представленный объектом TextFragment. |
| [getStrokingColor()](#getStrokingColor--) | Получает или задает операции обводки цветом при рендеринге TextFragment (обводка текста, граница прямоугольника) |
| [getTabStops()](#getTabStops--) | Получает позиции табуляции для текста. |
| [getTextHeight()](#getTextHeight--) | Получает высоту текста, представленную объектом TextFragment. |
| [getUnderline()](#getUnderline--) |  Получает или задает подчеркивание для текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект |
| [getWordSpacing()](#getWordSpacing--) | Получает межсловный интервал в тексте. |
| [hashCode()](#hashCode--) |  |
| [isInvisible()](#isInvisible--) | Получает невидимость текста. |
| [isSubscript()](#isSubscript--) | Получает или задает нижний индекс текста, представленного объектом TextFragment. |
| [isSuperscript()](#isSuperscript--) | Получает или задает верхний индекс текста, представленного объектом TextFragment. |
| [isUnderline()](#isUnderline--) | Получает подчеркивание текста, представленного объектом TextFragment. |
| [measureString(String str)](#measureString-java.lang.String-) | Измеряет струну. |
| [measureString(String str, boolean insideLine)](#measureString-java.lang.String-boolean-) | Измеряет струну. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) |  Устанавливает цвет фона текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | Задает интервал между символами текста, представленного объектом TextFragment. |
| [setDrawTextRectangleBorder(boolean value)](#setDrawTextRectangleBorder-boolean-) | Устанавливает флаг отрисовки границы текстового прямоугольника. |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Задает шрифт текста, представленного объектом TextFragment |
| [setFontSize(float value)](#setFontSize-float-) | Устанавливает размер шрифта текста, представленного объектом TextFragment |
| [setFontSizeSuppressedUpdate(float value)](#setFontSizeSuppressedUpdate-float-) | Устанавливает размер шрифта текста, который необходимо отключить при обновлении. |
| [setFontStyle(int value)](#setFontStyle-int-) |  Устанавливает стиль шрифта текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект |
| [setFontSuppressedUpdate(Font value)](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Получает шрифт текста, который желает отключить обновление. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Задает цвет переднего плана текста, представленного объектом TextFragment. |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Получает или задает параметры форматирования. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Задает горизонтальное выравнивание текста. |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | Задает горизонтальное масштабирование текста, представленного объектом TextFragment. |
| [setInvisible(boolean value)](#setInvisible-boolean-) | Устанавливает невидимость текста. |
| [setLineSpacing(float value)](#setLineSpacing-float-) | Устанавливает межстрочный интервал текста. |
| [setRenderingMode(int value)](#setRenderingMode-int-) | Получает или задает режим рендеринга текста. |
| [setRotation(double value)](#setRotation-double-) | Получает или задает угол поворота в градусах. |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | Устанавливает зачеркивание для текста, представленного объектом TextFragment. |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | Получает или задает операции обводки цветом при рендеринге TextFragment (обводка текста, граница прямоугольника) |
| [setSubscript(boolean value)](#setSubscript-boolean-) | Получает или задает нижний индекс текста, представленного объектом TextFragment. |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | Получает или задает верхний индекс текста, представленного объектом TextFragment. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Устанавливает подчеркивание для текста, представленного объектом TextFragment. |
| [setWordSpacing(float value)](#setWordSpacing-float-) | Устанавливает межсловный интервал в тексте. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragmentState(TextFragment fragment) {#TextFragmentState-com.aspose.pdf.TextFragment-}
```
public TextFragmentState(TextFragment fragment)
```


Инициализирует новый экземпляр объекта TextFragmentState с указанным объектом TextFragment. Эта инициализация TextFragmentState не поддерживается. TextFragmentState доступен только со свойством TextFragment.TextState.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | Текстовый фрагмент объекта. |

### TabTag {#TabTag}
```
public static final String TabTag
```


Вы можете поместить этот тег в текст, чтобы объявить табуляцию.

--------------------

Это действует только в паре с TabStops.

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```


Значение табуляции по умолчанию в ширине пробела шрифта по умолчанию.

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Применяет настройки из другого textState

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовый объект состояния.

--------------------

 Будут скопированы только те свойства, которые были изменены явно.|

### applyChangesFrom(TextState textState, boolean groupChangesOnly) {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
```
public void applyChangesFrom(TextState textState, boolean groupChangesOnly)
```


Применяет настройки из другого textState

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовый объект состояния. |
| groupChangesOnly | boolean | если true, наследовать только групповые изменения (без выделения сегментов в один сегмент) |

### calculateFontSize(String str, Rectangle rect) {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
```
public double calculateFontSize(String str, Rectangle rect)
```


Вычисляет размер шрифта для прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Строковое значение |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

**Возвращает:**
двойное - двойное значение
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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Задает цвет фона текста, представленного объектом TextFragment.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - значение Цвет объекта
### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


Получает межсимвольный интервал текста, представленный объектом TextFragment.

**Возвращает:**
float - плавающее значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDrawTextRectangleBorder() {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```


Получает флаг, если граница текстового прямоугольника нарисована.

**Возвращает:**
boolean - логическое значение
### getFont() {#getFont--}
```
public Font getFont()
```


Получает шрифт текста, представленного объектом TextFragment.

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Значение шрифта
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Получает размер шрифта текста, представленного объектом TextFragment.

**Возвращает:**
float - плавающее значение
### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


Задает стиль шрифта текста, представленного объектом TextFragment

**Возвращает:**
int - элемент FontStyles
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Получает цвет переднего плана текста, представленного объектом TextFragment.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта
### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


Получает или задает параметры форматирования. Настройка параметров будет эффективна только в сценариях с генератором.

**Возвращает:**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - Экземпляр TextFormattingOptions
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Выравнивает текст по горизонтали.

--------------------

HorizontalAlignment.None равно HorizontalAlignment.Left. Обратите внимание, что свойство TextFragmentState.VerticalAlignment работает только в новых сценариях генерации документов.

**Возвращает:**
int - значение HorizontalAlignment
### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


Получает горизонтальное масштабирование текста, представленного объектом TextFragment.

**Возвращает:**
float - плавающее значение
### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


Получает межстрочный интервал текста.

**Возвращает:**
float - плавающее значение

--------------------

Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Геттер свойства LineSpacing работает для объекта в случае, если он был явно установлен ранее с помощью установщика LineSpacing для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.
### getRenderingMode() {#getRenderingMode--}
```
public int getRenderingMode()
```


Получает или задает режим рендеринга текста.

**Возвращает:**
инт
### getRotation() {#getRotation--}
```
public double getRotation()
```


Получает или задает угол поворота в градусах.

**Возвращает:**
двойное - двойное значение
### getStrikeOut() {#getStrikeOut--}
```
public boolean getStrikeOut()
```


Вычеркивает текст, представленный объектом TextFragment.

**Возвращает:**
boolean - логическое значение
### getStrokingColor() {#getStrokingColor--}
```
public Color getStrokingColor()
```


Получает или задает операции обводки цветом при рендеринге TextFragment (обводка текста, граница прямоугольника)

**Возвращает:**
[Color](../../com.aspose.pdf/color)
### getTabStops() {#getTabStops--}
```
public TabStops getTabStops()
```


Получает позиции табуляции для текста.

--------------------

Обратите внимание, что свойство Tabstops работает только в новых сценариях генерации документов. Позиции табуляции могут быть добавлены во время инициализации TextFragment. Табуляции должны быть построены перед текстом.

**Возвращает:**
[TabStops](../../com.aspose.pdf/tabstops) - Объект TabStops
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Получает высоту текста, представленную объектом TextFragment.

**Возвращает:**
float - плавающее значение
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


 Получает или задает подчеркивание для текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект

**Возвращает:**
boolean - логическое значение
### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```


Получает межсловный интервал в тексте.

**Возвращает:**
float - плавающее значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isInvisible() {#isInvisible--}
```
public boolean isInvisible()
```


Получает невидимость текста.

**Возвращает:**
boolean - логическое значение
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Получает или задает нижний индекс текста, представленного объектом TextFragment.

**Возвращает:**
boolean - логическое значение
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Получает или задает верхний индекс текста, представленного объектом TextFragment.

**Возвращает:**
boolean - значение логическое значение
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Получает подчеркивание текста, представленного объектом TextFragment.

**Возвращает:**
boolean - логическое значение
### measureString(String str) {#measureString-java.lang.String-}
```
public double measureString(String str)
```


Измеряет струну.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Струна. |

**Возвращает:**
double - двойное значение, Ширина строки.
### measureString(String str, boolean insideLine) {#measureString-java.lang.String-boolean-}
```
public double measureString(String str, boolean insideLine)
```


Измеряет струну.

--------------------

insideLine указывает, что строка не заканчивается. в случае, если измеряется часть всей строки, внутренняя строка должна быть истинной. в случае, если измеряется вся строка, значение insideLine должно быть ложным. другими словами: в случае insideLine = true учитывается только ширина символов. никакие дополнительные преобразования не учитываются в случае, если insideLine = false конец строки обрабатывается правильно - учитывается курсивное преобразование.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Строковое значение |
| insideLine | boolean | логическое значение |

**Возвращает:**
двойное - двойное значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


 Устанавливает цвет фона текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```


Задает интервал между символами текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setDrawTextRectangleBorder(boolean value) {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```


Устанавливает флаг отрисовки границы текстового прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


Задает шрифт текста, представленного объектом TextFragment

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Значение шрифта |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Устанавливает размер шрифта текста, представленного объектом TextFragment

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFontSizeSuppressedUpdate(float value) {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```


Устанавливает размер шрифта текста, который необходимо отключить при обновлении.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


 Устанавливает стиль шрифта текста, представленного[TextFragment](../../com.aspose.pdf/textfragment) объект

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFontSuppressedUpdate(Font value) {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
```
public void setFontSuppressedUpdate(Font value)
```


Получает шрифт текста, который желает отключить обновление.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Объект шрифта |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public void setForegroundColor(Color value)
```


Задает цвет переднего плана текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Цвет объекта |

### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


Получает или задает параметры форматирования. Настройка параметров будет эффективна только в сценариях с генератором.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | Экземпляр TextFormattingOptions |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Задает горизонтальное выравнивание текста.

--------------------

HorizontalAlignment.None равно HorizontalAlignment.Left. Обратите внимание, что свойство TextFragmentState.VerticalAlignment работает только в новых сценариях генерации документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


Задает горизонтальное масштабирование текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


Устанавливает невидимость текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```


Устанавливает межстрочный интервал текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение

--------------------

 Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Геттер свойства LineSpacing работает для объекта в случае, если он был явно установлен ранее с помощью установщика LineSpacing для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.|

### setRenderingMode(int value) {#setRenderingMode-int-}
```
public void setRenderingMode(int value)
```


Получает или задает режим рендеринга текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Получает или задает угол поворота в градусах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setStrikeOut(boolean value) {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```


Устанавливает зачеркивание для текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setStrokingColor(Color value) {#setStrokingColor-com.aspose.pdf.Color-}
```
public void setStrokingColor(Color value)
```


Получает или задает операции обводки цветом при рендеринге TextFragment (обводка текста, граница прямоугольника)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


Получает или задает нижний индекс текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


Получает или задает верхний индекс текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```


Устанавливает подчеркивание для текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```


Устанавливает межсловный интервал в тексте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

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
