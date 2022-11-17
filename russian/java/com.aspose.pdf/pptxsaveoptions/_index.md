---
title: PptxSaveOptions
second_title: Aspose.PDF для справки по Java API
description: Сохранить параметры для экспорта в формат SVG
type: docs
weight: 292
url: /ru/java/com.aspose.pdf/pptxsaveoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Сохранить параметры для экспорта в формат SVG
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PptxSaveOptions()](#PptxSaveOptions--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [getImageResolution()](#getImageResolution--) | Получает или задает разрешение изображения (т/д). |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [getSaveFormat()](#getSaveFormat--) | Формат сохранения данных. |
| [getSeparateImages()](#getSeparateImages--) | Если установлено значение true, изображения отделяются от всей остальной графики. |
| [getSlidesAsImages()](#getSlidesAsImages--) | Если установлено значение true, то все содержимое распознается как изображения (по одному на страницу). |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [isOptimizeTextBoxes()](#isOptimizeTextBoxes--) | Переключает распознавание текстовых столбцов |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [setImageResolution(int value)](#setImageResolution-int-) | Получает или задает разрешение изображения (т/д). |
| [setOptimizeTextBoxes(boolean value)](#setOptimizeTextBoxes-boolean-) | Переключает распознавание текстовых столбцов |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [setSeparateImages(boolean value)](#setSeparateImages-boolean-) | Если установлено значение true, изображения отделяются от всей остальной графики. |
| [setSlidesAsImages(boolean value)](#setSlidesAsImages-boolean-) | Если установлено значение true, то все содержимое распознается как изображения (по одному на страницу). |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PptxSaveOptions() {#PptxSaveOptions--}
```
public PptxSaveOptions()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**Возвращает:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - Экземпляр ConversionProgressEventHandler
### getImageResolution() {#getImageResolution--}
```
public final int getImageResolution()
```


Получает или задает разрешение изображения (т/д). По умолчанию — 192 dpi.

**Возвращает:**
интервал - целочисленное значение
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Возвращает:**
com.aspose.pdf.ConversionProgressEventsTranslator — экземпляр ConversionProgressEventsTranslator
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Формат сохранения данных.

**Возвращает:**
[SaveFormat](../../com.aspose.pdf/saveformat) - Значение формата сохранения
### getSeparateImages() {#getSeparateImages--}
```
public boolean getSeparateImages()
```


Если установлено значение true, изображения отделяются от всей остальной графики.

**Возвращает:**
boolean - логическое значение
### getSlidesAsImages() {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```


Если установлено значение true, то все содержимое распознается как изображения (по одному на страницу).

**Возвращает:**
boolean - логическое значение
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
### isOptimizeTextBoxes() {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```


Переключает распознавание текстовых столбцов

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




### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole);
     doc.Save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | Экземпляр ConversionProgressEventHandler |

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

### setImageResolution(int value) {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```


Получает или задает разрешение изображения (т/д). По умолчанию — 192 dpi.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setOptimizeTextBoxes(boolean value) {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```


Переключает распознавание текстовых столбцов

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | Экземпляр ConversionProgressEventsTranslator |

### setSeparateImages(boolean value) {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```


Если установлено значение true, изображения отделяются от всей остальной графики.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSlidesAsImages(boolean value) {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```


Если установлено значение true, то все содержимое распознается как изображения (по одному на страницу).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
