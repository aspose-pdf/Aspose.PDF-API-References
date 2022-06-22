---
title: Convert
second_title: Aspose.PDF для справочника API .NET
description: Преобразует исходный файл в исходном формате в целевой файл в целевом формате.
type: docs
weight: 790
url: /ru/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Преобразует исходный файл в исходном формате в целевой файл в целевом формате.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя исходного файла. |
| loadOptions | LoadOptions | Формат исходного файла. |
| dstFileName | String | Имя файла назначения. |
| saveOptions | SaveOptions | Формат конечного файла. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Преобразует поток в исходном формате в целевой файл в целевом формате.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | Stream | Исходный поток. |
| loadOptions | LoadOptions | Формат исходного потока. |
| dstFileName | String | Имя файла назначения. |
| saveOptions | SaveOptions | Формат конечного файла. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Преобразует исходный файл в исходном формате в поток в целевом формате.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Имя исходного файла. |
| loadOptions | LoadOptions | Формат исходного файла. |
| dstStream | Stream | Целевой поток. |
| saveOptions | SaveOptions | Формат конечного потока. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Преобразует поток исходного формата в поток целевого формата.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | Stream | Исходный поток. |
| loadOptions | LoadOptions | Формат исходного потока. |
| dstStream | Stream | Целевой поток. |
| saveOptions | SaveOptions | Формат конечного файла. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Преобразование документа и сохранение ошибок в указанный файл.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | String | Путь к файлу, в котором будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть преобразованы |
| transparencyAction | ConvertTransparencyAction | Действие для объектов, замаскированных изображением |

### Возвращаемое значение

Результат операции

### Смотрите также

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Преобразование документа и сохранение ошибок в указанный файл.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | Stream | Поток, в котором будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть преобразованы |
| transparencyAction | ConvertTransparencyAction | Действие для объектов, замаскированных изображением |

### Возвращаемое значение

Результат операции

### Смотрите также

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Преобразование документа и сохранение ошибок в указанный файл.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | String | Путь к файлу, в котором будут храниться комментарии. |
| format | PdfFormat | Формат pdf. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть преобразованы |

### Возвращаемое значение

Результат операции

### Смотрите также

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Преобразование документа с использованием указанных параметров преобразования

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | PdfFormatConversionOptions | набор опций для конвертировать PDF-документ |

### Возвращаемое значение

Результат операции

### Смотрите также

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Преобразование документа и сохранение ошибок в указанный файл.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | CallBackGetHocr | Действие для объектов, которые не могут быть преобразованы |

### Возвращаемое значение

результат операции

### Смотрите также

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Конвертировать документ и сохранять ошибки в указанный поток.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | Stream | Поток, в котором будут храниться комментарии. |
| format | PdfFormat | Формат PDF. |
| action | ConvertErrorAction | Действие для объектов, которые не могут быть преобразованы |

### Возвращаемое значение

Результат операции

### Смотрите также

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Конвертируйте документ, применив Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип исправления. |
| outputLog | Stream | Журнал процесса. |
| onlyValidation | Boolean | Только проверка документа. |
| parameters | Object[] | Свойства для Fixup, которые нельзя установить. |

### Возвращаемое значение

Результат операции.

### Смотрите также

* enum [Fixup](../../fixup)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Конвертируйте документ, применив Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип исправления. |
| outputLog | String | Журнал процесса. |
| onlyValidation | Boolean | Только проверка документа. |
| parameters | Object[] | Свойства для Fixup, которые нельзя установить. |

### Возвращаемое значение

Результат операции.

### Смотрите также

* enum [Fixup](../../fixup)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
