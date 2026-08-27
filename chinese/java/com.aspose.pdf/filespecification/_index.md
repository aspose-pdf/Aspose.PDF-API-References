---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Aspose.PDF for Java API 参考"
description: "表示嵌入文件的类。"
type: docs
weight: 1510
url: /zh/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

表示嵌入文件的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileSpecification](#FileSpecification--) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-java.lang.String-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | 创建新的空文件规范。 |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | 创建新的空文件规范。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | 关联文件关系。 |
| [getCollectionItem](#getCollectionItem--) | 获取文件规范的集合项。 |
| [getContents](#getContents--) | 获取内容文件。 |
| [getContentsInternal](#getContentsInternal--) | 获取内容文件。 |
| [getDescription](#getDescription--) | 获取与文件规范关联的文本。 |
| [getEncoding](#getEncoding--) | 获取编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。 |
| [getEncryptedPayload](#getEncryptedPayload--) | 获取加密负载。 |
| [getEngineDict](#getEngineDict--) | 包含文件信息的 PDF 字典。仅内部使用 |
| [getEngineObj](#getEngineObj--) | 仅内部使用 |
| [getFileSystem](#getFileSystem--) | 获取文件系统的名称。 |
| [getMIMEType](#getMIMEType--) | 获取嵌入文件的子类型 |
| [getName](#getName--) | 获取文件规范名称。 |
| [getParams](#getParams--) | 获取文件参数。 |
| [getStreamContents](#getStreamContents--) | 获取文件内容作为流。内容不会加载到内存中，从而降低内存使用。但此流不支持定位和 Length 属性。如果需要这些功能，请改用 Contents 属性。 |
| [getUnicodeName](#getUnicodeName--) | 获取文件规范的 Unicode 名称。 |
| [getValue](#getValue-java.lang.String-) | 获取特定于应用程序的参数。 |
| [isIncludeContents](#isIncludeContents--) | 如果为 true，文件内容将包含在文件规范中。 |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | 关联文件关系。 |
| [setContents](#setContents-byte:A-) | 设置内容文件。 |
| [setContents](#setContents-java.io.InputStream-) | 设置内容文件。 |
| [setDescription](#setDescription-java.lang.String-) | 设置与文件规范关联的文本。 |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | 设置编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。 |
| [setFileSystem](#setFileSystem-java.lang.String-) | 设置文件系统的名称。 |
| [setIncludeContents](#setIncludeContents-boolean-) | 如果为 true，文件内容将包含在文件规范中。 |
| [setMIMEType](#setMIMEType-java.lang.String-) | 设置 MIME 类型。 |
| [setName](#setName-java.lang.String-) | 设置文件规范名称。 |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | 设置文件参数。 |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | 设置文件规范的 Unicode 名称。 |
| [setValue](#setValue-java.lang.String-java.lang.String-) | 设置特定于应用程序的参数。 |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

创建新的空文件规范。

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-java.lang.String-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
创建新的空文件规范。

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
创建新的空文件规范。

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

关联文件关系。

**Returns:**
AFRelationship 元素

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

获取文件规范的集合项。

**Returns:**
CollectionItem 实例

### getContents {#getContents--}
```
public InputStream getContents()
```

获取内容文件。

**Returns:**
InputStream 对象

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

获取内容文件。

**Returns:**
Stream 对象

### getDescription {#getDescription--}
```
public String getDescription()
```

获取与文件规范关联的文本。

**Returns:**
字符串值

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

获取编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。

**Returns:**
int 值 @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

获取加密负载。

**Returns:**
EncryptedPayload 实例

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

包含文件信息的 PDF 字典。仅内部使用

**Returns:**
IPdfDictionary 对象

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

仅内部使用

**Returns:**
IPdfObject 对象

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

获取文件系统的名称。

**Returns:**
字符串值

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

获取嵌入文件的子类型

**Returns:**
string 值

### getName {#getName--}
```
public String getName()
```

获取文件规范名称。

**Returns:**
字符串值

### getParams {#getParams--}
```
public FileParams getParams()
```

获取文件参数。

**Returns:**
FileParams 对象

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

获取文件内容作为流。内容不会加载到内存中，从而降低内存使用。但此流不支持定位和 Length 属性。如果需要这些功能，请改用 Contents 属性。

**Returns:**
InputStream 对象

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

获取文件规范的 Unicode 名称。

**Returns:**
字符串值

### getValue {#getValue-java.lang.String-}
获取特定于应用程序的参数。

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

如果为 true，文件内容将包含在文件规范中。

**Returns:**
布尔值

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
关联文件关系。

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

设置内容文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 字节数组 |

### setContents {#setContents-java.io.InputStream-}
设置内容文件。

### setDescription {#setDescription-java.lang.String-}
设置与文件规范关联的文本。

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
设置编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。

### setFileSystem {#setFileSystem-java.lang.String-}
设置文件系统的名称。

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

如果为 true，文件内容将包含在文件规范中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMIMEType {#setMIMEType-java.lang.String-}
设置 MIME 类型。

### setName {#setName-java.lang.String-}
设置文件规范名称。

### setParams {#setParams-com.aspose.pdf.FileParams-}
设置文件参数。

### setUnicodeName {#setUnicodeName-java.lang.String-}
设置文件规范的 Unicode 名称。

### setValue {#setValue-java.lang.String-java.lang.String-}
设置特定于应用程序的参数。
