---
title: FontRepository
second_title: Aspose.PDF для справки по Java API
description: Выполняет поиск шрифтов.
type: docs
weight: 134
url: /ru/java/com.aspose.pdf/fontrepository/
---
**Наследование:**
java.lang.Object
```
public final class FontRepository
```

Выполняет поиск шрифтов. Поиск в установленных системой шрифтах и стандартных шрифтах Pdf. Также предоставляет функциональные возможности для открытия пользовательских шрифтов.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  
  // Find font
  Font font = FontRepository.findFont("Arial");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontRepository()](#FontRepository--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addLocalFontPath(String path)](#addLocalFontPath-java.lang.String-) | Добавьте еще один путь к fonts. |
| [addSystemFont(Font font)](#addSystemFont-com.aspose.pdf.Font-) | Добавить системный шрифт с указанным шрифтом. |
| [clear()](#clear--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findFont(String fontName)](#findFont-java.lang.String-) | Ищет и возвращает шрифт с указанным именем шрифта. |
| [findFont(String fontName, boolean ignoreCase)](#findFont-java.lang.String-boolean-) | Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая чувствительность к регистру. |
| [findFont(String fontFamilyName, int stl)](#findFont-java.lang.String-int-) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта. |
| [findFont(String fontFamilyName, int stl, boolean ignoreCase)](#findFont-java.lang.String-int-boolean-) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая чувствительность к регистру. |
| [getClass()](#getClass--) |  |
| [getLocalFontPaths()](#getLocalFontPaths--) | Копия списка с фактическими каталогами шрифтов. |
| [getSources()](#getSources--) | Получает коллекцию источников шрифтов. |
| [getSubstitutions()](#getSubstitutions--) | Получает коллекцию стратегий замены шрифтов. |
| [hashCode()](#hashCode--) |  |
| [isReplaceNotFoundFonts()](#isReplaceNotFoundFonts--) | Не найденные шрифты будут заменены стандартным шрифтом. |
| [isThreadStaticConfigEnabled()](#isThreadStaticConfigEnabled--) | Возвращает состояние конфигурации хранилища источников шрифтов. |
| [loadFonts()](#loadFonts--) | Загружает установленные системой шрифты и стандартные шрифты Pdf. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFont(InputStream fontStream, int fontType)](#openFont-java.io.InputStream-int-) | Открывает шрифт с указанным потоком шрифтов. |
| [openFont(String fontFilePath)](#openFont-java.lang.String-) | Открывает шрифт с указанным путем к файлу шрифта. |
| [openFont(String fontFilePath, String metricsFilePath)](#openFont-java.lang.String-java.lang.String-) | Открывает шрифт с указанным путем к файлу шрифта и пути к файлу метрик. |
| [reloadFonts()](#reloadFonts--) | Перезагружает все шрифты, указанные в свойстве Sources (\#getSources.getSources) |
| [restoreLocalFontPath()](#restoreLocalFontPath--) | Восстанавливает список стандартных каталогов шрифтов по умолчанию. |
| [setLocalFontPaths(List<String> newFontPathsList)](#setLocalFontPaths-java.util.List-java.lang.String--) | Устанавливает список пользователей с путями шрифтов |
| [setReplaceNotFoundFonts(boolean value)](#setReplaceNotFoundFonts-boolean-) | Установите TRUE, если необходимо заменить ненайденные шрифты шрифтом по умолчанию. |
| [setThreadStaticConfigEnabled(boolean isTheadLocal)](#setThreadStaticConfigEnabled-boolean-) | Возможность настройки конфигурации хранилища источников шрифтов. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontRepository() {#FontRepository--}
```
public FontRepository()
```


### addLocalFontPath(String path) {#addLocalFontPath-java.lang.String-}
```
public static void addLocalFontPath(String path)
```


Добавьте еще один путь к fonts.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Строковое значение |

### addSystemFont(Font font) {#addSystemFont-com.aspose.pdf.Font-}
```
public static void addSystemFont(Font font)
```


Добавить системный шрифт с указанным шрифтом.

--------------------

```
The example demonstrates how to add system font.

  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))

  Font font = FontRepository.openFont(fontStream, FontTypes.TTF);

  FontRepository.addSystemFont(font);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | Экземпляр шрифта |

### clear() {#clear--}
```
public static void clear()
```




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
### findFont(String fontName) {#findFont-java.lang.String-}
```
public static Font findFont(String fontName)
```


Ищет и возвращает шрифт с указанным именем шрифта.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Название шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### findFont(String fontName, boolean ignoreCase) {#findFont-java.lang.String-boolean-}
```
public static Font findFont(String fontName, boolean ignoreCase)
```


Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая чувствительность к регистру.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Название шрифта. |
| ignoreCase | boolean | чувствительность к регистру |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### findFont(String fontFamilyName, int stl) {#findFont-java.lang.String-int-}
```
public static Font findFont(String fontFamilyName, int stl)
```


Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Название семейства шрифтов. |
| stl | int | Значение стиля шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта, соответствующий параметрам поискового запроса.
### findFont(String fontFamilyName, int stl, boolean ignoreCase) {#findFont-java.lang.String-int-boolean-}
```
public static Font findFont(String fontFamilyName, int stl, boolean ignoreCase)
```


Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая чувствительность к регистру.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  
  Font font = FontRepository.findFont("Arial", FontStyles.Italic, true);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Название семейства шрифтов. |
| stl | int | Значение стиля шрифта. |
| ignoreCase | boolean | чувствительность к регистру |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта, соответствующий параметрам поискового запроса.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getLocalFontPaths() {#getLocalFontPaths--}
```
public static List<String> getLocalFontPaths()
```


Копия списка с фактическими каталогами шрифтов.

**Возвращает:**
java.util.List<java.lang.String> — список строк
### getSources() {#getSources--}
```
public static FontSourceCollection getSources()
```


Получает коллекцию источников шрифтов.

**Возвращает:**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) - Объект FontSourceCollection
### getSubstitutions() {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```


Получает коллекцию стратегий замены шрифтов.

**Возвращает:**
[FontSubstitutionCollection](../../com.aspose.pdf.text/fontsubstitutioncollection) - Объект FontSubstitutionCollection
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReplaceNotFoundFonts() {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```


Не найденные шрифты будут заменены стандартным шрифтом.

**Возвращает:**
boolean - логическое значение
### isThreadStaticConfigEnabled() {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```


Возвращает состояние конфигурации хранилища источников шрифтов.
Если true, используется ThreadStatic, и у каждого потока есть собственные источники шрифтов.
Если false, используется глобальная статическая конфигурация для всех потоков.

--------------------

Значение по умолчанию — Истина.

**Возвращает:**
boolean - логическое значение
### loadFonts() {#loadFonts--}
```
public static void loadFonts()
```


Загружает установленные системой шрифты и стандартные шрифты Pdf. Этот метод был разработан для ускорения процесса загрузки шрифтов. По умолчанию шрифты загружаются по первому запросу для любого шрифта. Использование этого метода загружает системные и стандартные шрифты Pdf непосредственно перед открытием любого документа Pdf.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### openFont(InputStream fontStream, int fontType) {#openFont-java.io.InputStream-int-}
```
public static Font openFont(InputStream fontStream, int fontType)
```


Открывает шрифт с указанным потоком шрифтов.

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
  
  // Open font
  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))
  {
      Font font = FontRepository.openFont(fontStream, , FontTypes.TTF);
  
      // Open document
      Document doc = new Document("D:\\Tests\\input.pdf");
      // Create TextFragmentAbsorber object to find all "hello world" text occurrences
      TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
      // Accept the absorber for first page
      doc.getPages().get_Item(1).accept(absorber);
  
      // Change font of the first text occurrence
      absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
      // Save document
      doc.save("D:\\Tests\\output.pdf"); 
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontStream | java.io.InputStream | Поток шрифтов. |
| fontType | int | Значение типа шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### openFont(String fontFilePath) {#openFont-java.lang.String-}
```
public static Font openFont(String fontFilePath)
```


Открывает шрифт с указанным путем к файлу шрифта.

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
 
  // Open font
  Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | java.lang.String | Путь к файлу шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### openFont(String fontFilePath, String metricsFilePath) {#openFont-java.lang.String-java.lang.String-}
```
public static Font openFont(String fontFilePath, String metricsFilePath)
```


Открывает шрифт с указанным путем к файлу шрифта и пути к файлу метрик.

--------------------

```
The example demonstrates how to open Type1 font with metrics and replace the font of text of first page.
  
  // Open font
  Font font = FontRepository.openFont("courier.pfb", "courier.afm");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | java.lang.String | Путь к файлу шрифта. |
| metricsFilePath | java.lang.String | Путь к файлу метрик шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### reloadFonts() {#reloadFonts--}
```
public static void reloadFonts()
```


Перезагружает все шрифты, указанные в свойстве Sources (\#getSources.getSources)

### restoreLocalFontPath() {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```


Восстанавливает список стандартных каталогов шрифтов по умолчанию.

### setLocalFontPaths(List<String> newFontPathsList) {#setLocalFontPaths-java.util.List-java.lang.String--}
```
public static void setLocalFontPaths(List<String> newFontPathsList)
```


Устанавливает список пользователей с путями шрифтов

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newFontPathsList | java.util.List<java.lang.String> |  Список объектов |

### setReplaceNotFoundFonts(boolean value) {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```


Установите TRUE, если необходимо заменить ненайденные шрифты шрифтом по умолчанию. Значение по умолчанию неверно.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | логический | boolean |

### setThreadStaticConfigEnabled(boolean isTheadLocal) {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```


Возможность настройки конфигурации хранилища источников шрифтов.
Если true, используется ThreadStatic, и у каждого потока есть собственные источники шрифтов.
Если false, используется глобальная статическая конфигурация для всех потоков.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| isTheadLocal | boolean | логическое значение |

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
