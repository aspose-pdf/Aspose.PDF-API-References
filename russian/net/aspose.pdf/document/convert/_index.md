---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Метод Document. Конвертировать документ и сохранить ошибки в указанный файл
type: docs
weight: 580
url: /ru/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Конвертировать документ и сохранить ошибки в указанный файл.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | String | Путь к файлу, где будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть конвертированы |
| transparencyAction | ConvertTransparencyAction | Действие для объектов с маскированными изображениями |

### Возвращаемое значение

Результат операции

### См. также

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Конвертировать документ и сохранить ошибки в указанный файл.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | Stream | Поток, где будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть конвертированы |
| transparencyAction | ConvertTransparencyAction | Действие для объектов с маскированными изображениями |

### Возвращаемое значение

Результат операции

### См. также

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Конвертировать документ и сохранить ошибки в указанный файл.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | String | Путь к файлу, где будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть конвертированы |

### Возвращаемое значение

Результат операции

### См. также

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Конвертировать документ, используя указанные параметры конвертации

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | PdfFormatConversionOptions | Набор параметров для конвертации PDF документа |

### Возвращаемое значение

Результат операции

### См. также

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Распознать изображения внутри документа и добавить строки hocr поверх них.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Действие для изображений, которые будут обработаны распознаванием hocr. |
| flattenImages | Boolean | Текст в pdf изображениях может быть закрашен с использованием механики масок, в этом случае изображения должны быть уплощены. |

### Возвращаемое значение

Результат операции. Если в документе нет изображений, возвращает !:false.

### См. также

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Распознать изображения внутри документа и добавить строки hocr поверх них.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | CallBackGetHocr | Действие для изображений, которые будут обработаны распознаванием hocr. |
| flattenImages | Boolean | Текст в pdf изображениях может быть закрашен с использованием механики масок, в этом случае изображения должны быть уплощены. |

### Возвращаемое значение

Результат операции. Если в документе нет изображений, возвращает !:false.

### См. также

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Конвертировать документ и сохранить ошибки в указанный поток.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | Stream | Поток, где будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть конвертированы |

### Возвращаемое значение

Результат операции

### См. также

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Конвертировать документ, применяя Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип Fixup. |
| outputLog | Stream | Журнал процесса. |
| onlyValidation | Boolean | Только валидация документа. |
| parameters | Object[] | Свойства для Fixup, которые не могут быть установлены. |

### Возвращаемое значение

Результат операции.

### См. также

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Конвертировать документ, применяя Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип Fixup. |
| outputLog | String | Журнал процесса. |
| onlyValidation | Boolean | Только валидация документа. |
| parameters | Object[] | Свойства для Fixup, которые не могут быть установлены. |

### Возвращаемое значение

Результат операции.

### См. также

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Конвертирует исходный файл в исходном формате в целевой файл в целевом формате.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя исходного файла. |
| loadOptions | LoadOptions | Формат исходного файла. |
| dstFileName | String | Имя целевого файла. |
| saveOptions | SaveOptions | Формат целевого файла. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Конвертирует поток в исходном формате в целевой файл в целевом формате.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | Stream | Исходный поток. |
| loadOptions | LoadOptions | Формат исходного потока. |
| dstFileName | String | Имя целевого файла. |
| saveOptions | SaveOptions | Формат целевого файла. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Конвертирует исходный файл в исходном формате в поток в целевом формате.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя исходного файла. |
| loadOptions | LoadOptions | Формат исходного файла. |
| dstStream | Stream | Целевой поток. |
| saveOptions | SaveOptions | Формат целевого потока. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Конвертирует поток в исходном формате в поток в целевом формате.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | Stream | Исходный поток. |
| loadOptions | LoadOptions | Формат исходного потока. |
| dstStream | Stream | Целевой поток. |
| saveOptions | SaveOptions | Формат целевого файла. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)