---
title: FileSpecification
linktitle: FileSpecification
second_title: Aspose.PDF for Java API Reference
description: Class representing embedded file.
type: docs
weight: 1510
url: /java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Class representing embedded file.

## Constructors

| Constructor | Description |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Create new empty file specification. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Create new empty file specification. |

## Methods

| Method | Description |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Associated file Relationship. |
| [getCollectionItem](#getCollectionItem--) | Gets a collection item of the file specification. |
| [getContents](#getContents--) | Gets contents file. |
| [getContentsInternal](#getContentsInternal--) | Gets contents file. |
| [getDescription](#getDescription--) | Gets text associated with the file specification. |
| [getEncoding](#getEncoding--) | Gets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed. |
| [getEncryptedPayload](#getEncryptedPayload--) | Gets encrypted payload. |
| [getEngineDict](#getEngineDict--) | Pdf dictionary containing information about the file. Internal only |
| [getEngineObj](#getEngineObj--) | Internal only |
| [getFileSystem](#getFileSystem--) | Gets name of the file system. |
| [getMIMEType](#getMIMEType--) | Gets subtype of the embedded file |
| [getName](#getName--) | Gets file specification name. |
| [getParams](#getParams--) | Gets file parameters. |
| [getStreamContents](#getStreamContents--) | Gets contents of file as stream. Contents is not loaded into memory which allows to decrease memory usage. But this stream does not support positioning and Length property. If you need this features please use Contents property instead. |
| [getUnicodeName](#getUnicodeName--) | Gets file specification unicode name. |
| [getValue](#getValue-java.lang.String-) | Gets application-specific parameter. |
| [isIncludeContents](#isIncludeContents--) | If true, contents of the file will be included in the file specification. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Associated file Relationship. |
| [setContents](#setContents-byte:A-) | Sets contents file. |
| [setContents](#setContents-java.io.InputStream-) | Sets contents file. |
| [setDescription](#setDescription-java.lang.String-) | Sets text associated with the file specification. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Sets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Sets name of the file system. |
| [setIncludeContents](#setIncludeContents-boolean-) | If true, contents of the file will be included in the file specification. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Sets MIMEType. |
| [setName](#setName-java.lang.String-) | Sets file specification name. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Sets file parameters. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Sets file specification unicode name. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Sets application-specific parameter. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Create new empty file specification.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Create new empty file specification.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Create new empty file specification.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Create new empty file specification.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Create new empty file specification.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Create new empty file specification.

### FileSpecification {#FileSpecification-java.lang.String-}
Create new empty file specification.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Create new empty file specification.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Create new empty file specification.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Associated file Relationship.

**Returns:**
AFRelationship element

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Gets a collection item of the file specification.

**Returns:**
CollectionItem instance

### getContents {#getContents--}
```
public InputStream getContents()
```

Gets contents file.

**Returns:**
InputStream object

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Gets contents file.

**Returns:**
Stream object

### getDescription {#getDescription--}
```
public String getDescription()
```

Gets text associated with the file specification.

**Returns:**
String value

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Gets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed.

**Returns:**
int value @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Gets encrypted payload.

**Returns:**
EncryptedPayload instance

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Pdf dictionary containing information about the file. Internal only

**Returns:**
IPdfDictionary object

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Internal only

**Returns:**
IPdfObject object

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Gets name of the file system.

**Returns:**
String value

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Gets subtype of the embedded file

**Returns:**
string value

### getName {#getName--}
```
public String getName()
```

Gets file specification name.

**Returns:**
String value

### getParams {#getParams--}
```
public FileParams getParams()
```

Gets file parameters.

**Returns:**
FileParams object

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Gets contents of file as stream. Contents is not loaded into memory which allows to decrease memory usage. But this stream does not support positioning and Length property. If you need this features please use Contents property instead.

**Returns:**
InputStream object

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Gets file specification unicode name.

**Returns:**
String value

### getValue {#getValue-java.lang.String-}
Gets application-specific parameter.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

If true, contents of the file will be included in the file specification.

**Returns:**
boolean value

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Associated file Relationship.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Sets contents file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of bytes |

### setContents {#setContents-java.io.InputStream-}
Sets contents file.

### setDescription {#setDescription-java.lang.String-}
Sets text associated with the file specification.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Sets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed.

### setFileSystem {#setFileSystem-java.lang.String-}
Sets name of the file system.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

If true, contents of the file will be included in the file specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMIMEType {#setMIMEType-java.lang.String-}
Sets MIMEType.

### setName {#setName-java.lang.String-}
Sets file specification name.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Sets file parameters.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Sets file specification unicode name.

### setValue {#setValue-java.lang.String-java.lang.String-}
Sets application-specific parameter.
