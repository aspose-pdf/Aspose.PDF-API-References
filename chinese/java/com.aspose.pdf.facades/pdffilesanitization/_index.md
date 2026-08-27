---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Aspose.PDF for Java API 参考"
description: "表示清理和恢复 API。如果无法以其他方式创建/打开文档，请使用它。"
type: docs
weight: 510
url: /zh/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

表示清理和恢复 API。如果无法以其他方式创建/打开文档，请使用它。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | 初始化一个新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | 绑定用于清理的 Pdf 流。 |
| [bindPdf](#bindPdf-java.lang.String-) | 绑定用于清理的 Pdf 文件。 |
| [close](#close--) | 关闭该外观。 |
| [getLog](#getLog--) | 文件保存后，您可以检查对文件所做的操作。 |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | 允许为文档生成新的 xref 和 trailer。 |
| [getUseTrimBottom](#getUseTrimBottom--) | 允许删除 pdf 数据之后的内容 |
| [getUseTrimTop](#getUseTrimTop--) | 允许删除 pdf 数据之前的内容。 |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | 删除带有 trailer 的旧 xref，并创建新的 xref 和 trailer。 |
| [recover](#recover--) | 恢复文档。使用属性进行自定义。 |
| [save](#save-java.io.OutputStream-) | 将结果 PDF 保存到流中。 |
| [save](#save-java.lang.String-) | 将结果 PDF 保存到文件中。 |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | 允许为文档生成新的 xref 和 trailer。 |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | 允许删除 pdf 数据之后的内容 |
| [setUseTrimTop](#setUseTrimTop-boolean-) | 允许删除 pdf 数据之前的内容。 |
| [trimBottom](#trimBottom--) | 删除最后一个 %%EOF 之后的数据。 |
| [trimTop](#trimTop--) | 删除 %PDF 之前的数据。 |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

初始化一个新实例。

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
初始化 facade。

### bindPdf {#bindPdf-java.io.InputStream-}
绑定用于清理的 Pdf 流。

### bindPdf {#bindPdf-java.lang.String-}
绑定用于清理的 Pdf 文件。

### close {#close--}
```
public void close()
```

关闭该外观。

### getLog {#getLog--}
```
public final List < String > getLog()
```

文件保存后，您可以检查对文件所做的操作。

**Returns:**
String 元素列表

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

允许为文档生成新的 xref 和 trailer。

**Returns:**
布尔值

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

允许删除 pdf 数据之后的内容

**Returns:**
布尔值

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

允许删除 pdf 数据之前的内容。

**Returns:**
布尔值

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

删除带有 trailer 的旧 xref，并创建新的 xref 和 trailer。

### recover {#recover--}
```
public final void recover()
```

恢复文档。使用属性进行自定义。

### save {#save-java.io.OutputStream-}
将结果 PDF 保存到流中。

### save {#save-java.lang.String-}
将结果 PDF 保存到文件中。

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

允许为文档生成新的 xref 和 trailer。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

允许删除 pdf 数据之后的内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

允许删除 pdf 数据之前的内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

删除最后一个 %%EOF 之后的数据。

### trimTop {#trimTop--}
```
public final void trimTop()
```

删除 %PDF 之前的数据。
