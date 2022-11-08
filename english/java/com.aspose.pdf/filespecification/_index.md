---
title: FileSpecification
second_title: Aspose.PDF for Java API Reference
description: Class representing embedded file.
type: docs
weight: 118
url: /java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class FileSpecification implements System.IDisposable, Closeable
```

Class representing embedded file.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileSpecification(IPdfPrimitive specification)](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | File specification |
| [FileSpecification(String file)](#FileSpecification-java.lang.String-) | Constructor for FileSpecification |
| [FileSpecification(System.IO.Stream stream, String name)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Constructor for file specification. |
| [FileSpecification(InputStream stream, String name)](#FileSpecification-java.io.InputStream-java.lang.String-) | Constructor for file specification. |
| [FileSpecification(String file, String description)](#FileSpecification-java.lang.String-java.lang.String-) | Constructor for FileSpecification. |
| [FileSpecification(System.IO.Stream stream, String name, String description)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Constructor for FileSpecification. |
| [FileSpecification(InputStream stream, String name, String description)](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Constructor for FileSpecification. |
| [FileSpecification(String fileName, Annotation annot)](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Constructor for FileSpecification. |
| [FileSpecification()](#FileSpecification--) | Create new empty file specification. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Dispose contents. |
| [dispose()](#dispose--) | Dispose contents. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFRelationship()](#getAFRelationship--) | Associated file Relationship. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Gets contents file. |
| [getContentsInternal()](#getContentsInternal--) | Gets contents file. |
| [getDescription()](#getDescription--) | Gets text associated with the file specification. |
| [getEncoding()](#getEncoding--) | Gets encoding format. |
| [getEncryptedPayload()](#getEncryptedPayload--) | Gets encrypted payload. |
| [getEngineDict()](#getEngineDict--) | Pdf dictionary containing information about the file. |
| [getEngineObj()](#getEngineObj--) | Internal only |
| [getFileSystem()](#getFileSystem--) | Gets name of the file system. |
| [getMIMEType()](#getMIMEType--) | Gets subtype of the embedded file |
| [getName()](#getName--) | Gets file specification name. |
| [getParams()](#getParams--) | Gets file paramteres. |
| [getStreamContents()](#getStreamContents--) | Gets contents of file as stream. |
| [getUnicodeName()](#getUnicodeName--) | Gets file specification unicode name. |
| [getValue(String key)](#getValue-java.lang.String-) | Gets application-specific parameter. |
| [hashCode()](#hashCode--) |  |
| [isIncludeContents()](#isIncludeContents--) | If true, contents of the file will be included in the file specification. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAFRelationship(AFRelationship value)](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Associated file Relationship. |
| [setContents(byte[] value)](#setContents-byte---) | Sets contents file. |
| [setContents(InputStream value)](#setContents-java.io.InputStream-) | Sets contents file. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets text associated with the file specification. |
| [setEncoding(int value)](#setEncoding-int-) | Sets encoding format. |
| [setFileSystem(String value)](#setFileSystem-java.lang.String-) | Sets name of the file system. |
| [setIncludeContents(boolean value)](#setIncludeContents-boolean-) | If true, contents of the file will be included in the file specification. |
| [setMIMEType(String value)](#setMIMEType-java.lang.String-) | Sets MIMEType. |
| [setName(String value)](#setName-java.lang.String-) | Sets file specification name. |
| [setParams(FileParams value)](#setParams-com.aspose.pdf.FileParams-) | Sets file paramteres. |
| [setUnicodeName(String value)](#setUnicodeName-java.lang.String-) | Sets file specification unicode name. |
| [setValue(String key, String value)](#setValue-java.lang.String-java.lang.String-) | Sets application-specific parameter. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSpecification(IPdfPrimitive specification) {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public FileSpecification(IPdfPrimitive specification)
```


File specification

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive object |

### FileSpecification(String file) {#FileSpecification-java.lang.String-}
```
public FileSpecification(String file)
```


Constructor for FileSpecification

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | File path. |

### FileSpecification(System.IO.Stream stream, String name) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name)
```


Constructor for file specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Stream containing data file. |
| name | java.lang.String | File specification. |

### FileSpecification(InputStream stream, String name) {#FileSpecification-java.io.InputStream-java.lang.String-}
```
public FileSpecification(InputStream stream, String name)
```


Constructor for file specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream containing data file. |
| name | java.lang.String | File specification. |

### FileSpecification(String file, String description) {#FileSpecification-java.lang.String-java.lang.String-}
```
public FileSpecification(String file, String description)
```


Constructor for FileSpecification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | File path. |
| description | java.lang.String | File description. |

### FileSpecification(System.IO.Stream stream, String name, String description) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name, String description)
```


Constructor for FileSpecification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Stream to be used in the document. |
| name | java.lang.String | A file specification string. |
| description | java.lang.String | File description. |

### FileSpecification(InputStream stream, String name, String description) {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
```
public FileSpecification(InputStream stream, String name, String description)
```


Constructor for FileSpecification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to be used in the document. |
| name | java.lang.String | A file specification string. |
| description | java.lang.String | File description. |

### FileSpecification(String fileName, Annotation annot) {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
```
public FileSpecification(String fileName, Annotation annot)
```


Constructor for FileSpecification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | String object |
| annot | [Annotation](../../com.aspose.pdf/annotation) | Annotation object |

### FileSpecification() {#FileSpecification--}
```
public FileSpecification()
```


Create new empty file specification.

### close() {#close--}
```
public void close()
```


Dispose contents.

### dispose() {#dispose--}
```
public void dispose()
```


Dispose contents.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAFRelationship() {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```


Associated file Relationship.

**Returns:**
[AFRelationship](../../com.aspose.pdf/afrelationship) - AFRelationship element
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContents() {#getContents--}
```
public InputStream getContents()
```


Gets contents file.

**Returns:**
java.io.InputStream - InputStream object
### getContentsInternal() {#getContentsInternal--}
```
public System.IO.Stream getContentsInternal()
```


Gets contents file.

**Returns:**
com.aspose.ms.System.IO.Stream - Stream object
### getDescription() {#getDescription--}
```
public String getDescription()
```


Gets text associated with the file specification.

**Returns:**
java.lang.String - String value
### getEncoding() {#getEncoding--}
```
public int getEncoding()
```


Gets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed.

**Returns:**
int - int value
### getEncryptedPayload() {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```


Gets encrypted payload.

**Returns:**
[EncryptedPayload](../../com.aspose.pdf/encryptedpayload) - EncryptedPayload instance
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Pdf dictionary containing information about the file. Internal only

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary object
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Internal only

**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - IPdfObject object
### getFileSystem() {#getFileSystem--}
```
public String getFileSystem()
```


Gets name of the file system.

**Returns:**
java.lang.String - String value
### getMIMEType() {#getMIMEType--}
```
public String getMIMEType()
```


Gets subtype of the embedded file

**Returns:**
java.lang.String - string value
### getName() {#getName--}
```
public String getName()
```


Gets file specification name.

**Returns:**
java.lang.String - String value
### getParams() {#getParams--}
```
public FileParams getParams()
```


Gets file paramteres.

**Returns:**
[FileParams](../../com.aspose.pdf/fileparams) - FileParams object
### getStreamContents() {#getStreamContents--}
```
public InputStream getStreamContents()
```


Gets contents of file as stream. Contents is not loaded into memory which allows to decrease memory usage. But this stream does not support positioning and Length property. If you need this features please use Contents property instead.

**Returns:**
java.io.InputStream - InputStream object
### getUnicodeName() {#getUnicodeName--}
```
public String getUnicodeName()
```


Gets file specification unicode name.

**Returns:**
java.lang.String - String value
### getValue(String key) {#getValue-java.lang.String-}
```
public final String getValue(String key)
```


Gets application-specific parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Parameter name. |

**Returns:**
java.lang.String - String value - if parameter found; otherwise, null.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isIncludeContents() {#isIncludeContents--}
```
public boolean isIncludeContents()
```


If true, contents of the file will be included in the file specification.

**Returns:**
boolean - boolean value
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


Associated file Relationship.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AFRelationship](../../com.aspose.pdf/afrelationship) | AFRelationship element |

### setContents(byte[] value) {#setContents-byte---}
```
public void setContents(byte[] value)
```


Sets contents file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | array of bytes |

### setContents(InputStream value) {#setContents-java.io.InputStream-}
```
public void setContents(InputStream value)
```


Sets contents file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Sets text associated with the file specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setEncoding(int value) {#setEncoding-int-}
```
public void setEncoding(int value)
```


Sets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setFileSystem(String value) {#setFileSystem-java.lang.String-}
```
public void setFileSystem(String value)
```


Sets name of the file system.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setIncludeContents(boolean value) {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```


If true, contents of the file will be included in the file specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMIMEType(String value) {#setMIMEType-java.lang.String-}
```
public void setMIMEType(String value)
```


Sets MIMEType.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets file specification name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setParams(FileParams value) {#setParams-com.aspose.pdf.FileParams-}
```
public void setParams(FileParams value)
```


Sets file paramteres.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileParams](../../com.aspose.pdf/fileparams) | FileParams object |

### setUnicodeName(String value) {#setUnicodeName-java.lang.String-}
```
public void setUnicodeName(String value)
```


Sets file specification unicode name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setValue(String key, String value) {#setValue-java.lang.String-java.lang.String-}
```
public final void setValue(String key, String value)
```


Sets application-specific parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Parameter name. |
| value | java.lang.String | New parameter value. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

