---
title: Convert
second_title: Aspose.PDF for .NET API 参考
description: 将源格式的源文件转换为目标格式的目标文件
type: docs
weight: 790
url: /zh/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

将源格式的源文件转换为目标格式的目标文件。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstFileName | String | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

将源格式的流转换为目标格式的目标文件。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | Stream | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstFileName | String | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

将源格式的源文件转换为目标格式的流。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstStream | Stream | 目标流。 |
| saveOptions | SaveOptions | 目标流格式。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

将源格式的流转换为目标格式的流。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | Stream | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstStream | Stream | 目标流。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | String | 存储注释的文件路径。 |
| format | PdfFormat | pdf 格式。 |
| action | ConvertErrorAction | 无法转换的对象的操作 |
| transparencyAction | ConvertTransparencyAction | 图像蒙版对象的操作 |

### 返回值

运算结果

### 也可以看看

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | Stream | 将存储评论的流。 |
| format | PdfFormat | pdf 格式。 |
| action | ConvertErrorAction | 无法转换的对象的操作 |
| transparencyAction | ConvertTransparencyAction | 图像蒙版对象的操作 |

### 返回值

运算结果

### 也可以看看

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | String | 存储注释的文件路径。 |
| format | PdfFormat | pdf 格式。 |
| action | ConvertErrorAction | 无法转换的对象的动作 |

### 返回值

运算结果

### 也可以看看

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

使用指定的转换选项转换文档

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | PdfFormatConversionOptions | 选项集转换PDF文档 |

### 返回值

运算结果

### 也可以看看

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(CallBackGetHocr callback)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | CallBackGetHocr | 对无法转换的对象的操作 |

### 返回值

运算结果

### 也可以看看

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

转换文档并将错误保存到指定的流中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | Stream | 将存储评论的流。 |
| format | PdfFormat | Pdf 格式。 |
| action | ConvertErrorAction | 无法转换的对象的动作 |

### 返回值

运算结果

### 也可以看看

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

通过应用修复转换文档。

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | Fixup | 修复类型。 |
| outputLog | Stream | 进程日志。 |
| onlyValidation | Boolean | 仅文档验证。 |
| parameters | Object[] | 无法设置的 Fixup 属性。 |

### 返回值

运算结果。

### 也可以看看

* enum [Fixup](../../fixup)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

通过应用修复转换文档。

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | Fixup | 修复类型。 |
| outputLog | String | 进程日志。 |
| onlyValidation | Boolean | 仅文档验证。 |
| parameters | Object[] | 无法设置的 Fixup 属性。 |

### 返回值

运算结果。

### 也可以看看

* enum [Fixup](../../fixup)
* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
