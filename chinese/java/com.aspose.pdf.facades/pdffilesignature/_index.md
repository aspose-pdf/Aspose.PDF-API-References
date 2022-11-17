---
title: PdfFileSignature
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表一个用证书签署 pdf 文件的类。
type: docs
weight: 45
url: /zh/java/com.aspose.pdf.facades/pdffilesignature/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileSignature extends SaveableFacade
```

代表一个用证书签署 pdf 文件的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSignature()](#PdfFileSignature--) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature(String inputFile)](#PdfFileSignature-java.lang.String-) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature(String inputFile, String outputFile)](#PdfFileSignature-java.lang.String-java.lang.String-) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature(IDocument document)](#PdfFileSignature-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfFileSignature 对象。 |
| [PdfFileSignature(IDocument document, String outputFile)](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | 在文档的基础上初始化新的 PdfFileSignature 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | 绑定一个 Pdf 流进行编辑。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | 绑定一个 Pdf 文件进行编辑。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature)](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | 使用 MDP 签名验证文档。 |
| [certify(String sigName, DocMDPSignature docMdpSignature)](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | 使用放置在已提供的签名字段中的 MDP 签名来证明文档。 |
| [close()](#close--) | 关闭门面。 |
| [containsSignature()](#containsSignature--) | 检查 pdf 是否有数字签名。 |
| [containsUsageRights()](#containsUsageRights--) | 检查 pdf 是否具有使用权限。 |
| [coversWholeDocument(String signName)](#coversWholeDocument-java.lang.String-) | 检查签名是否覆盖整个文档。 |
| [dispose()](#dispose--) | 关闭门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractCertificate(String signName)](#extractCertificate-java.lang.String-) | 将签名的单个 X.509 证书提取为流。 |
| [extractImage(String signName)](#extractImage-java.lang.String-) | 提取签名的图像。 |
| [getAccessPermissions()](#getAccessPermissions--) | 按 MDP 签名类型返回认证文档的访问权限值。 |
| [getBlankSignNames()](#getBlankSignNames--) | 获取所有空签名字段的名称。 |
| [getClass()](#getClass--) |  |
| [getContactInfo(String signName)](#getContactInfo-java.lang.String-) | 获取签名的联系方式。 |
| [getDateTime(String signName)](#getDateTime-java.lang.String-) | 获取签名的日期时间。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getLocation(String signName)](#getLocation-java.lang.String-) | 获取签名的位置。 |
| [getReason(String signName)](#getReason-java.lang.String-) | 获取签名的原因。 |
| [getRevision(String signName)](#getRevision-java.lang.String-) | 获取签名的修订。 |
| [getSignNames()](#getSignNames--) | 获取所有非空签名的名称。 |
| [getSignNames(boolean onlyActive)](#getSignNames-boolean-) | 获取所有非空签名的名称。 |
| [getSignatureAppearance()](#getSignatureAppearance--) | 获取签名的图形外观。 |
| [getSignatureAppearanceStream()](#getSignatureAppearanceStream--) | 获取签名的图形外观。 |
| [getSignerName(String signName)](#getSignerName-java.lang.String-) | 获取签署 pdf 文档的个人或组织的名称。 |
| [getTotalRevision()](#getTotalRevision--) | 获取总修订版。 |
| [hashCode()](#hashCode--) |  |
| [isCertified()](#isCertified--) | 获取确定文档是否经过认证的标志。 |
| [isContainSignature()](#isContainSignature--) | 检查 pdf 是否有数字签名。 |
| [isCoversWholeDocument(String signName)](#isCoversWholeDocument-java.lang.String-) | 检查签名是否覆盖整个文档。 |
| [isLtvEnabled()](#isLtvEnabled--) | 获取 LTV 启用标志。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeSignature(String signName)](#removeSignature-java.lang.String-) | 根据签名的名称去除签名。 |
| [removeSignature(String signName, boolean removeField)](#removeSignature-java.lang.String-boolean-) | 根据签名的名称移除签名。 |
| [removeUsageRights()](#removeUsageRights--) | 删除使用权限条目。 |
| [save()](#save--) | 保存签名的 pdf 文件。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 将结果 PDF 保存到流中。 |
| [save(String outputFile)](#save-java.lang.String-) | 将结果 PDF 保存到文件。 |
| [setCertificate(String pfx, String pass)](#setCertificate-java.lang.String-java.lang.String-) | 为签名例程设置证书文件和密码。 |
| [setSignatureAppearance(String value)](#setSignatureAppearance-java.lang.String-) | 设置签名的图形外观。 |
| [setSignatureAppearanceStream(InputStream value)](#setSignatureAppearanceStream-java.io.InputStream-) | 设置签名的图形外观。 |
| [sign(int page, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用给定的类型签名签署文档。 |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | 在 pdf 文档上签名。 |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用给定的类型签名签署文档。 |
| [sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用放置在已提供的签名字段中的给定类型签名对文档进行签名。 |
| [sign(String SigName, Signature sig)](#sign-java.lang.String-com.aspose.pdf.Signature-) | 使用放置在已提供的签名字段中的给定类型签名对文档进行签名。 |
| [sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | 使用放置在已提供的签名字段中的给定类型签名对文档进行签名。 |
| [toString()](#toString--) |  |
| [verifySignature(String signName)](#verifySignature-java.lang.String-) | 检查签名的有效性。 |
| [verifySigned(String signName)](#verifySigned-java.lang.String-) | 检查签名的有效性。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSignature() {#PdfFileSignature--}
```
public PdfFileSignature()
```


PdfFileSignature 类的构造函数。

### PdfFileSignature(String inputFile) {#PdfFileSignature-java.lang.String-}
```
public PdfFileSignature(String inputFile)
```


PdfFileSignature 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 签名的输入文件。 |

### PdfFileSignature(String inputFile, String outputFile) {#PdfFileSignature-java.lang.String-java.lang.String-}
```
public PdfFileSignature(String inputFile, String outputFile)
```


PdfFileSignature 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 签名的输入文件。 |
| outputFile | java.lang.String | 输出文件。 |

### PdfFileSignature(IDocument document) {#PdfFileSignature-com.aspose.pdf.IDocument-}
```
public PdfFileSignature(IDocument document)
```


在文档的基础上初始化新的 PdfFileSignature 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### PdfFileSignature(IDocument document, String outputFile) {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSignature(IDocument document, String outputFile)
```


在文档的基础上初始化新的 PdfFileSignature 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputFile | java.lang.String | 输出文件。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


绑定一个 Pdf 流进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要编辑的 pdf 流。 |

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

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


绑定一个 Pdf 文件进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 要编辑的 pdf 文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature) {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
```
public void certify(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```


使用 MDP 签名验证文档。签名原因、联系人和位置等数据必须由签名对象sig 的相应属性提供。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 签名的页面。 |
| SigReason | java.lang.String | 签名的原因。 |
| SigContact | java.lang.String | 签名联系方式。 |
| SigLocation | java.lang.String | 签名的位置。 |
| visible | boolean | 签名的可见性。 |
| annotRect | java.awt.Rectangle | 签名的矩形。 |
| docMdpSignature | [DocMDPSignature](../../com.aspose.pdf/docmdpsignature) | 签名的文档 MDP 类型。 |

### certify(String sigName, DocMDPSignature docMdpSignature) {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
```
public final void certify(String sigName, DocMDPSignature docMdpSignature)
```


使用放置在已提供的签名字段中的 MDP 签名来证明文档。签名前签名字段必须为空，即字段不能包含签名字典。因此pdf文档已经有签名域，你不应该提供盖章签名的地方，相应的页面和矩形取自通过签名名称找到的签名域（见sigName参数）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sigName | java.lang.String | 签名域的名称。 |
| docMdpSignature | [DocMDPSignature](../../com.aspose.pdf/docmdpsignature) | 签名的类型，可以是，和    |

### close() {#close--}
```
public void close()
```


关闭门面。

### containsSignature() {#containsSignature--}
```
public boolean containsSignature()
```


检查 pdf 是否有数字签名。

**退货：**
boolean - 返回 bool 类型的结果。
### containsUsageRights() {#containsUsageRights--}
```
public boolean containsUsageRights()
```


检查 pdf 是否具有使用权限。

**退货：**
boolean - 返回 bool 类型的结果。
### coversWholeDocument(String signName) {#coversWholeDocument-java.lang.String-}
```
public boolean coversWholeDocument(String signName)
```


检查签名是否覆盖整个文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
boolean - 返回 bool 类型的结果。
### dispose() {#dispose--}
```
public void dispose()
```


关闭门面。此方法已过时，请改用 close() 。

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
### extractCertificate(String signName) {#extractCertificate-java.lang.String-}
```
public InputStream extractCertificate(String signName)
```


将签名的单个 X.509 证书提取为流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.io.InputStream - 如果找到证书则返回 X.509 单一证书；否则为空。
### extractImage(String signName) {#extractImage-java.lang.String-}
```
public InputStream extractImage(String signName)
```


提取签名的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.io.InputStream - 如果成功找到图像则返回流对象；否则为空。
### getAccessPermissions() {#getAccessPermissions--}
```
public int getAccessPermissions()
```


按 MDP 签名类型返回认证文档的访问权限值。

**退货：**
int - 如果文档正在被认证，则返回访问权限值；否则，被抛出。
### getBlankSignNames() {#getBlankSignNames--}
```
public List<String> getBlankSignNames()
```


获取所有空签名字段的名称。

**退货：**
java.util.List<java.lang.String> - 返回一个数组列表。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContactInfo(String signName) {#getContactInfo-java.lang.String-}
```
public String getContactInfo(String signName)
```


获取签名的联系方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.lang.String - 返回 String 类型的结果。
### getDateTime(String signName) {#getDateTime-java.lang.String-}
```
public Date getDateTime(String signName)
```


获取签名的日期时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
[Date](../../java.util/date) - 返回日期时间类型的结果。
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getLocation(String signName) {#getLocation-java.lang.String-}
```
public String getLocation(String signName)
```


获取签名的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.lang.String - 返回 String 类型的结果。
### getReason(String signName) {#getReason-java.lang.String-}
```
public String getReason(String signName)
```


获取签名的原因。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.lang.String - 返回 String 类型的结果。
### getRevision(String signName) {#getRevision-java.lang.String-}
```
public int getRevision(String signName)
```


获取签名的修订。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
int - 返回签名修订号。
### getSignNames() {#getSignNames--}
```
public final List<String> getSignNames()
```


获取所有非空签名的名称。

--------------------

**退货：**
java.util.List<java.lang.String> - 返回一个数组列表。
### getSignNames(boolean onlyActive) {#getSignNames-boolean-}
```
public List<String> getSignNames(boolean onlyActive)
```


获取所有非空签名的名称。

--------------------

```
String inFile=TestPath + "example1.pdf";
  PdfFileSignature pdfSign=new PdfFileSignature();
  pdfSign.bindPdf(inFile);
  ArrayList names=pdfSign.getSignNames(true);
 for(int i=0;i<names.Count;i++)
 {
   System.out.println("signature name:"+(String)names[i]);
   System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i]));
   System.out.println("revision:"+pdfSign.GetRevision((String)names[i]));
   System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i]));
   System.out.println("reason:"+pdfSign.GetReason((String)names[i]));
   System.out.println("location:"+pdfSign.GetLocation((String)names[i]));
   System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i]));
  }
  System.out.println("totalvision:"+pdfSign.GetTotalRevision());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| onlyActive | boolean | 布尔值，如果为真，则只返回有效签名；否则，返回所有签名。 |

**退货：**
java.util.List<java.lang.String> - 返回一个数组列表。
### getSignatureAppearance() {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```


获取签名的图形外观。属性值表示图像文件名。

**退货：**
java.lang.String - 字符串值
### getSignatureAppearanceStream() {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```


获取签名的图形外观。属性值表示图像流。

**退货：**
java.io.InputStream - InputStream 元素
### getSignerName(String signName) {#getSignerName-java.lang.String-}
```
public String getSignerName(String signName)
```


获取签署 pdf 文档的个人或组织的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
java.lang.String - 返回签名者姓名的结果。
### getTotalRevision() {#getTotalRevision--}
```
public int getTotalRevision()
```


获取总修订版。

**退货：**
int - 返回签名修订的总数。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCertified() {#isCertified--}
```
public boolean isCertified()
```


获取确定文档是否经过认证的标志。

**退货：**
boolean - 布尔值
### isContainSignature() {#isContainSignature--}
```
public boolean isContainSignature()
```


检查 pdf 是否有数字签名。

**退货：**
boolean - 返回 bool 类型的结果。
### isCoversWholeDocument(String signName) {#isCoversWholeDocument-java.lang.String-}
```
public boolean isCoversWholeDocument(String signName)
```


检查签名是否覆盖整个文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
boolean - 返回 bool 类型的结果。
### isLtvEnabled() {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```


获取 LTV 启用标志。

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




### removeSignature(String signName) {#removeSignature-java.lang.String-}
```
public void removeSignature(String signName)
```


根据签名的名称去除签名。

--------------------

```
String inFile = TestPath + "example1.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.bindPdf(inFile);
 List names = pdfSign.getSignNames();
 for(int i = 0; i < names.size(); i++)
 {
    pdfSign.removeSignature((String)names.get(i));
 }
 pdfSign.save(TestPath + "signed_removed.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

### removeSignature(String signName, boolean removeField) {#removeSignature-java.lang.String-boolean-}
```
public void removeSignature(String signName, boolean removeField)
```


根据签名的名称移除签名。

--------------------

```
String inFile = TestPath + "example1.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.BindPdf(inFile);
 List names = pdfSign.getSignNames();
 for(int i = 0; i < names.size(); i++)
 {
    pdfSign.removeSignature((String)names.get(i), false);
 }
 pdfSign.save(TestPath + "signed_removed.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |
| removeField | boolean | 如果设置为 true，则从文档中删除签名和字段；否则，仅签名。 |

### removeUsageRights() {#removeUsageRights--}
```
public void removeUsageRights()
```


删除使用权限条目。

### save() {#save--}
```
public void save()
```


保存签名的 pdf 文件。必须在相应的 PdfFileSignature 构造函数的帮助下之前提供输出文件名。

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


将结果 PDF 保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出pdf流 |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


将结果 PDF 保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 输出pdf文件 |

### setCertificate(String pfx, String pass) {#setCertificate-java.lang.String-java.lang.String-}
```
public void setCertificate(String pfx, String pass)
```


为签名例程设置证书文件和密码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pfx | java.lang.String |  PKCS\#12 证书文件。 |
| pass | java.lang.String | 用于访问证书私钥的密码。 |

### setSignatureAppearance(String value) {#setSignatureAppearance-java.lang.String-}
```
public void setSignatureAppearance(String value)
```


设置签名的图形外观。属性值表示图像文件名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setSignatureAppearanceStream(InputStream value) {#setSignatureAppearanceStream-java.io.InputStream-}
```
public void setSignatureAppearanceStream(InputStream value)
```


设置签名的图形外观。属性值表示图像流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流元素 |

### sign(int page, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, boolean visible, Rectangle annotRect, Signature sig)
```


使用给定的类型签名签署文档。

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 sig.setReason ( "Some reason");
 sig.setContact ( "Smith");
 sig.setLocation ( "New York");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 Rectangle rect = new Rectangle(100, 100, 200, 100);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign(2, true, rect, sig);
 pdfSign.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 签名的页码。 |
| visible | boolean | 签名的可见性。 |
| annotRect | java.awt.Rectangle | 签名的矩形。 |
| sig | [Signature](../../com.aspose.pdf/signature) | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。签名原因、联系人和位置等数据必须已经存在于此对象中（请参阅相应的属性）。 |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)
```


在 pdf 文档上签名。

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature();
 pdfSign.bindPdf(inFile);
 Rectangle rect = new Rectangle(100, 100, 200, 200);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.setCertificate("certificate.pfx", "password");
 pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect);
 pdfSign.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 签名的页码。 |
| SigReason | java.lang.String | 签名的原因。 |
| SigContact | java.lang.String | 签名联系方式。 |
| SigLocation | java.lang.String | 签名的位置。 |
| visible | boolean | 签名的可见性。 |
| annotRect | java.awt.Rectangle | 签名的矩形。 |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


使用给定的类型签名签署文档。

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 Rectangle rect = new Rectangle(100, 100, 200, 100);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect, new PKCS1("certificate.pfx", "password"));
 pdfSign.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 签名的页码。 |
| SigReason | java.lang.String | 签名的原因。 |
| SigContact | java.lang.String | 签名联系方式。 |
| SigLocation | java.lang.String | 签名的位置。 |
| visible | boolean | 签名的可见性。 |
| annotRect | java.awt.Rectangle | 签名的矩形。 |
| sig | [Signature](../../com.aspose.pdf/signature) | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

### sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


使用放置在已提供的签名字段中的给定类型签名对文档进行签名。签名前pdf文档应该已经有签名域，相应的页面和矩形取自签名名找到的签名域（见SigName参数）。

--------------------

```
String inFile = TestPath + "blankWithSignature.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS7 sig = new PKCS7("certificate.pfx", "password");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile);
 Rectangle rect = new Rectangle(100, 100, 100, 100);
 pdfSign.setSignatureAppearance( TestPath + "butterfly.jpg");
 pdfSign.sign(1, "Signature1", "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig);
 pdfSign.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 签名的页码。 |
| SigName | java.lang.String | 签名域的名称。 |
| SigReason | java.lang.String | 签名的原因。 |
| SigContact | java.lang.String | 签名联系方式。 |
| SigLocation | java.lang.String | 签名的位置。 |
| visible | boolean | 签名的可见性。 |
| annotRect | java.awt.Rectangle | 签名的矩形。 |
| sig | [Signature](../../com.aspose.pdf/signature) | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

### sign(String SigName, Signature sig) {#sign-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, Signature sig)
```


使用放置在已提供的签名字段中的给定类型签名对文档进行签名。签名前签名字段必须为空，即字段不能包含签名字典。因此pdf文档已经有签名域，你不应该提供盖章签名的地方，相应的页面和矩形取自通过签名名称找到的签名域（见SigName参数）。签名原因、联系人和位置等数据必须由签名对象sig 的相应属性提供。

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 sig.setReason ( "Some reason");
 sig.setContact ( "Smith");
 sig.setLocation ( "New York");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign("Signature1", sig);
 pdfSign.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| SigName | java.lang.String | 签名域的名称。 |
| sig | [Signature](../../com.aspose.pdf/signature) | 签名的类型，可以是 PKCS1（Pkcs1Signature 对象）、PKCS7 和 PKCS7 detached（Pkcs7Signature 对象） |

### sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig) {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)
```


使用放置在已提供的签名字段中的给定类型签名对文档进行签名。签名前签名字段必须为空，即字段不能包含签名字典。因此pdf文档已经有签名域，你不应该提供盖章签名的地方，相应的页面和矩形取自通过签名名称找到的签名域（见SigName参数）。

--------------------

```
String inFile = TestPath + "example1.pdf";
 String outFile = TestPath + "signature.pdf";
 PKCS1 sig = new PKCS1("certificate.pfx", "password");
 PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
 pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
 pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig);
 pdfSign.save();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| SigName | java.lang.String | 签名域的名称。 |
| SigReason | java.lang.String | 签名的原因。 |
| SigContact | java.lang.String | 签名联系方式。 |
| SigLocation | java.lang.String | 签名的位置。 |
| sig | [Signature](../../com.aspose.pdf/signature) | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### verifySignature(String signName) {#verifySignature-java.lang.String-}
```
public boolean verifySignature(String signName)
```


检查签名的有效性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
boolean - 返回 bool 类型的结果。
### verifySigned(String signName) {#verifySigned-java.lang.String-}
```
public boolean verifySigned(String signName)
```


检查签名的有效性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signName | java.lang.String | 署名名称。 |

**退货：**
boolean - 返回 bool 类型的结果。
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
