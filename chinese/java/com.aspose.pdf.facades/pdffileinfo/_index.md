---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于访问 PDF 文档元信息的类。"
type: docs
weight: 490
url: /zh/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

表示用于访问 PDF 文档元信息的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | 初始化 facade。 |
| [clearInfo](#clearInfo--) | 清除 PDF 文档的所有元信息。 |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [dispose](#dispose--) | 关闭此实例使用的所有资源。此方法已过时，请改用 close()。 |
| [getAuthor](#getAuthor--) | 获取 PDF 文档的 Author 信息。 |
| [getCreationDate](#getCreationDate--) | 获取 PDF 文档的 CreationDate 信息。 |
| [getCreator](#getCreator--) | 获取 PDF 文档的 Creator 信息。 |
| [getDocumentPrivilege](#getDocumentPrivilege--) | 获取 PDF 文档的特权设置。 |
| [getHeader](#getHeader--) | <p> 获取 PDF 文档的自定义信息。 </p> |
| [getInputFile](#getInputFile--) | 获取输入文件。 |
| [getInputStream](#getInputStream--) | 获取输入流。 |
| [getKeywords](#getKeywords--) | 获取 PDF 文档的关键词信息。 |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | 获取 PDF 文档中具有属性名称的自定义信息。如果没有匹配该名称的属性，则返回空字符串。 |
| [getModDate](#getModDate--) | 获取 PDF 文档的 ModDate 日期信息。 |
| [getNumberOfPages](#getNumberOfPages--) | 获取文档的页数。 |
| [getPageHeight](#getPageHeight-int-) | 获取指定页面的高度。 |
| [getPageRotation](#getPageRotation-int-) | 获取指定页面的旋转。 |
| [getPageWidth](#getPageWidth-int-) | 获取指定页面的宽度。 |
| [getPageXOffset](#getPageXOffset-int-) | 获取指定页面显示区域的水平偏移量。 |
| [getPageYOffset](#getPageYOffset-int-) | 获取指定页面显示区域的垂直偏移量。 |
| [getPasswordType](#getPasswordType--) | 返回用于创建 PdfFileInfo 实例的密码类型。请参阅 {@code PasswordType} 中的可能取值。请注意，PDF 文档可以使用用户（或打开）密码和所有者（或权限、编辑）密码两者打开。 |
| [getPdfVersion](#getPdfVersion--) | 获取 PDF 文档的版本信息。 |
| [getProducer](#getProducer--) | 获取 PDF 文档的 Producer 信息。 |
| [getSubject](#getSubject--) | 获取 PDF 文档的 Subject 信息。 |
| [getTitle](#getTitle--) | 获取 PDF 文档的 Title 信息。 |
| [getUseStrictValidation](#getUseStrictValidation--) | 通过使用 {@code IsPdfFile}({@link #isPdfFile}) 属性来使用严格的验证规则。 |
| [hasCollection](#hasCollection--) | 如果当前输入文件是包含 PDF 文件集合的 "Portfolio" 文件，则返回 true。 |
| [hasEditPassword](#hasEditPassword--) | 如果需要密码来修改权限或文档安全属性，则返回 true。请注意，只有在 {@code PdfFileInfo} 构造函数中提供了有效密码时，才能读取此属性。如果 PasswordType 为 Inaccessible（表示提供了无效密码），读取此属性将因 {@code InvalidPasswordException} 而失败。 |
| [hasOpenPassword](#hasOpenPassword--) | 如果需要密码才能打开受密码保护的 PDF 文档，则返回 true。 |
| [isEncrypted](#isEncrypted--) | 检查 PDF 文档是否已加密。 |
| [isPdfFile](#isPdfFile--) | 检查源输入是否为有效的 PDF 文件。 |
| [save](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定文件。 |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | 将更新后的 PDF 文档保存到指定流中。 |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | 将更新后的 PDF 文档保存到指定文件中。 |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | 通过设置文件信息显式更改指定的属性，其他属性保持不变。 |
| [setAuthor](#setAuthor-java.lang.String-) | 设置 PDF 文档的 Author 信息。 |
| [setCreationDate](#setCreationDate-java.lang.String-) | 设置 PDF 文档的 CreationDate 信息。 |
| [setCreator](#setCreator-java.lang.String-) | 设置 PDF 文档的 Creator 信息。 |
| [setHeader](#setHeader-java.util.Map-) | 设置 PDF 文档的自定义信息。 |
| [setInputFile](#setInputFile-java.lang.String-) | 设置输入文件。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setKeywords](#setKeywords-java.lang.String-) | 设置 PDF 文档的 Keywords 信息。 |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | 设置 PDF 文档的自定义信息。 |
| [setModDate](#setModDate-java.lang.String-) | 设置 PDF 文档的 ModDate 日期信息。 |
| [setSubject](#setSubject-java.lang.String-) | 设置 PDF 文档的 Subject 信息。 |
| [setTitle](#setTitle-java.lang.String-) | 设置 PDF 文档的 Title 信息。 |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | 通过使用 {@code IsPdfFile}({@link #isPdfFile}) 属性来使用严格的验证规则。 |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
初始化 facade。

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

清除 PDF 文档的所有元信息。

### close {#close--}
```
public void close()
```

关闭此文档使用的所有资源。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭此实例使用的所有资源。此方法已过时，请改用 close()。

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

获取 PDF 文档的 Author 信息。

**Returns:**
字符串值

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

获取 PDF 文档的 CreationDate 信息。

**Returns:**
字符串值

### getCreator {#getCreator--}
```
public String getCreator()
```

获取 PDF 文档的 Creator 信息。

**Returns:**
字符串值

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

获取 PDF 文档的特权设置。

**Returns:**
PDF 文档的权限设置。

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> 获取 PDF 文档的自定义信息。 </p>

**Returns:**
{@code Map<String, String>} 对象

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

获取输入文件。

**Returns:**
字符串值

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

获取输入流。

**Returns:**
InputStream 对象

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

获取 PDF 文档的关键词信息。

**Returns:**
字符串值

### getMetaInfo {#getMetaInfo-java.lang.String-}
获取 PDF 文档中具有属性名称的自定义信息。如果没有匹配该名称的属性，则返回空字符串。

### getModDate {#getModDate--}
```
public String getModDate()
```

获取 PDF 文档的 ModDate 日期信息。

**Returns:**
字符串值

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

获取文档的页数。

**Returns:**
int 值

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

获取指定页面的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNum |  | 页码。 |

**Returns:**
页面的高度。

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

获取指定页面的旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNum |  | 页码。 |

**Returns:**
页面的旋转。该值可能为 0,90,180,270。

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

获取指定页面的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNum |  | 页码。 |

**Returns:**
页面的宽度。

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

获取指定页面显示区域的水平偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNum |  | 页码。 |

**Returns:**
页面左侧的水平偏移。

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

获取指定页面显示区域的垂直偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNum |  | 页码。 |

**Returns:**
页面显示区域的垂直偏移。

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

返回用于创建 PdfFileInfo 实例的密码类型。请参阅 {@code PasswordType} 中的可能取值。请注意，PDF 文档可以使用用户（或打开）密码和所有者（或权限、编辑）密码两者打开。

**Returns:**
PasswordType 元素 @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

获取 PDF 文档的版本信息。

**Returns:**
版本字符串。

### getProducer {#getProducer--}
```
public String getProducer()
```

获取 PDF 文档的 Producer 信息。

**Returns:**
字符串值

### getSubject {#getSubject--}
```
public String getSubject()
```

获取 PDF 文档的 Subject 信息。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取 PDF 文档的 Title 信息。

**Returns:**
字符串值

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

通过使用 {@code IsPdfFile}({@link #isPdfFile}) 属性来使用严格的验证规则。

**Returns:**
布尔值

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

如果当前输入文件是包含 PDF 文件集合的 "Portfolio" 文件，则返回 true。

**Returns:**
布尔值

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

如果需要密码来修改权限或文档安全属性，则返回 true。请注意，只有在 {@code PdfFileInfo} 构造函数中提供了有效密码时，才能读取此属性。如果 PasswordType 为 Inaccessible（表示提供了无效密码），读取此属性将因 {@code InvalidPasswordException} 而失败。

**Returns:**
布尔值

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

如果需要密码才能打开受密码保护的 PDF 文档，则返回 true。

**Returns:**
布尔值

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

检查 PDF 文档是否已加密。

**Returns:**
布尔值

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

检查源输入是否为有效的 PDF 文件。

**Returns:**
布尔值

### save {#save-java.io.OutputStream-}
将 PDF 文档保存到指定文件。

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
将更新后的 PDF 文档保存到指定流中。

### saveNewInfo {#saveNewInfo-java.lang.String-}
将更新后的 PDF 文档保存到指定文件中。

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
通过设置文件信息显式更改指定的属性，其他属性保持不变。

### setAuthor {#setAuthor-java.lang.String-}
设置 PDF 文档的 Author 信息。

### setCreationDate {#setCreationDate-java.lang.String-}
设置 PDF 文档的 CreationDate 信息。

### setCreator {#setCreator-java.lang.String-}
设置 PDF 文档的 Creator 信息。

### setHeader {#setHeader-java.util.Map-}
设置 PDF 文档的自定义信息。

### setInputFile {#setInputFile-java.lang.String-}
设置输入文件。

### setInputStream {#setInputStream-java.io.InputStream-}
设置输入流。

### setKeywords {#setKeywords-java.lang.String-}
设置 PDF 文档的 Keywords 信息。

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
设置 PDF 文档的自定义信息。

### setModDate {#setModDate-java.lang.String-}
设置 PDF 文档的 ModDate 日期信息。

### setSubject {#setSubject-java.lang.String-}
设置 PDF 文档的 Subject 信息。

### setTitle {#setTitle-java.lang.String-}
设置 PDF 文档的 Title 信息。

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

通过使用 {@code IsPdfFile}({@link #isPdfFile}) 属性来使用严格的验证规则。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
