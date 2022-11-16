---
title: Font
second_title: Aspose.PDF для справки по Java API
description: Представляет объект шрифта.
type: docs
weight: 130
url: /ru/java/com.aspose.pdf/font/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Cloneable
```
public final class Font implements Cloneable
```

Представляет объект шрифта.

--------------------

```
The example demonstrates how to search text on first page and change font of a first search occurrence.
 
  
  // Open document
  Document doc = new Document("input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Create font and mark it to be embedded
  Font font = FontRepository.findFont("Arial");
  font.isEmbedded(true);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont( font);
  
  
  // Save document
  doc.save("output.pdf");
```
## Методы

| Метод | Описание |
| --- | --- |
| [doesFontContainAllCharacters(String value)](#doesFontContainAllCharacters-java.lang.String-) | Определяет, содержит ли шрифт указанные символы |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseFont()](#getBaseFont--) | Получает значение BaseFont объекта шрифта PDF. |
| [getClass()](#getClass--) |  |
| [getDecodedFontName()](#getDecodedFontName--) | Иногда шрифты PDF (обычно китайские/японские/корейские шрифты) могут иметь определенное имя шрифта. |
| [getFontName()](#getFontName--) | Получает имя шрифта объекта Font. |
| [getFontOptions()](#getFontOptions--) | Полезные свойства для настройки поведения шрифта |
| [getIFont()](#getIFont--) | Объект системного шрифта. |
| [getIPdfFont()](#getIPdfFont--) | Объект шрифта PDF. |
| [getLastFontEmbeddingError()](#getLastFontEmbeddingError--) | Задача этого метода - вернуть описание ошибки, если попытка встроить шрифт не удалась. |
| [getType()](#getType--) | Тип шрифта Имя |
| [hashCode()](#hashCode--) |  |
| [isAccessible()](#isAccessible--) | Получает информацию о наличии (установленности) шрифта в системе. |
| [isEmbedded()](#isEmbedded--) | Получает значение, указывающее, внедрен ли шрифт. |
| [isSubset()](#isSubset--) | Получает значение, указывающее, является ли шрифт подмножеством. |
| [measureString(String str, float fontSize)](#measureString-java.lang.String-float-) | Измеряет струну. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет шрифт в поток. |
| [setEmbedded(boolean value)](#setEmbedded-boolean-) | Задает значение, указывающее, встроен ли шрифт. |
| [setSubset(boolean value)](#setSubset-boolean-) | Задает значение, указывающее, является ли шрифт подмножеством. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### doesFontContainAllCharacters(String value) {#doesFontContainAllCharacters-java.lang.String-}
```
public boolean doesFontContainAllCharacters(String value)
```


Определяет, содержит ли шрифт указанные символы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

**Возвращает:**
boolean - true, если все символы из текста присутствуют в текущем шрифте.
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
### getBaseFont() {#getBaseFont--}
```
public final String getBaseFont()
```


Получает значение BaseFont объекта шрифта PDF. Также известен как название шрифта PostScript.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDecodedFontName() {#getDecodedFontName--}
```
public String getDecodedFontName()
```


Иногда шрифты PDF (обычно китайские/японские/корейские шрифты) могут иметь определенное имя шрифта. Это имя является значением свойства шрифта PDF «BaseFont», и иногда это свойство может быть представлено в шестнадцатеричной форме. Если прочитать это имя напрямую, оно может быть представлено в нечитаемой форме. Для получения удобочитаемого вида необходимо расшифровать название шрифта по правилам, специфичным для этого шрифта. Это свойство возвращает декодированное имя шрифта, поэтому используйте его для случаев, когда вы встречаетесь с нечитаемым FontName. Если свойство FontName имеет удобочитаемую форму, это свойство будет таким же, как FontName , поэтому вы можете использовать это свойство для любых случаев, когда вам нужно получить имя шрифта в удобочитаемой форме.

**Возвращает:**
java.lang.String — строковое значение
### getFontName() {#getFontName--}
```
public String getFontName()
```


Получает имя шрифта объекта Font.

**Возвращает:**
java.lang.String — строковое значение

--------------------

```
The example demonstrates how to search text on first page and view font name of a first text occurrence.
 
  // Open document
  Document doc = new Document(@"D:\Tests\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // View font name of first text occurrence
  System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName());
```
### getFontOptions() {#getFontOptions--}
```
public IFontOptions getFontOptions()
```


Полезные свойства для настройки поведения шрифта

**Возвращает:**
[IFontOptions](../../com.aspose.pdf/ifontoptions) - Объект IFontOptions
### getIFont() {#getIFont--}
```
public IFont getIFont()
```


Объект системного шрифта.

--------------------

Только для внутреннего использования

**Возвращает:**
[IFont](../../com.aspose.font/ifont) - IFont объект
### getIPdfFont() {#getIPdfFont--}
```
public IPdfFont getIPdfFont()
```


Объект шрифта PDF.

--------------------

Только для внутреннего использования

**Возвращает:**
[IPdfFont](../../com.aspose.pdf.engine.commondata.text.fonts/ipdffont) - Объект IPdfFont
### getLastFontEmbeddingError() {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```


Задача этого метода - вернуть описание ошибки, если попытка встроить шрифт не удалась. Если ошибок нет, возвращает пустую строку.

**Возвращает:**
java.lang.String — Описание ошибки
### getType() {#getType--}
```
public String getType()
```


Тип шрифта Имя

**Возвращает:**
java.lang.String — строковый объект
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isAccessible() {#isAccessible--}
```
public boolean isAccessible()
```


Получает информацию о наличии (установленности) шрифта в системе.

**Возвращает:**
boolean - логическое значение

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system.
 
 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(absorber);
 
 // View font's IsSubset value of first text occurrence
 if (absorber.getTextFragments().get_Item(1).getTextState().getFont()
 		.isAccessible())
 	System.out.println("the font is installed in the system");
```

--------------------

Некоторые операции недоступны со шрифтами, которые не удалось найти в системе.
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Получает значение, указывающее, внедрен ли шрифт. Шрифт на основе IFont будет автоматически подмножен и встроен

--------------------

```
The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font.
 
	      // Create font and mark it to be embedded
	      com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial");
	      font.isEmbedded ( true);
	      // open document
	      com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf");
	      // create TextFragmentAbsorber object to find all "hello world" text occurrences
	      com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world");
	      // accept the absorber for first page
	      doc.getPages().get_Item(1).accept(absorber);
	      // change font for the first text occurrence
	      absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
	      // save document
	      doc.save("D:\\Tests\\output.pdf");
```

**Возвращает:**
boolean - логическое значение
### isSubset() {#isSubset--}
```
public boolean isSubset()
```


Получает значение, указывающее, является ли шрифт подмножеством. Шрифт на основе IFont будет автоматически подмножен и встроен

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset.
  
	       // Open document
	       Document doc = new Document("D:\\Tests\\input.pdf");
	       // Create TextFragmentAbsorber object to find all "hello world" text occurrences
	       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
	       
	       // Accept the absorber for first page
	       doc.getPages().get_Item(1).accept(absorber);
	       
	       // View font's IsSubset value of first text occurrence
	       if(absorber.TextFragments[1].TextState.Font.IsSubset)
	          System.out.println("the font is a subset");
```

**Возвращает:**
boolean - логическое значение
### measureString(String str, float fontSize) {#measureString-java.lang.String-float-}
```
public double measureString(String str, float fontSize)
```


Измеряет струну.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Струна. |
| fontSize | float | Размер шрифта. |

**Возвращает:**
double - Ширина строки, представленной этим шрифтом и указанным размером.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет шрифт в поток. Обратите внимание, что шрифт сохраняется в промежуточном формате TTF, предназначенном для использования только в преобразованной копии исходного документа. Файл шрифта не предназначен для использования вне контекста исходного документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения шрифта. |

### setEmbedded(boolean value) {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```


Задает значение, указывающее, встроен ли шрифт. Шрифт на основе IFont будет автоматически подмножен и встроен

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSubset(boolean value) {#setSubset-boolean-}
```
public void setSubset(boolean value)
```


Задает значение, указывающее, является ли шрифт подмножеством. Шрифт на основе IFont будет автоматически подмножен и встроен

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
