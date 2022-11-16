---
title: PdfFormatConversionOptions
second_title: Aspose.PDF для справки по Java API
description: представляет собой набор опций для преобразования документа PDF
type: docs
weight: 278
url: /ru/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Наследование:**
java.lang.Object
```
public class PdfFormatConversionOptions
```

представляет собой набор опций для преобразования документа PDF
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Конструктор |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Конструктор |
| [PdfFormatConversionOptions(PdfFormat format)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Конструктор |
| [PdfFormatConversionOptions(PdfFormat format, int action)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-) | Конструктор |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Конструктор |
| [PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [addNotAccessibleFont(String fontName)](#addNotAccessibleFont-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignStrategy()](#getAlignStrategy--) | Стратегия выравнивания текста. |
| [getAlignText()](#getAlignText--) | Этот флаг управляет выравниванием текста в преобразованном документе. |
| [getClass()](#getClass--) |  |
| [getConvertSoftMaskAction()](#getConvertSoftMaskAction--) | Действие для изображений с мягкой маской. |
| [getDefault()](#getDefault--) | Получает объект PdfFormatConversionOptions с параметрами по умолчанию. |
| [getErrorAction()](#getErrorAction--) | Действие для объектов, которые нельзя конвертировать |
| [getExcludeFontsStrategy()](#getExcludeFontsStrategy--) | Стратегии по исключению лишних шрифтов и уменьшению размера файла документа. |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) | Варианты для случаев, когда невозможно встроить некоторые шрифты в документ PDF. |
| [getFormat()](#getFormat--) | PDF формат. |
| [getIccProfileFileName()](#getIccProfileFileName--) | Получает имя файла имени профиля icc. |
| [getLogFileName()](#getLogFileName--) | Путь к файлу, в котором будут храниться комментарии. |
| [getLogStream()](#getLogStream--) | Поток, где будут храниться комментарии. |
| [getNonSpecificationCases()](#getNonSpecificationCases--) | Удерживает флаги для управления процессом преобразования PDF/A в случаях, когда исходный документ не соответствует спецификации PDF/A. |
| [getNotAccessibleFonts()](#getNotAccessibleFonts--) | Это свойство вне собственности. |
| [getOptimizeFileSize()](#getOptimizeFileSize--) | Получает флаг, который включает/отключает специальный режим преобразования для получения документа PDF/A с уменьшенным размером файла. |
| [getPuaTextProcessingStrategy()](#getPuaTextProcessingStrategy--) | Стратегия обработки символов из области частного использования Unicode (PUA). |
| [getSymbolicFontEncodingStrategy()](#getSymbolicFontEncodingStrategy--) | Стратегия копирования данных кодирования для символических шрифтов, если символический шрифт TrueType имеет более одной подтаблицы кодирования. |
| [getTransparencyAction()](#getTransparencyAction--) | Действие для объектов, замаскированных изображением |
| [getTransparencyResolution()](#getTransparencyResolution--) | Устанавливает разрешение при преобразовании прозрачных изображений. |
| [getUnicodeProcessingRules()](#getUnicodeProcessingRules--) | Правила решения проблем с отображением юникода. |
| [hashCode()](#hashCode--) |  |
| [isAsyncImageStreamsConversionMode()](#isAsyncImageStreamsConversionMode--) | Получает/задает запуск потоков изображений в асинхронном режиме. |
| [isLowMemoryMode()](#isLowMemoryMode--) | Включен ли режим преобразования нехватки памяти |
| [isPageByPageFontProcess()](#isPageByPageFontProcess--) | Включен ли режим анализа шрифтов на странице за страницей? |
| [isTransferInfo()](#isTransferInfo--) | Получает или задает, следует ли передавать данные из информации в метаданные при преобразовании в PDF 2.0. |
| [isTransparencyIgnore()](#isTransparencyIgnore--) | Значение по умолчанию FALSE и цвет прозрачности будут сохранены, чтобы сохранить внешний вид документа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignStrategy(byte alignStrategy)](#setAlignStrategy-byte-) | Стратегия выравнивания текста. |
| [setAlignText(boolean value)](#setAlignText-boolean-) | Этот флаг управляет выравниванием текста в преобразованном документе. |
| [setAsyncImageStreamsConversionMode(boolean value)](#setAsyncImageStreamsConversionMode-boolean-) | Получает/задает запуск потоков изображений в асинхронном режиме. |
| [setConvertSoftMaskAction(int value)](#setConvertSoftMaskAction-int-) | Действие для изображений с мягкой маской. |
| [setErrorAction(int value)](#setErrorAction-int-) | Действие для объектов, которые нельзя конвертировать |
| [setExcludeFontsStrategy(byte value)](#setExcludeFontsStrategy-byte-) | Стратегии по исключению лишних шрифтов и уменьшению размера файла документа. |
| [setFormat(PdfFormat value)](#setFormat-com.aspose.pdf.PdfFormat-) | PDF формат. |
| [setIccProfileFileName(String value)](#setIccProfileFileName-java.lang.String-) | Устанавливает имя файла имени профиля icc. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Путь к файлу, в котором будут храниться комментарии. |
| [setLogStream(OutputStream value)](#setLogStream-java.io.OutputStream-) | Поток, где будут храниться комментарии. |
| [setLowMemoryMode(boolean value)](#setLowMemoryMode-boolean-) | Включен ли режим преобразования нехватки памяти |
| [setOptimizeFileSize(boolean value)](#setOptimizeFileSize-boolean-) | Устанавливает флаг, который включает/отключает специальный режим преобразования для получения документа PDF/A с уменьшенным размером файла. |
| [setPageByPageFontProcess(boolean b)](#setPageByPageFontProcess-boolean-) | Включить анализ шрифта на странице за страницей |
| [setPuaTextProcessingStrategy(int value)](#setPuaTextProcessingStrategy-int-) | Стратегия обработки символов из области частного использования Unicode (PUA). |
| [setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Стратегия копирования данных кодирования для символических шрифтов, если символический шрифт TrueType имеет более одной подтаблицы кодирования. |
| [setTransferInfo(boolean value)](#setTransferInfo-boolean-) | Получает или задает, следует ли передавать данные из информации в метаданные при преобразовании в PDF 2.0. |
| [setTransparencyAction(int value)](#setTransparencyAction-int-) | Действие для объектов, замаскированных изображением |
| [setTransparencyIgnore(boolean value)](#setTransparencyIgnore-boolean-) | Значение по умолчанию FALSE и цвет прозрачности будут сохранены, чтобы сохранить внешний вид документа. |
| [setTransparencyResolution(int dpi)](#setTransparencyResolution-int-) | Устанавливает разрешение при преобразовании прозрачных изображений. |
| [setUnicodeProcessingRules(ToUnicodeProcessingRules value)](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Правила решения проблем с отображением юникода. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |
| action | int | Действие для объектов, которые нельзя конвертировать |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |

### PdfFormatConversionOptions(PdfFormat format) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(PdfFormat format)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |

### PdfFormatConversionOptions(PdfFormat format, int action) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(PdfFormat format, int action)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |
| action | int | Действие для объектов, которые нельзя конвертировать |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |
| action | int | Действие для объектов, которые нельзя конвертировать |
| transparencyAction | int | Действие для объектов, замаскированных изображением |

### PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action) {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Поток, где будут храниться комментарии |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат PDF |
| action | int | Действие для объектов, которые нельзя конвертировать |

### addNotAccessibleFont(String fontName) {#addNotAccessibleFont-java.lang.String-}
```
public void addNotAccessibleFont(String fontName)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String |  |

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
### getAlignStrategy() {#getAlignStrategy--}
```
public byte getAlignStrategy()
```


Стратегия выравнивания текста. Этот параметр имеет смысл только тогда, когда флаг AlignText установлен в true.

**Возвращает:**
byte — элемент SegmentAlignStrategy
### getAlignText() {#getAlignText--}
```
public boolean getAlignText()
```


Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию преобразование документа не влияет на выравнивание текста и оставляет текст как есть. Но в некоторых случаях подстановка шрифта приводит к перекрытию текста или появлению лишних пробелов в преобразованном документе. При установке этого флага будут выполняться специальные операции выравнивания. Этот флаг следует устанавливать только для документов, в которых есть проблемы с перекрывающимся текстом или дополнительными текстовыми пробелами, что приводит к снижению производительности при использовании этого флага и в некоторых случаях может привести к повреждению текстового содержимого.

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getConvertSoftMaskAction() {#getConvertSoftMaskAction--}
```
public final int getConvertSoftMaskAction()
```


Действие для изображений с мягкой маской.

**Возвращает:**
интервал - целочисленное значение
### getDefault() {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```


Получает объект PdfFormatConversionOptions с параметрами по умолчанию.

**Возвращает:**
[PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) Объект PdfFormatConversionOptions
### getErrorAction() {#getErrorAction--}
```
public int getErrorAction()
```


Действие для объектов, которые нельзя конвертировать

**Возвращает:**
int — элемент ConvertErrorAction
### getExcludeFontsStrategy() {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```


Стратегии по исключению лишних шрифтов и уменьшению размера файла документа. Этот параметр имеет смысл только тогда, когда флаг OptimizeFileSize установлен в значение true. По умолчанию используется комбинация стратегий SubsetFonts и RemoveDuplicatedFonts.

**Возвращает:**
байт - значение байта
### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```


Варианты для случаев, когда невозможно встроить некоторые шрифты в документ PDF.

**Возвращает:**
[FontEmbeddingOptions](../../com.aspose.pdf/fontembeddingoptions) - Объект FontEmbeddingOptions
### getFormat() {#getFormat--}
```
public PdfFormat getFormat()
```


PDF формат.

**Возвращает:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - Элемент PDFFormat
### getIccProfileFileName() {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```


Получает имя файла имени профиля icc. В случае null используется профиль icc по умолчанию.

**Возвращает:**
java.lang.String — строковый объект
### getLogFileName() {#getLogFileName--}
```
public String getLogFileName()
```


Путь к файлу, в котором будут храниться комментарии.

**Возвращает:**
java.lang.String — строковый объект
### getLogStream() {#getLogStream--}
```
public OutputStream getLogStream()
```


Поток, где будут храниться комментарии.

**Возвращает:**
java.io.OutputStream — объект OutputStream
### getNonSpecificationCases() {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```


Удерживает флаги для управления процессом преобразования PDF/A в случаях, когда исходный документ не соответствует спецификации PDF/A.

**Возвращает:**
[PdfANonSpecificationFlags](../../com.aspose.pdf/pdfanonspecificationflags) - Объект PdfANonSpecificationFlags
### getNotAccessibleFonts() {#getNotAccessibleFonts--}
```
public String[] getNotAccessibleFonts()
```


Это свойство вне собственности. Он содержит все шрифты (имена шрифтов), которые не были найдены на компьютере при последнем преобразовании PDF/A.

**Возвращает:**
java.lang.String[] - Массив строк
### getOptimizeFileSize() {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```


Получает флаг, который включает/отключает специальный режим преобразования для получения документа PDF/A с уменьшенным размером файла.

Теперь этот флаг влияет на оптимизацию шрифтов, используемых в PDF-документе, возможно, в будущем этот флаг также будет использоваться для включения оптимизации для других структур данных, например графических.

Установка этого флага и режима может значительно уменьшить размер файла, но в то же время может значительно снизить производительность конвертации.

**Возвращает:**
boolean - логическое значение
### getPuaTextProcessingStrategy() {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```


Стратегия обработки символов из области частного использования Unicode (PUA).

**Возвращает:**
int - элемент PuaProcessingStrategy
### getSymbolicFontEncodingStrategy() {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```


Стратегия копирования данных кодирования для символических шрифтов, если символический шрифт TrueType имеет более одной подтаблицы кодирования.

**Возвращает:**
[PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) - Объект PdfASymbolicFontEncodingStrategy
### getTransparencyAction() {#getTransparencyAction--}
```
public int getTransparencyAction()
```


Действие для объектов, замаскированных изображением

**Возвращает:**
int — элемент ConvertTransparencyAction
### getTransparencyResolution() {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```


Устанавливает разрешение при преобразовании прозрачных изображений. Чем выше разрешение, тем ниже скорость конвертации. Значение по умолчанию — 300.

**Возвращает:**
int - значение разрешения
### getUnicodeProcessingRules() {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```


Правила решения проблем с отображением юникода. Может быть нулевым.

**Возвращает:**
[ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) - Объект ToUnicodeProcessingRules
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isAsyncImageStreamsConversionMode() {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```


Получает/задает запуск потоков изображений в асинхронном режиме.

**Возвращает:**
boolean - логическое значение
### isLowMemoryMode() {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```


Включен ли режим преобразования нехватки памяти

**Возвращает:**
boolean - логическое значение
### isPageByPageFontProcess() {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```


Включен ли режим анализа шрифтов на странице за страницей?

Значение по умолчанию = ложь

**Возвращает:**
boolean - логическое значение
### isTransferInfo() {#isTransferInfo--}
```
public final boolean isTransferInfo()
```


Получает или задает, следует ли передавать данные из информации в метаданные при преобразовании в PDF 2.0. Верно по умолчанию.

**Возвращает:**
boolean - логическое значение
### isTransparencyIgnore() {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```


Значение по умолчанию FALSE и цвет прозрачности будут сохранены, чтобы сохранить внешний вид документа. При значении TRUE цвет прозрачности будет преобразован в непрозрачность, некоторые объекты могут быть закрыты.

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




### setAlignStrategy(byte alignStrategy) {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```


Стратегия выравнивания текста. Этот параметр имеет смысл только тогда, когда флаг AlignText установлен в true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignStrategy | byte | Элемент SegmentAlignStrategy |

### setAlignText(boolean value) {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```


Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию преобразование документа не влияет на выравнивание текста и оставляет текст как есть. Но в некоторых случаях подстановка шрифта приводит к перекрытию текста или появлению лишних пробелов в преобразованном документе. При установке этого флага будут выполняться специальные операции выравнивания. Этот флаг следует устанавливать только для документов, в которых есть проблемы с перекрывающимся текстом или дополнительными текстовыми пробелами, что приводит к снижению производительности при использовании этого флага и в некоторых случаях может привести к повреждению текстового содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAsyncImageStreamsConversionMode(boolean value) {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```


Получает/задает запуск потоков изображений в асинхронном режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setConvertSoftMaskAction(int value) {#setConvertSoftMaskAction-int-}
```
public final void setConvertSoftMaskAction(int value)
```


Действие для изображений с мягкой маской.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setErrorAction(int value) {#setErrorAction-int-}
```
public void setErrorAction(int value)
```


Действие для объектов, которые нельзя конвертировать

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ConvertErrorAction |

### setExcludeFontsStrategy(byte value) {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```


Стратегии по исключению лишних шрифтов и уменьшению размера файла документа. Этот параметр имеет смысл только тогда, когда флаг OptimizeFileSize установлен в значение true. По умолчанию используется комбинация стратегий SubsetFonts и RemoveDuplicatedFonts.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | логическое значение |

### setFormat(PdfFormat value) {#setFormat-com.aspose.pdf.PdfFormat-}
```
public void setFormat(PdfFormat value)
```


PDF формат.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | Элемент PdfFormat |

### setIccProfileFileName(String value) {#setIccProfileFileName-java.lang.String-}
```
public void setIccProfileFileName(String value)
```


Устанавливает имя файла имени профиля icc. В случае null используется профиль icc по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public void setLogFileName(String value)
```


Путь к файлу, в котором будут храниться комментарии.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setLogStream(OutputStream value) {#setLogStream-java.io.OutputStream-}
```
public void setLogStream(OutputStream value)
```


Поток, где будут храниться комментарии.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setLowMemoryMode(boolean value) {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```


Включен ли режим преобразования нехватки памяти

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOptimizeFileSize(boolean value) {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```


Устанавливает флаг, который включает/отключает специальный режим преобразования для получения документа PDF/A с уменьшенным размером файла.

Теперь этот флаг влияет на оптимизацию шрифтов, используемых в PDF-документе, возможно, в будущем этот флаг также будет использоваться для включения оптимизации для других структур данных, например графических.

Установка этого флага и режима может значительно уменьшить размер файла, но в то же время может значительно снизить производительность конвертации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPageByPageFontProcess(boolean b) {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```


Включить анализ шрифта на странице за страницей

Значение по умолчанию = ложь

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| b | boolean | логическое значение |

### setPuaTextProcessingStrategy(int value) {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```


Стратегия обработки символов из области частного использования Unicode (PUA).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value) {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
```
public void setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)
```


Стратегия копирования данных кодирования для символических шрифтов, если символический шрифт TrueType имеет более одной подтаблицы кодирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) | Объект PdfASymbolicFontEncodingStrategy |

### setTransferInfo(boolean value) {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```


Получает или задает, следует ли передавать данные из информации в метаданные при преобразовании в PDF 2.0. Верно по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTransparencyAction(int value) {#setTransparencyAction-int-}
```
public void setTransparencyAction(int value)
```


Действие для объектов, замаскированных изображением

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ConvertTransparencyAction |

### setTransparencyIgnore(boolean value) {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```


Значение по умолчанию FALSE и цвет прозрачности будут сохранены, чтобы сохранить внешний вид документа. При значении TRUE цвет прозрачности будет преобразован в непрозрачность, некоторые объекты могут быть закрыты.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTransparencyResolution(int dpi) {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```


Устанавливает разрешение при преобразовании прозрачных изображений. Чем выше разрешение, тем ниже скорость конвертации. Значение по умолчанию — 300.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi | int | Значение разрешения |

### setUnicodeProcessingRules(ToUnicodeProcessingRules value) {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
```
public void setUnicodeProcessingRules(ToUnicodeProcessingRules value)
```


Правила решения проблем с отображением юникода. Может быть нулевым.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) | Объект ToUnicodeProcessingRules |

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
