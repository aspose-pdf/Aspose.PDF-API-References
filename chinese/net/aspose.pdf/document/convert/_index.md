---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: 文档方法。转换文档并将错误保存到指定文件中
type: docs
weight: 580
url: /zh/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | 字符串 | 存储注释的文件路径。 |
| format | PdfFormat | PDF 格式。 |
| action | ConvertErrorAction | 对无法转换的对象的操作 |
| transparencyAction | ConvertTransparencyAction | 对图像遮罩对象的操作 |

### 返回值

操作结果

### 另请参阅

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | 流 | 存储注释的流。 |
| format | PdfFormat | PDF 格式。 |
| action | ConvertErrorAction | 对无法转换的对象的操作 |
| transparencyAction | ConvertTransparencyAction | 对图像遮罩对象的操作 |

### 返回值

操作结果

### 另请参阅

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

转换文档并将错误保存到指定文件中。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | 字符串 | 存储注释的文件路径。 |
| format | PdfFormat | PDF 格式。 |
| action | ConvertErrorAction | 对无法转换的对象的操作 |

### 返回值

操作结果

### 另请参阅

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
| options | PdfFormatConversionOptions | 转换 PDF 文档的选项集 |

### 返回值

操作结果

### 另请参阅

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
| callback | CallBackGetHocrWithPage | 对将通过 hocr 识别处理的图像的操作。 |
| flattenImages | 布尔值 | PDF 图像中的文本可以使用遮罩机制绘制，在这种情况下，图像必须被平整化。 |

### 返回值

操作结果。如果文档中没有图像，则返回 !:false。

### 另请参阅

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
| callback | CallBackGetHocr | 对将通过 hocr 识别处理的图像的操作。 |
| flattenImages | 布尔值 | PDF 图像中的文本可以使用遮罩机制绘制，在这种情况下，图像必须被平整化。 |

### 返回值

操作结果。如果文档中没有图像，则返回 !:false。

### 另请参阅

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

转换文档并将错误保存到指定流中。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | 流 | 存储注释的流。 |
| format | PdfFormat | PDF 格式。 |
| action | ConvertErrorAction | 对无法转换的对象的操作 |

### 返回值

操作结果

### 另请参阅

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
| fixup | Fixup | Fixup 类型。 |
| outputLog | 流 | 处理日志。 |
| onlyValidation | 布尔值 | 仅文档验证。 |
| parameters | Object[] | 不能设置的 Fixup 属性。 |

### 返回值

操作结果。

### 另请参阅

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
| fixup | Fixup | Fixup 类型。 |
| outputLog | 字符串 | 处理日志。 |
| onlyValidation | 布尔值 | 仅文档验证。 |
| parameters | Object[] | 不能设置的 Fixup 属性。 |

### 返回值

操作结果。

### 另请参阅

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

将源文件从源格式转换为目标文件的目标格式。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstFileName | 字符串 | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参阅

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

将源格式的流转换为目标文件的目标格式。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | 流 | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstFileName | 字符串 | 目标文件名。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参阅

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

将源文件从源格式转换为目标格式的流。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 源文件名。 |
| loadOptions | LoadOptions | 源文件格式。 |
| dstStream | 流 | 目标流。 |
| saveOptions | SaveOptions | 目标流格式。 |

### 另请参阅

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
| srcStream | 流 | 源流。 |
| loadOptions | LoadOptions | 源流格式。 |
| dstStream | 流 | 目标流。 |
| saveOptions | SaveOptions | 目标文件格式。 |

### 另请参阅

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)