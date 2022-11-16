---
title: PdfFileInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示用于访问 PDF 文档的元信息的类。
type: docs
weight: 41
url: /zh/java/com.aspose.pdf.facades/pdffileinfo/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileInfo extends SaveableFacade
```

表示用于访问 PDF 文档的元信息的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileInfo()](#PdfFileInfo--) | 使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo(InputStream inputStream)](#PdfFileInfo-java.io.InputStream-) | 初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo(InputStream inputStream, String password)](#PdfFileInfo-java.io.InputStream-java.lang.String-) | 初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo(String inputFile)](#PdfFileInfo-java.lang.String-) | 初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo(String inputFile, String password)](#PdfFileInfo-java.lang.String-java.lang.String-) | 初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo(IDocument document)](#PdfFileInfo-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfFileInfo 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [clearInfo()](#clearInfo--) | 清除 PDF 文档的所有元信息。 |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [dispose()](#dispose--) | 关闭此实例使用的所有资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthor()](#getAuthor--) | 获取PDF文档的作者信息。 |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | 获取PDF文档的创建日期信息。 |
| [getCreator()](#getCreator--) | 获取PDF文档的创建者信息。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getDocumentPrivilege()](#getDocumentPrivilege--) | 获取PDF文档权限设置。 |
| [getHeader()](#getHeader--) | 获取PDF文档的自定义信息。 |
| [getInputFile()](#getInputFile--) | 获取输入文件。 |
| [getInputStream()](#getInputStream--) | 获取输入流。 |
| [getKeywords()](#getKeywords--) | 获取PDF文档的关键字信息。 |
| [getMetaInfo(String name)](#getMetaInfo-java.lang.String-) | 获取带有属性名称的 PDF 文档的自定义信息。 |
| [getModDate()](#getModDate--) | 获取 PDF 文档的 ModDate 日期信息。 |
| [getNumberOfPages()](#getNumberOfPages--) | 获取文档页数。 |
| [getPageHeight(int pageNum)](#getPageHeight-int-) | 获取指定页面的高度。 |
| [getPageRotation(int pageNum)](#getPageRotation-int-) | 获取指定页面的旋转。 |
| [getPageWidth(int pageNum)](#getPageWidth-int-) | 获取指定页面的宽度。 |
| [getPageXOffset(int pageNum)](#getPageXOffset-int-) | 获取指定页面显示区域的水平偏移量。 |
| [getPageYOffset(int pageNum)](#getPageYOffset-int-) | 获取指定页面显示区域的垂直偏移量。 |
| [getPasswordType()](#getPasswordType--) | 返回为创建 PdfFileInfo 实例而传递的密码类型。 |
| [getPdfVersion()](#getPdfVersion--) | 获取 PDF 文档的版本信息。 |
| [getProducer()](#getProducer--) | 获取PDF文档的制作者信息。 |
| [getSubject()](#getSubject--) | 获取 PDF 文档的主题信息。 |
| [getTitle()](#getTitle--) | 获取PDF文档的标题信息。 |
| [getUseStrictValidation()](#getUseStrictValidation--) | 通过使用 IsPdfFile (\#isPdfFile.isPdfFile) 属性。 |
| [hasCollection()](#hasCollection--) | 如果当前输入文件是包含 PDF 文件集合的“Portfolio”文件，则返回 true。 |
| [hasEditPassword()](#hasEditPassword--) | 如果需要密码来修改权限或记录安全属性，则返回 true。 |
| [hasOpenPassword()](#hasOpenPassword--) | 如果需要密码才能打开受密码保护的 pdf 文档，则返回 true。 |
| [hashCode()](#hashCode--) |  |
| [isEncrypted()](#isEncrypted--) | 检查 PDF 文档是否加密。 |
| [isPdfFile()](#isPdfFile--) | 检查源输入是否为有效的 PDF 文件。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定文件。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [saveNewInfo(OutputStream outputStream)](#saveNewInfo-java.io.OutputStream-) | 将更新的 PDF 文档保存到指定的流中。 |
| [saveNewInfo(String outputFile)](#saveNewInfo-java.lang.String-) | 将更新的 PDF 文档保存到指定的文件中。 |
| [saveNewInfoWithXmp(String outputFileName)](#saveNewInfoWithXmp-java.lang.String-) | 更改通过设置文件信息明确指定的属性，其他属性保持不变。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 设置PDF文档的作者信息。 |
| [setCreationDate(String value)](#setCreationDate-java.lang.String-) | 设置 PDF 文档的创建日期信息。 |
| [setCreator(String value)](#setCreator-java.lang.String-) | 设置PDF文档的创建者信息。 |
| [setHeader(Map<String,String> value)](#setHeader-java.util.Map-java.lang.String-java.lang.String--) | 设置PDF文档的自定义信息。 |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | 设置输入文件。 |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 设置PDF文档的关键字信息。 |
| [setMetaInfo(String name, String value)](#setMetaInfo-java.lang.String-java.lang.String-) | 设置PDF文档的自定义信息。 |
| [setModDate(String value)](#setModDate-java.lang.String-) | 设置PDF文档的ModDate日期信息。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 设置 PDF 文档的主题信息。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置PDF文档的标题信息。 |
| [setUseStrictValidation(boolean value)](#setUseStrictValidation-boolean-) | 通过使用 IsPdfFile (\#isPdfFile.isPdfFile) 属性。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileInfo() {#PdfFileInfo--}
```
public PdfFileInfo()
```


使用默认值初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

### PdfFileInfo(InputStream inputStream) {#PdfFileInfo-java.io.InputStream-}
```
public PdfFileInfo(InputStream inputStream)
```


初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 放置输入文件的流。 |

### PdfFileInfo(InputStream inputStream, String password) {#PdfFileInfo-java.io.InputStream-java.lang.String-}
```
public PdfFileInfo(InputStream inputStream, String password)
```


初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 放置输入文件的流。 |
| password | java.lang.String | 访问文件的密码。 |

### PdfFileInfo(String inputFile) {#PdfFileInfo-java.lang.String-}
```
public PdfFileInfo(String inputFile)
```


初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 包含输入文件的文件的名称。 |

### PdfFileInfo(String inputFile, String password) {#PdfFileInfo-java.lang.String-java.lang.String-}
```
public PdfFileInfo(String inputFile, String password)
```


初始化 com.aspose.pdf.facades.PdfFileInfo 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 包含输入文件的文件的名称。 |
| password | java.lang.String | 访问文件的密码。 |

### PdfFileInfo(IDocument document) {#PdfFileInfo-com.aspose.pdf.IDocument-}
```
public PdfFileInfo(IDocument document)
```


在文档的基础上初始化新的 PdfFileInfo 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |
| password | java.lang.String | PDF文档的密码。 |

### clearInfo() {#clearInfo--}
```
public void clearInfo()
```


清除 PDF 文档的所有元信息。

### close() {#close--}
```
public void close()
```


关闭此文档使用的所有资源。

### dispose() {#dispose--}
```
public void dispose()
```


关闭此实例使用的所有资源。

此方法已过时，请改用 close() 。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取PDF文档的作者信息。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public String getCreationDate()
```


获取PDF文档的创建日期信息。

**退货：**
java.lang.String - 字符串值
### getCreator() {#getCreator--}
```
public String getCreator()
```


获取PDF文档的创建者信息。

**退货：**
java.lang.String - 字符串值
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getDocumentPrivilege() {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```


获取PDF文档权限设置。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - PDF文档权限设置。
### getHeader() {#getHeader--}
```
public Map<String,String> getHeader()
```


获取PDF文档的自定义信息。

**退货：**
java.util.Map<java.lang.String,java.lang.String> - 地图对象
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


获取输入文件。

**退货：**
java.lang.String - 字符串值
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


获取输入流。

**退货：**
java.io.InputStream - InputStream 对象
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


获取PDF文档的关键字信息。

**退货：**
java.lang.String - 字符串值
### getMetaInfo(String name) {#getMetaInfo-java.lang.String-}
```
public String getMetaInfo(String name)
```


获取带有属性名称的 PDF 文档的自定义信息。如果没有匹配名称的属性，它将返回一个空字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 自定义元属性键。 |

**退货：**
java.lang.String - 自定义元属性值。
### getModDate() {#getModDate--}
```
public String getModDate()
```


获取 PDF 文档的 ModDate 日期信息。

**退货：**
java.lang.String - 字符串值
### getNumberOfPages() {#getNumberOfPages--}
```
public int getNumberOfPages()
```


获取文档页数。

**退货：**
int - 整数值
### getPageHeight(int pageNum) {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```


获取指定页面的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNum | int | 页码。 |

**退货：**
float - 页面的高度。
### getPageRotation(int pageNum) {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```


获取指定页面的旋转。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNum | int | 页码。 |

**退货：**
int - 页面的旋转。该值可能是 0,90,180,270。
### getPageWidth(int pageNum) {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```


获取指定页面的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNum | int | 页码。 |

**退货：**
float - 页面的宽度。
### getPageXOffset(int pageNum) {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```


获取指定页面显示区域的水平偏移量。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNum | int | 页码。 |

**退货：**
float - 距页面左侧的水平偏移量。
### getPageYOffset(int pageNum) {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```


获取指定页面显示区域的垂直偏移量。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNum | int | 页码。 |

**退货：**
float - 页面显示区域的垂直偏移量。
### getPasswordType() {#getPasswordType--}
```
public int getPasswordType()
```


返回为创建 PdfFileInfo 实例而传递的密码类型。请参阅 PasswordType 中的可能值。请注意，可以使用用户（或打开）密码和所有者（或权限、编辑）密码打开 pdf 文档。

**退货：**
int - 密码类型元素
### getPdfVersion() {#getPdfVersion--}
```
public String getPdfVersion()
```


获取 PDF 文档的版本信息。

**退货：**
java.lang.String - 版本字符串。
### getProducer() {#getProducer--}
```
public String getProducer()
```


获取PDF文档的制作者信息。

**退货：**
java.lang.String - 字符串值
### getSubject() {#getSubject--}
```
public String getSubject()
```


获取 PDF 文档的主题信息。

**退货：**
java.lang.String - 字符串值
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取PDF文档的标题信息。

**退货：**
java.lang.String - 字符串值
### getUseStrictValidation() {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```


通过使用 IsPdfFile (\#isPdfFile.isPdfFile) 属性。

**退货：**
boolean - 布尔值
### hasCollection() {#hasCollection--}
```
public boolean hasCollection()
```


如果当前输入文件是包含 PDF 文件集合的“Portfolio”文件，则返回 true。

**退货：**
boolean - 布尔值
### hasEditPassword() {#hasEditPassword--}
```
public boolean hasEditPassword()
```


如果需要密码来修改权限或记录安全属性，则返回 true。请注意，只有在 PdfFileInfo 构造函数中提供了有效密码时，才能读取此属性。如果 PasswordType 是 Inaccessible（意味着提供了无效密码），读取此属性将失败并出现 InvalidPasswordException 。

**退货：**
boolean - 布尔值
### hasOpenPassword() {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```


如果需要密码才能打开受密码保护的 pdf 文档，则返回 true。

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


检查 PDF 文档是否加密。

**退货：**
boolean - 布尔值
### isPdfFile() {#isPdfFile--}
```
public boolean isPdfFile()
```


检查源输入是否为有效的 PDF 文件。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 目标文件。 |

### saveNewInfo(OutputStream outputStream) {#saveNewInfo-java.io.OutputStream-}
```
public boolean saveNewInfo(OutputStream outputStream)
```


将更新的 PDF 文档保存到指定的流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出流。 |

**退货：**
boolean - 如果成功则为真，否则为假。
### saveNewInfo(String outputFile) {#saveNewInfo-java.lang.String-}
```
public boolean saveNewInfo(String outputFile)
```


将更新的 PDF 文档保存到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 输出文件。 |

**退货：**
boolean - 如果成功则为真，否则为假。
### saveNewInfoWithXmp(String outputFileName) {#saveNewInfoWithXmp-java.lang.String-}
```
public boolean saveNewInfoWithXmp(String outputFileName)
```


更改通过设置文件信息明确指定的属性，其他属性保持不变。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 输出文件。 |

**退货：**
boolean - True 表示成功，否则为 false。
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


设置PDF文档的作者信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCreationDate(String value) {#setCreationDate-java.lang.String-}
```
public void setCreationDate(String value)
```


设置 PDF 文档的创建日期信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


设置PDF文档的创建者信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setHeader(Map<String,String> value) {#setHeader-java.util.Map-java.lang.String-java.lang.String--}
```
public void setHeader(Map<String,String> value)
```


设置PDF文档的自定义信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Map<java.lang.String,java.lang.String> |  地图对象 |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


设置输入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


设置输入流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


设置PDF文档的关键字信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setMetaInfo(String name, String value) {#setMetaInfo-java.lang.String-java.lang.String-}
```
public void setMetaInfo(String name, String value)
```


设置PDF文档的自定义信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 自定义元属性键。 |
| value | java.lang.String | 自定义元属性值。 |

### setModDate(String value) {#setModDate-java.lang.String-}
```
public void setModDate(String value)
```


设置PDF文档的ModDate日期信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


设置 PDF 文档的主题信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置PDF文档的标题信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setUseStrictValidation(boolean value) {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```


通过使用 IsPdfFile (\#isPdfFile.isPdfFile) 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
