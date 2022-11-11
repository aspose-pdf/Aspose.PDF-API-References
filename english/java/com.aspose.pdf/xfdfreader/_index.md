---
title: XfdfReader
second_title: Aspose.PDF for Java API Reference
description: Class which peroformes reading of XFDF format.
type: docs
weight: 413
url: /java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object
```
public final class XfdfReader
```

Class which peroformes reading of XFDF format.

--------------------

`Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf");`
## Constructors

| Constructor | Description |
| --- | --- |
| [XfdfReader()](#XfdfReader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements(System.Xml.XmlReader reader)](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Parses XFDF file and returns information as hashtable. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAnnotations(InputStream stream, IDocument document)](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Import annotations from XFDF file and put them into document. |
| [readFields(InputStream stream, IDocument document)](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Import field values from XFDF file. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfdfReader() {#XfdfReader--}
```
public XfdfReader()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements(System.Xml.XmlReader reader) {#getElements-com.aspose.ms.System.Xml.XmlReader-}
```
public static Map getElements(System.Xml.XmlReader reader)
```


Parses XFDF file and returns information as hashtable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reader | com.aspose.ms.System.Xml.XmlReader | XmlReader for the source file. |

**Returns:**
java.util.Map - Hashtable with information parsed from XFDF file.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readAnnotations(InputStream stream, IDocument document) {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readAnnotations(InputStream stream, IDocument document)
```


Import annotations from XFDF file and put them into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream containing XFDF file. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotations will be added. |

### readFields(InputStream stream, IDocument document) {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readFields(InputStream stream, IDocument document)
```


Import field values from XFDF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream containing XFDF data. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where fields data will be imported. |

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

