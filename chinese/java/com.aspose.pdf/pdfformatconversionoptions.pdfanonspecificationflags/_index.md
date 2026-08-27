---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Aspose.PDF for Java API 参考"
description: "此类保存用于控制 PDF/A 转换的标志，适用于源 PDF 文档不符合 PDF 规范的情况。如果使用此类的标志，则会降低。"
type: docs
weight: 3740
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

此类持有标志，用于在源 PDF 文档不符合 PDF 规范的情况下控制 PDF/A 转换。如果使用此类的标志会降低性能，但在源 PDF 文档无法通过常规方式转换为 PDF/A 格式时是必要的。默认情况下，所有标志均设置为 false。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | 某些 PDF 文档包含内部数据中名称不同的字体。使用此标志可在 BaseFont 和 FontDescriptor.FontName 字段不同时强制特殊处理逻辑。 |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | 某些 PDF 文档包含内部数据中名称不同的字体。使用此标志可在 BaseFont 和 FontDescriptor.FontName 字段不同时强制特殊处理逻辑。 |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

构造函数

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

某些 PDF 文档包含内部数据中名称不同的字体。使用此标志可在 BaseFont 和 FontDescriptor.FontName 字段不同时强制特殊处理逻辑。

**Returns:**
布尔值

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

某些 PDF 文档包含内部数据中名称不同的字体。使用此标志可在 BaseFont 和 FontDescriptor.FontName 字段不同时强制特殊处理逻辑。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
