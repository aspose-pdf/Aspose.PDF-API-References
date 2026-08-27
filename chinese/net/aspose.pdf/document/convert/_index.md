---
title: "Document.Convert"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 方法。将文档转换并将错误保存到指定文件中"
type: docs
weight: 600
url: /zh/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

转换文档并将错误保存到指定的文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | String | 存放注释的文件路径。 |
| 格式 | PdfFormat | PDF 格式。 |
| 操作 | ConvertErrorAction | 对无法转换的对象的操作。 |
| transparencyAction | ConvertTransparencyAction | 对图像遮罩对象的操作 |

### 返回值

操作结果

### 另请参见

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

转换文档并将错误保存到指定的文件中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | Stream | 存放注释的流。 |
| 格式 | PdfFormat | PDF 格式。 |
| 操作 | ConvertErrorAction | 对无法转换的对象的操作。 |
| transparencyAction | ConvertTransparencyAction | 对图像遮罩对象的操作 |

### 返回值

操作结果

### 另请参见

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

转换文档并将错误保存到指定的文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | String | 存放注释的文件路径。 |
| 格式 | PdfFormat | PDF 格式。 |
| 操作 | ConvertErrorAction | 对无法转换的对象的操作。 |

### 返回值

操作结果

### 另请参见

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

使用指定的转换选项转换文档

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | PdfFormatConversionOptions | 用于转换 PDF 文档的选项集合 |

### 返回值

操作结果

### 另请参见

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

识别文档中的图像并在其上添加 hocr 字符串。

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 回调 | CallBackGetHocrWithPage | 用于将由 hocr 识别处理的图像的操作。 |
| flattenImages | Boolean | pdf 图像中的文本可以使用遮罩机制进行绘制，在这种情况下必须将图像展平。 |

### 返回值

操作结果。如果文档中没有图像，则返回 !:false。

### 另请参见

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

识别文档中的图像并在其上添加 hocr 字符串。

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 回调 | CallBackGetHocr | 用于将由 hocr 识别处理的图像的操作。 |
| flattenImages | Boolean | pdf 图像中的文本可以使用遮罩机制进行绘制，在这种情况下必须将图像展平。 |

### 返回值

操作结果。如果文档中没有图像，则返回 !:false。

### 另请参见

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

转换文档并将错误保存到指定的流中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | Stream | 存放注释的流。 |
| 格式 | PdfFormat | Pdf 格式。 |
| 操作 | ConvertErrorAction | 对无法转换的对象的操作。 |

### 返回值

操作结果

### 另请参见

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

通过应用 Fixup 转换文档。

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 修复 | 修复 | Fixup 类型。 |
| outputLog | Stream | 进程日志。 |
| onlyValidation | Boolean | 仅文档验证。 |
| 参数 | Object[] | Fixup 的属性无法设置。 |

### 返回值

操作结果。

### 另请参见

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

通过应用 Fixup 转换文档。

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 修复 | 修复 | Fixup 类型。 |
| outputLog | String | 进程日志。 |
| onlyValidation | Boolean | 仅文档验证。 |
| 参数 | Object[] | Fixup 的属性无法设置。 |

### 返回值

操作结果。

### 另请参见

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

将源格式的源文件转换为目标格式的目标文件。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstFileName | String | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

将源格式的流转换为目标格式的文件。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | Stream | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstFileName | String | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

将源格式的源文件转换为目标格式的流。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstStream | Stream | 目标流。 |
| saveOptions | SaveOptions | 目标流格式。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

将源格式的流转换为目标格式的流。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | Stream | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstStream | Stream | 目标流。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


