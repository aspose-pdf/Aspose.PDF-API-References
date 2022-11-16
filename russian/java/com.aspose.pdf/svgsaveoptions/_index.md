---
title: SvgSaveOptions
second_title: Aspose.PDF для справки по Java API
description: Сохранить параметры для экспорта в формат SVG
type: docs
weight: 344
url: /ru/java/com.aspose.pdf/svgsaveoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Сохранить параметры для экспорта в формат SVG
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgSaveOptions()](#SvgSaveOptions--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomStrategyOfEmbeddedImagesSaving()](#getCustomStrategyOfEmbeddedImagesSaving--) | Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов внешних изображений (например, встроенных BMP или JPEG), встроенных в сохраненный SVG. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [getSaveFormat()](#getSaveFormat--) | Формат сохранения данных. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [isCompressOutputToZipArchive()](#isCompressOutputToZipArchive--) | Указывает, будут ли выходные данные создаваться как один zip-архив. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [isScaleToPixels()](#isScaleToPixels--) | Указывает, следует ли масштабировать выходной документ от типографских точек до пикселей. |
| [isTreatTargetFileNameAsDirectory()](#isTreatTargetFileNameAsDirectory--) | Эта опция определяет, будет ли создан целевой каталог (если он еще отсутствует) с тем же именем, что и запрошенный выходной файл, вместо самого запрошенного выходного файла. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [setCompressOutputToZipArchive(boolean compressOutputToZipArchive)](#setCompressOutputToZipArchive-boolean-) | Указывает, будут ли выходные данные создаваться как один zip-архив. |
| [setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов внешних изображений (например, встроенных BMP или JPEG), встроенных в сохраненный SVG. |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [setScaleToPixels(boolean scaleToPixels)](#setScaleToPixels-boolean-) | Указывает, следует ли масштабировать выходной документ от типографских точек до пикселей. |
| [setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)](#setTreatTargetFileNameAsDirectory-boolean-) | Эта опция определяет, будет ли создан целевой каталог (если он еще отсутствует) с тем же именем, что и запрошенный выходной файл, вместо самого запрошенного выходного файла. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgSaveOptions() {#SvgSaveOptions--}
```
public SvgSaveOptions()
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
### getCustomStrategyOfEmbeddedImagesSaving() {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```


Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов внешних изображений (например, встроенных BMP или JPEG), встроенных в сохраненный SVG. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URI сохраненного ресурса в сгенерированном SVG. Если обработка того или иного файла по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, установите в пользовательском коде флаг «CustomProcessingCancelled» переменной параметра «imageSavingInfo». этот ресурс должен быть сделан в самом конвертере, как если бы не было никакого внешнего пользовательского кода.

**Возвращает:**
[EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) - Экземпляр EmbeddedImagesSavingStrategy
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
### isCompressOutputToZipArchive() {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```


Указывает, будут ли выходные данные создаваться как один zip-архив. Обратитесь к комментарию к опциям «TreatTargetFileNameAsDirectory», чтобы увидеть правила именования svg-файлов страниц для многостраничного исходного документа, которые также применяются к сжатому набору выходных файлов.

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
### isScaleToPixels() {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```


Указывает, следует ли масштабировать выходной документ от типографских точек до пикселей.

**Возвращает:**
boolean - логическое значение
### isTreatTargetFileNameAsDirectory() {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```


 Эта опция определяет, будет ли создан целевой каталог (если он еще отсутствует) с тем же именем, что и запрошенный выходной файл, вместо самого запрошенного выходного файла. Это так, что в этом каталоге будут находиться все выходные SVG-изображения страниц (как описано ниже). Если нет, выходные файлы страниц, отличных от первой, будут созданы точно в запрошенном каталоге в качестве основного выходного файла, но будут содержать суффикс в имени файла.\_[2...n], который определяется номером страницы, например, если Вы определяете выходной файл "C:\\AsposeTests\\output.svg" и вывод будет содержать несколько svg-файлов страниц, тогда файлы страниц будут создаваться также в директории "C:\\AsposeTests\\" и имеют имена "output.svg", "output\_2.svg», «вывод\_3.svg и т. д.

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

### setCompressOutputToZipArchive(boolean compressOutputToZipArchive) {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```


Указывает, будут ли выходные данные создаваться как один zip-архив. Обратитесь к комментарию к опциям «TreatTargetFileNameAsDirectory», чтобы увидеть правила именования svg-файлов страниц для многостраничного исходного документа, которые также применяются к сжатому набору выходных файлов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| compressOutputToZipArchive | boolean | логическое значение |

### setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving) {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
```
public void setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)
```


Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов внешних изображений (например, встроенных BMP или JPEG), встроенных в сохраненный SVG. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URI сохраненного ресурса в сгенерированном SVG. Если обработка того или иного файла по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, установите в пользовательском коде флаг «CustomProcessingCancelled» переменной параметра «imageSavingInfo». этот ресурс должен быть сделан в самом конвертере, как если бы не было никакого внешнего пользовательского кода.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customStrategyOfEmbeddedImagesSaving | [EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) | Экземпляр EmbeddedImagesSavingStrategy |

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

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | Экземпляр ConversionProgressEventsTranslator |

### setScaleToPixels(boolean scaleToPixels) {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```


Указывает, следует ли масштабировать выходной документ от типографских точек до пикселей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleToPixels | boolean | логическое значение |

### setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory) {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```


 Эта опция определяет, будет ли создан целевой каталог (если он еще отсутствует) с тем же именем, что и запрошенный выходной файл, вместо самого запрошенного выходного файла. Это так, что в этом каталоге будут находиться все выходные SVG-изображения страниц (как описано ниже). Если нет, выходные файлы страниц, отличных от первой, будут созданы точно в запрошенном каталоге в качестве основного выходного файла, но будут содержать суффикс в имени файла.\_[2...n], который определяется номером страницы, например, если Вы определяете выходной файл "C:\\AsposeTests\\output.svg" и вывод будет содержать несколько svg-файлов страниц, тогда файлы страниц будут создаваться также в директории "C:\\AsposeTests\\" и имеют имена "output.svg", "output\_2.svg», «вывод\_3.svg и т. д.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| treatTargetFileNameAsDirectory | boolean | логическое значение |

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
