---
title: DocSaveOptions
second_title: Aspose.PDF для справки по Java API
description: Сохранить параметры для экспорта в формат Doc
type: docs
weight: 90
url: /ru/java/com.aspose.pdf/docsaveoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**Все реализованные интерфейсы:**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Сохранить параметры для экспорта в формат Doc
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocSaveOptions()](#DocSaveOptions--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [getFormat()](#getFormat--) | Получить выходной формат |
| [getImageResolutionX()](#getImageResolutionX--) | Преобразованные изображения с разрешением X. |
| [getImageResolutionY()](#getImageResolutionY--) | Преобразованные изображения в разрешении Y. |
| [getMaxDistanceBetweenTextLines()](#getMaxDistanceBetweenTextLines--) | Этот параметр используется для группировки строк текста в абзацы. |
| [getMemorySaveModePath()](#getMemorySaveModePath--) | Определяет путь (имя файла или имя каталога) для хранения временных данных при преобразовании в режиме экономии памяти. |
| [getMode()](#getMode--) | Режим распознавания. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [getRelativeHorizontalProximity()](#getRelativeHorizontalProximity--) | В Pdf слова могут быть внутренне представлены операторами, которые печатают слова, независимо печатая их буквы или слоги. |
| [getSaveFormat()](#getSaveFormat--) | Формат сохранения данных. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isAddReturnToLineEnd()](#isAddReturnToLineEnd--) | Используется разрыв абзаца или строки. |
| [isCloseResponse()](#isCloseResponse--) | Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [isRecognizeBullets()](#isRecognizeBullets--) | Включите распознавание пуль. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddReturnToLineEnd(boolean value)](#setAddReturnToLineEnd-boolean-) | Используйте разрывы абзаца или строки |
| [setBatchSize(int value)](#setBatchSize-int-) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [setFormat(int value)](#setFormat-int-) | Установить выходной формат |
| [setImageResolutionX(int value)](#setImageResolutionX-int-) | Преобразованные изображения с разрешением X. |
| [setImageResolutionY(int value)](#setImageResolutionY-int-) | Преобразованные изображения в разрешении Y. |
| [setMaxDistanceBetweenTextLines(float value)](#setMaxDistanceBetweenTextLines-float-) | Этот параметр используется для группировки строк текста в абзацы. |
| [setMemorySaveModePath(String value)](#setMemorySaveModePath-java.lang.String-) | Определяет путь (имя файла или имя каталога) для хранения временных данных при преобразовании в режиме экономии памяти. |
| [setMode(int value)](#setMode-int-) | Режим распознавания. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [setRecognizeBullets(boolean value)](#setRecognizeBullets-boolean-) | Включите распознавание пуль. |
| [setRelativeHorizontalProximity(float value)](#setRelativeHorizontalProximity-float-) | В Pdf слова могут быть внутренне представлены операторами, которые печатают слова, независимо печатая их буквы или слоги. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocSaveOptions() {#DocSaveOptions--}
```
public DocSaveOptions()
```


Конструктор

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Возвращает:**
инт
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**Возвращает:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - Экземпляр ConversionProgressEventHandler
### getFormat() {#getFormat--}
```
public int getFormat()
```


Получить выходной формат

**Возвращает:**
int - элемент формата документа
### getImageResolutionX() {#getImageResolutionX--}
```
public int getImageResolutionX()
```


Преобразованные изображения с разрешением X.

**Возвращает:**
интервал - целочисленное значение
### getImageResolutionY() {#getImageResolutionY--}
```
public int getImageResolutionY()
```


Преобразованные изображения в разрешении Y.

**Возвращает:**
интервал - целочисленное значение
### getMaxDistanceBetweenTextLines() {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```


Этот параметр используется для группировки строк текста в абзацы. Определяет, насколько далеко друг от друга могут быть две относительные строки текста. Указывается в сотнях процентов от высоты строки текста.

**Возвращает:**
float - плавающее значение
### getMemorySaveModePath() {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```


Определяет путь (имя файла или имя каталога) для хранения временных данных при преобразовании в режиме экономии памяти.

**Возвращает:**
java.lang.String — строковое значение
### getMode() {#getMode--}
```
public int getMode()
```


Режим распознавания.

**Возвращает:**
int — значение режима распознавания
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Возвращает:**
com.aspose.pdf.ConversionProgressEventsTranslator — экземпляр ConversionProgressEventsTranslator
### getRelativeHorizontalProximity() {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```


В Pdf слова могут быть внутренне представлены операторами, которые печатают слова, независимо печатая их буквы или слоги. Таким образом, для обнаружения слов иногда нам нужно обнаруживать группы независимых символов, которые на самом деле являются словами. Этот параметр определяет ширину промежутка между текстовыми элементами (буквами, слогами), который должен рассматриваться как расстояние между словами при распознавании слов в исходном PDF-файле. (наличие пробела хотя бы при такой ширине между буквами означает, что элементы текста относятся к разным словам). Это нормировано по размеру шрифта - 1.0 означает 100% размера шрифта предполагаемого слова. ВНИМАНИЕ! Используется только в тех случаях, когда исходный PDF содержит определенные редко используемые шрифты, для которых невозможно вычислить оптимальное значение из шрифта. Таким образом, в подавляющем большинстве случаев этот параметр ничего не меняет в результирующем документе.

**Возвращает:**
float - Относительная близость
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Формат сохранения данных.

**Возвращает:**
[SaveFormat](../../com.aspose.pdf/saveformat) - Значение формата сохранения
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isAddReturnToLineEnd() {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```


Используется разрыв абзаца или строки.

**Возвращает:**
boolean - логическое значение.
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Возвращает:**
boolean - логическое значение
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR.

Значение: в результирующий документ будет извлечен истинный текст; в противном случае ложь.

**Возвращает:**
boolean - логическое значение
### isRecognizeBullets() {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```


Включите распознавание пуль.

**Возвращает:**
boolean - логическое значение
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

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




### setAddReturnToLineEnd(boolean value) {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```


Используйте разрывы абзаца или строки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение. |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | Экземпляр ConversionProgressEventHandler |

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR.

Значение: в результирующий документ будет извлечен истинный текст; в противном случае ложь.

--------------------

Значение по умолчанию == ложь

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


Установить выходной формат

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент формата документа |

### setImageResolutionX(int value) {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```


Преобразованные изображения с разрешением X.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setImageResolutionY(int value) {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```


Преобразованные изображения в разрешении Y.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setMaxDistanceBetweenTextLines(float value) {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```


Этот параметр используется для группировки строк текста в абзацы. Определяет, насколько далеко друг от друга могут быть две относительные строки текста. Указывается в сотнях процентов от высоты строки текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setMemorySaveModePath(String value) {#setMemorySaveModePath-java.lang.String-}
```
public final void setMemorySaveModePath(String value)
```


Определяет путь (имя файла или имя каталога) для хранения временных данных при преобразовании в режиме экономии памяти.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Режим распознавания.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение RecognitionMode |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | Экземпляр ConversionProgressEventsTranslator |

### setRecognizeBullets(boolean value) {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```


Включите распознавание пуль.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRelativeHorizontalProximity(float value) {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```


В Pdf слова могут быть внутренне представлены операторами, которые печатают слова, независимо печатая их буквы или слоги. Таким образом, для обнаружения слов иногда нам нужно обнаруживать группы независимых символов, которые на самом деле являются словами. Этот параметр определяет ширину промежутка между текстовыми элементами (буквами, слогами), который должен рассматриваться как расстояние между словами при распознавании слов в исходном PDF-файле. (наличие пробела хотя бы при такой ширине между буквами означает, что элементы текста относятся к разным словам). Это нормировано по размеру шрифта - 1.0 означает 100% размера шрифта предполагаемого слова. ВНИМАНИЕ! Используется только в тех случаях, когда исходный PDF содержит определенные редко используемые шрифты, для которых невозможно вычислить оптимальное значение из шрифта. Таким образом, в подавляющем большинстве случаев этот параметр ничего не меняет в результирующем документе.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Относительная близость |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | логическое значение |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | Значение IWarningCallback |

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
