---
title: TextSearchOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры текстового поиска
type: docs
weight: 385
url: /ru/java/com.aspose.pdf/textsearchoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextSearchOptions extends TextOptions
```

Представляет параметры текстового поиска
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextSearchOptions(boolean isRegularExpressionUsed)](#TextSearchOptions-boolean-) | Инициализирует новый экземпляр объекта TextSearchOptions. |
| [TextSearchOptions(Rectangle rectangle)](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Инициализирует новый экземпляр объекта TextSearchOptions. |
| [TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Инициализирует новый экземпляр объекта TextSearchOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIgnoreResourceFontErrors()](#getIgnoreResourceFontErrors--) | Получает или задает индикацию того, что ошибки, связанные с отсутствием шрифта, будут игнорироваться поглотителем текста (фрагмента). |
| [getLimitToPageBounds()](#getLimitToPageBounds--) | Получает указание, что текст ищется в пределах страницы. |
| [getLogTextExtractionErrors()](#getLogTextExtractionErrors--) | Получает или задает индикацию того, что ошибки извлечения (декодирования) текста будут регистрироваться в поглотителе текста (фрагментов). true - означает, что ошибки извлечения (декодирования) текста будут протоколироваться. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник, ограничивающий искомый текст. |
| [getSearchForTextRelatedGraphics()](#getSearchForTextRelatedGraphics--) | Получает или задает значение, разрешающее поиск связанной с текстом графики (подчеркивание, фон и т. д.) во время поиска текста. |
| [getStoredGraphicElementsMaxCount()](#getStoredGraphicElementsMaxCount--) | Получает значение, которое ограничивает поиск связанной с текстом графики (подчеркивание, фон и т. д.) на странице для указанного количества элементов. |
| [getUseFontEngineEncoding()](#getUseFontEngineEncoding--) | Получает указание на то, что текст будет искаться с использованием кодировки механизма шрифтов. true — означает, что будет использоваться кодировка шрифтового движка (попробуйте, если текстовый поиск не работает из-за несовершенной кодировки в документе) false — означает, что будет использоваться кодировка шрифта документа (значение по умолчанию) |
| [hashCode()](#hashCode--) |  |
| [isDotallMode()](#isDotallMode--) | В точечном режиме выражение . соответствует любому символу, включая признак конца строки. |
| [isIgnoreShadowText()](#isIgnoreShadowText--) | Получает или задает указание на то, что текстовые фрагменты, представляющие тень обычного текста, будут игнорироваться при поиске. true - означает, что теневой текст не будет найден (попробуйте, если текстовый поиск возвращает дублирующиеся фрагменты на близких позициях) false - означает, что теневой текст будет найден так же, как и обычный текст (значение по умолчанию) |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | Указано, что регулярное выражение используется или нет |
| [isSearchInAnnotations()](#isSearchInAnnotations--) | Получает или задает значение, разрешающее поиск текста в аннотациях. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDotallMode(boolean dotallMode)](#setDotallMode-boolean-) | Включает точечный режим. |
| [setIgnoreResourceFontErrors(boolean value)](#setIgnoreResourceFontErrors-boolean-) | Получает или задает индикацию того, что ошибки, связанные с отсутствием шрифта, будут игнорироваться поглотителем текста (фрагмента). |
| [setIgnoreShadowText(boolean value)](#setIgnoreShadowText-boolean-) | Получает или задает указание на то, что текстовые фрагменты, представляющие тень обычного текста, будут игнорироваться при поиске. true - означает, что теневой текст не будет найден (попробуйте, если текстовый поиск возвращает дублирующиеся фрагменты на близких позициях) false - означает, что теневой текст будет найден так же, как и обычный текст (значение по умолчанию) |
| [setLimitToPageBounds(boolean value)](#setLimitToPageBounds-boolean-) | Устанавливает индикацию поиска текста в пределах страницы. |
| [setLogTextExtractionErrors(boolean value)](#setLogTextExtractionErrors-boolean-) | Получает или задает индикацию того, что ошибки извлечения (декодирования) текста будут регистрироваться в поглотителе текста (фрагментов). true - означает, что ошибки извлечения (декодирования) текста будут протоколироваться. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Задает прямоугольник, ограничивающий искомый текст. |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | Указано, что регулярное выражение используется или нет |
| [setSearchForTextRelatedGraphics(boolean value)](#setSearchForTextRelatedGraphics-boolean-) | Получает или задает значение, разрешающее поиск связанной с текстом графики (подчеркивание, фон и т. д.) во время поиска текста. |
| [setSearchInAnnotations(boolean value)](#setSearchInAnnotations-boolean-) | Получает или задает значение, разрешающее поиск текста в аннотациях. |
| [setStoredGraphicElementsMaxCount(int value)](#setStoredGraphicElementsMaxCount-int-) | Устанавливает значение, которое ограничивает поиск связанной с текстом графики (подчеркивание, фон и т. д.) на странице для указанного количества элементов. |
| [setUseFontEngineEncoding(boolean value)](#setUseFontEngineEncoding-boolean-) | Устанавливает индикацию того, что текст будет искаться с использованием кодировки шрифтового движка. true — означает, что будет использоваться кодировка шрифтового движка (попробуйте, если текстовый поиск не работает из-за несовершенной кодировки в документе) false — означает, что будет использоваться кодировка шрифта документа (значение по умолчанию) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextSearchOptions(boolean isRegularExpressionUsed) {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```


Инициализирует новый экземпляр объекта TextSearchOptions. Задает режим использования регулярного выражения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| isRegularExpressionUsed | boolean | Значение, указывающее, что используется регулярное выражение. |

### TextSearchOptions(Rectangle rectangle) {#TextSearchOptions-com.aspose.pdf.Rectangle-}
```
public TextSearchOptions(Rectangle rectangle)
```


Инициализирует новый экземпляр объекта TextSearchOptions. Задает прямоугольник, ограничивающий искомый текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, содержащий извлеченный текст. |

### TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed) {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
```
public TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)
```


Инициализирует новый экземпляр объекта TextSearchOptions. Задает прямоугольник, ограничивающий искомый текст, и режим использования регулярного выражения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, содержащий извлеченный текст. |
| isRegularExpressionUsed | boolean | Значение, указывающее, что используется регулярное выражение. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getIgnoreResourceFontErrors() {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```


Получает или задает индикацию того, что ошибки, связанные с отсутствием шрифта, будут игнорироваться поглотителем текста (фрагмента). true - означает, что ошибки отсутствия шрифта будут игнорироваться. Текстовые сегменты, которые ссылаются на некорректные ресурсы, будут пропущены при обработке. false (по умолчанию) - отсутствие ошибки шрифта приведет к прекращению обработки с выдачей исключения.

**Возвращает:**
boolean - логическое значение
### getLimitToPageBounds() {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```


Получает указание, что текст ищется в пределах страницы.

**Возвращает:**
boolean - логическое значение
### getLogTextExtractionErrors() {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```


Получает или задает индикацию того, что ошибки извлечения (декодирования) текста будут регистрироваться в поглотителе текста (фрагментов). true - означает, что ошибки извлечения (декодирования) текста будут протоколироваться. Это может снизить производительность. false (по умолчанию) - нет регистрации ошибок.

**Возвращает:**
boolean - логическое значение
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник, ограничивающий искомый текст. Свойство может быть использовано в случае, если требуется разграничить область извлечения текста или замены текста.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника
### getSearchForTextRelatedGraphics() {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```


Получает или задает значение, разрешающее поиск связанной с текстом графики (подчеркивание, фон и т. д.) во время поиска текста. true - будет выполняться поиск графики, связанной с текстом (значение по умолчанию). false - графические элементы, которые могут присутствовать в исходном документе, будут игнорироваться. Установите это в случае проблем с производительностью или отсутствия необходимости обрабатывать подчеркивание, фон или обрезку.

**Возвращает:**
boolean - логическое значение
### getStoredGraphicElementsMaxCount() {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```


Получает значение, которое ограничивает поиск связанной с текстом графики (подчеркивание, фон и т. д.) на странице для указанного количества элементов. По умолчанию 250. Установите меньшее значение в случае проблем с производительностью, попробуйте большее значение в случае, если некоторые графические элементы не были найдены.

**Возвращает:**
интервал - целочисленное значение
### getUseFontEngineEncoding() {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```


Получает указание на то, что текст будет искаться с использованием кодировки механизма шрифтов. true — означает, что будет использоваться кодировка шрифтового движка (попробуйте, если текстовый поиск не работает из-за несовершенной кодировки в документе) false — означает, что будет использоваться кодировка шрифта документа (значение по умолчанию)

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isDotallMode() {#isDotallMode--}
```
public static boolean isDotallMode()
```


В точечном режиме выражение . соответствует любому символу, включая признак конца строки. По умолчанию это выражение не соответствует разделителям строк.

**Возвращает:**
boolean - логическое значение
### isIgnoreShadowText() {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```


Получает или задает указание на то, что текстовые фрагменты, представляющие тень обычного текста, будут игнорироваться при поиске. true - означает, что теневой текст не будет найден (попробуйте, если текстовый поиск возвращает дублирующиеся фрагменты на близких позициях) false - означает, что теневой текст будет найден так же, как и обычный текст (значение по умолчанию)

**Возвращает:**
boolean - логическое значение
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


Указано, что регулярное выражение используется или нет

**Возвращает:**
boolean - логическое значение
### isSearchInAnnotations() {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```


Получает или задает значение, разрешающее поиск текста в аннотациях. true - текст будет искаться в аннотациях. false — текст в аннотациях не будет анализироваться TextFragmentAbsorber.

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




### setDotallMode(boolean dotallMode) {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```


Включает точечный режим.

В точечном режиме выражение . соответствует любому символу, включая признак конца строки. По умолчанию это выражение не соответствует разделителям строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| dotallMode | boolean | логическое значение |

### setIgnoreResourceFontErrors(boolean value) {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```


Получает или задает индикацию того, что ошибки, связанные с отсутствием шрифта, будут игнорироваться поглотителем текста (фрагмента). true - означает, что ошибки отсутствия шрифта будут игнорироваться. Текстовые сегменты, которые ссылаются на некорректные ресурсы, будут пропущены при обработке. false (по умолчанию) - отсутствие ошибки шрифта приведет к прекращению обработки с выдачей исключения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setIgnoreShadowText(boolean value) {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```


Получает или задает указание на то, что текстовые фрагменты, представляющие тень обычного текста, будут игнорироваться при поиске. true - означает, что теневой текст не будет найден (попробуйте, если текстовый поиск возвращает дублирующиеся фрагменты на близких позициях) false - означает, что теневой текст будет найден так же, как и обычный текст (значение по умолчанию)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLimitToPageBounds(boolean value) {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```


Устанавливает индикацию поиска текста в пределах страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLogTextExtractionErrors(boolean value) {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```


Получает или задает индикацию того, что ошибки извлечения (декодирования) текста будут регистрироваться в поглотителе текста (фрагментов). true - означает, что ошибки извлечения (декодирования) текста будут протоколироваться. Это может снизить производительность. false (по умолчанию) - нет регистрации ошибок.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Задает прямоугольник, ограничивающий искомый текст. Свойство может быть использовано в случае, если требуется разграничить область извлечения текста или замены текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


Указано, что регулярное выражение используется или нет

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSearchForTextRelatedGraphics(boolean value) {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```


Получает или задает значение, разрешающее поиск связанной с текстом графики (подчеркивание, фон и т. д.) во время поиска текста. true - будет выполняться поиск графики, связанной с текстом (значение по умолчанию). false - графические элементы, которые могут присутствовать в исходном документе, будут игнорироваться. Установите это в случае проблем с производительностью или отсутствия необходимости обрабатывать подчеркивание, фон или обрезку.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSearchInAnnotations(boolean value) {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```


Получает или задает значение, разрешающее поиск текста в аннотациях. true - текст будет искаться в аннотациях. false — текст в аннотациях не будет анализироваться TextFragmentAbsorber.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setStoredGraphicElementsMaxCount(int value) {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```


Устанавливает значение, которое ограничивает поиск связанной с текстом графики (подчеркивание, фон и т. д.) на странице для указанного количества элементов. По умолчанию 250. Установите меньшее значение в случае проблем с производительностью, попробуйте большее значение в случае, если некоторые графические элементы не были найдены.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setUseFontEngineEncoding(boolean value) {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```


Устанавливает индикацию того, что текст будет искаться с использованием кодировки шрифтового движка. true — означает, что будет использоваться кодировка шрифтового движка (попробуйте, если текстовый поиск не работает из-за несовершенной кодировки в документе) false — означает, что будет использоваться кодировка шрифта документа (значение по умолчанию)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
