---
title: FileSpecification
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示嵌入文件的类。
type: docs
weight: 118
url: /zh/java/com.aspose.pdf/filespecification/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class FileSpecification implements System.IDisposable, Closeable
```

表示嵌入文件的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileSpecification(IPdfPrimitive specification)](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | 档案规格 |
| [FileSpecification(String file)](#FileSpecification-java.lang.String-) | FileSpecification 的构造函数 |
| [FileSpecification(System.IO.Stream stream, String name)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | 文件规范的构造函数。 |
| [FileSpecification(InputStream stream, String name)](#FileSpecification-java.io.InputStream-java.lang.String-) | 文件规范的构造函数。 |
| [FileSpecification(String file, String description)](#FileSpecification-java.lang.String-java.lang.String-) | FileSpecification 的构造函数。 |
| [FileSpecification(System.IO.Stream stream, String name, String description)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | FileSpecification 的构造函数。 |
| [FileSpecification(InputStream stream, String name, String description)](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | FileSpecification 的构造函数。 |
| [FileSpecification(String fileName, Annotation annot)](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | FileSpecification 的构造函数。 |
| [FileSpecification()](#FileSpecification--) | 创建新的空文件规范。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 处理内容物。 |
| [dispose()](#dispose--) | 处理内容物。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFRelationship()](#getAFRelationship--) | 关联文件关系。 |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | 获取内容文件。 |
| [getContentsInternal()](#getContentsInternal--) | 获取内容文件。 |
| [getDescription()](#getDescription--) | 获取与文件规范关联的文本。 |
| [getEncoding()](#getEncoding--) | 获取编码格式。 |
| [getEncryptedPayload()](#getEncryptedPayload--) | 获取加密的负载。 |
| [getEngineDict()](#getEngineDict--) | 包含有关文件信息的 Pdf 字典。 |
| [getEngineObj()](#getEngineObj--) | 仅限内部 |
| [getFileSystem()](#getFileSystem--) | 获取文件系统的名称。 |
| [getMIMEType()](#getMIMEType--) | 获取嵌入文件的子类型 |
| [getName()](#getName--) | 获取文件规范名称。 |
| [getParams()](#getParams--) | 获取文件参数。 |
| [getStreamContents()](#getStreamContents--) | 获取文件内容作为流。 |
| [getUnicodeName()](#getUnicodeName--) | 获取文件规范 unicode 名称。 |
| [getValue(String key)](#getValue-java.lang.String-) | 获取特定于应用程序的参数。 |
| [hashCode()](#hashCode--) |  |
| [isIncludeContents()](#isIncludeContents--) | 如果为真，文件的内容将包含在文件规范中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAFRelationship(AFRelationship value)](#setAFRelationship-com.aspose.pdf.AFRelationship-) | 关联文件关系。 |
| [setContents(byte[] value)](#setContents-byte---) | 设置内容文件。 |
| [setContents(InputStream value)](#setContents-java.io.InputStream-) | 设置内容文件。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 设置与文件规范关联的文本。 |
| [setEncoding(int value)](#setEncoding-int-) | 设置编码格式。 |
| [setFileSystem(String value)](#setFileSystem-java.lang.String-) | 设置文件系统的名称。 |
| [setIncludeContents(boolean value)](#setIncludeContents-boolean-) | 如果为真，文件的内容将包含在文件规范中。 |
| [setMIMEType(String value)](#setMIMEType-java.lang.String-) | 设置 MIME 类型。 |
| [setName(String value)](#setName-java.lang.String-) | 设置文件规范名称。 |
| [setParams(FileParams value)](#setParams-com.aspose.pdf.FileParams-) | 设置文件参数。 |
| [setUnicodeName(String value)](#setUnicodeName-java.lang.String-) | 设置文件规范 unicode 名称。 |
| [setValue(String key, String value)](#setValue-java.lang.String-java.lang.String-) | 设置特定于应用程序的参数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSpecification(IPdfPrimitive specification) {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public FileSpecification(IPdfPrimitive specification)
```


档案规格

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| specification | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPDF原始对象 |

### FileSpecification(String file) {#FileSpecification-java.lang.String-}
```
public FileSpecification(String file)
```


FileSpecification 的构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件路径。 |

### FileSpecification(System.IO.Stream stream, String name) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name)
```


文件规范的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 包含数据文件的流。 |
| name | java.lang.String | 文件规范。 |

### FileSpecification(InputStream stream, String name) {#FileSpecification-java.io.InputStream-java.lang.String-}
```
public FileSpecification(InputStream stream, String name)
```


文件规范的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含数据文件的流。 |
| name | java.lang.String | 文件规范。 |

### FileSpecification(String file, String description) {#FileSpecification-java.lang.String-java.lang.String-}
```
public FileSpecification(String file, String description)
```


FileSpecification 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件路径。 |
| description | java.lang.String | 文件描述。 |

### FileSpecification(System.IO.Stream stream, String name, String description) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name, String description)
```


FileSpecification 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 要在文档中使用的流。 |
| name | java.lang.String | 文件规范字符串。 |
| description | java.lang.String | 文件描述。 |

### FileSpecification(InputStream stream, String name, String description) {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
```
public FileSpecification(InputStream stream, String name, String description)
```


FileSpecification 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要在文档中使用的流。 |
| name | java.lang.String | 文件规范字符串。 |
| description | java.lang.String | 文件描述。 |

### FileSpecification(String fileName, Annotation annot) {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
```
public FileSpecification(String fileName, Annotation annot)
```


FileSpecification 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 字符串对象 |
| annot | [Annotation](../../com.aspose.pdf/annotation) | 注释对象 |

### FileSpecification() {#FileSpecification--}
```
public FileSpecification()
```


创建新的空文件规范。

### close() {#close--}
```
public void close()
```


处理内容物。

### dispose() {#dispose--}
```
public void dispose()
```


处理内容物。

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
### getAFRelationship() {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```


关联文件关系。

**退货：**
[AFRelationship](../../com.aspose.pdf/afrelationship) - AFRelationship元素
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContents() {#getContents--}
```
public InputStream getContents()
```


获取内容文件。

**退货：**
java.io.InputStream - InputStream 对象
### getContentsInternal() {#getContentsInternal--}
```
public System.IO.Stream getContentsInternal()
```


获取内容文件。

**退货：**
com.aspose.ms.System.IO.Stream - 流对象
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取与文件规范关联的文本。

**退货：**
java.lang.String - 字符串值
### getEncoding() {#getEncoding--}
```
public int getEncoding()
```


获取编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。

**退货：**
int - 整数值
### getEncryptedPayload() {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```


获取加密的负载。

**退货：**
[EncryptedPayload](../../com.aspose.pdf/encryptedpayload) - EncryptedPayload 实例
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


包含有关文件信息的 Pdf 字典。仅限内部

**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) IPdfDictionary 对象
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


仅限内部

**退货：**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) IPdfObject 对象
### getFileSystem() {#getFileSystem--}
```
public String getFileSystem()
```


获取文件系统的名称。

**退货：**
java.lang.String - 字符串值
### getMIMEType() {#getMIMEType--}
```
public String getMIMEType()
```


获取嵌入文件的子类型

**退货：**
java.lang.String - 字符串值
### getName() {#getName--}
```
public String getName()
```


获取文件规范名称。

**退货：**
java.lang.String - 字符串值
### getParams() {#getParams--}
```
public FileParams getParams()
```


获取文件参数。

**退货：**
[FileParams](../../com.aspose.pdf/fileparams) 文件参数对象
### getStreamContents() {#getStreamContents--}
```
public InputStream getStreamContents()
```


获取文件内容作为流。内容不会加载到内存中，这样可以减少内存使用量。但是这个流不支持定位和长度属性。如果您需要此功能，请改用 Contents 属性。

**退货：**
java.io.InputStream - InputStream 对象
### getUnicodeName() {#getUnicodeName--}
```
public String getUnicodeName()
```


获取文件规范 unicode 名称。

**退货：**
java.lang.String - 字符串值
### getValue(String key) {#getValue-java.lang.String-}
```
public final String getValue(String key)
```


获取特定于应用程序的参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 参数名称。 |

**退货：**
java.lang.String - 字符串值 - 如果找到参数；否则为空。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isIncludeContents() {#isIncludeContents--}
```
public boolean isIncludeContents()
```


如果为真，文件的内容将包含在文件规范中。

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




### setAFRelationship(AFRelationship value) {#setAFRelationship-com.aspose.pdf.AFRelationship-}
```
public final void setAFRelationship(AFRelationship value)
```


关联文件关系。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [AFRelationship](../../com.aspose.pdf/afrelationship) | AFR关系元素 |

### setContents(byte[] value) {#setContents-byte---}
```
public void setContents(byte[] value)
```


设置内容文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] | 字节数组 |

### setContents(InputStream value) {#setContents-java.io.InputStream-}
```
public void setContents(InputStream value)
```


设置内容文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


设置与文件规范关联的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setEncoding(int value) {#setEncoding-int-}
```
public void setEncoding(int value)
```


设置编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFileSystem(String value) {#setFileSystem-java.lang.String-}
```
public void setFileSystem(String value)
```


设置文件系统的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setIncludeContents(boolean value) {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```


如果为真，文件的内容将包含在文件规范中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMIMEType(String value) {#setMIMEType-java.lang.String-}
```
public void setMIMEType(String value)
```


设置 MIME 类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置文件规范名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setParams(FileParams value) {#setParams-com.aspose.pdf.FileParams-}
```
public void setParams(FileParams value)
```


设置文件参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileParams](../../com.aspose.pdf/fileparams) | 文件参数对象 |

### setUnicodeName(String value) {#setUnicodeName-java.lang.String-}
```
public void setUnicodeName(String value)
```


设置文件规范 unicode 名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setValue(String key, String value) {#setValue-java.lang.String-java.lang.String-}
```
public final void setValue(String key, String value)
```


设置特定于应用程序的参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 参数名称。 |
| value | java.lang.String | 新的参数值。 |

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
