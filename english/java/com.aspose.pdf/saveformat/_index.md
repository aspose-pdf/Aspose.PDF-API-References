---
title: SaveFormat
second_title: Aspose.PDF for Java API Reference
description: Specifies format
type: docs
weight: 445
url: /java/com.aspose.pdf/saveformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SaveFormat extends Enum<SaveFormat>
```

Specifies format
## Fields

| Field | Description |
| --- | --- |
| [Aps](#Aps) | Saving as APS XML file. |
| [Doc](#Doc) | means saving in DOC format |
| [DocX](#DocX) | means saving in DOCX format |
| [Epub](#Epub) | means saving in EPUB format(special format of e-books) |
| [Excel](#Excel) | means saving in MsExcel format |
| [Html](#Html) | means saving in HTML format |
| [MobiXml](#MobiXml) | means saving in MobiXML format(special format of e-books) |
| [None](#None) | means saving without change of format, i.e. as PDF It's obsolete one and will be deleted eventually, please use instead 'SaveFormat.Pdf' |
| [Pdf](#Pdf) | means saving without change of format, i.e. as PDF use it please instead of 'SaveFormat.None', that is obsolete one |
| [PdfXml](#PdfXml) | Internal PDF document structure in XML format |
| [Plugin](#Plugin) | means saving with the aid of a plugin |
| [Pptx](#Pptx) | means saving in MHT(WebArchieve) /// |
| [Svg](#Svg) | means saving in SVG format |
| [TeX](#TeX) | means saving in TEX format i.e. format suitable for Latex text editor |
| [Xml](#Xml) | means saving in XML format |
| [Xps](#Xps) | means saving in XPS format |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Aps {#Aps}
```
public static final SaveFormat Aps
```


Saving as APS XML file.

### Doc {#Doc}
```
public static final SaveFormat Doc
```


means saving in DOC format

### DocX {#DocX}
```
public static final SaveFormat DocX
```


means saving in DOCX format

### Epub {#Epub}
```
public static final SaveFormat Epub
```


means saving in EPUB format(special format of e-books)

### Excel {#Excel}
```
public static final SaveFormat Excel
```


means saving in MsExcel format

### Html {#Html}
```
public static final SaveFormat Html
```


means saving in HTML format

### MobiXml {#MobiXml}
```
public static final SaveFormat MobiXml
```


means saving in MobiXML format(special format of e-books)

### None {#None}
```
public static final SaveFormat None
```


means saving without change of format, i.e. as PDF It's obsolete one and will be deleted eventually, please use instead 'SaveFormat.Pdf'

### Pdf {#Pdf}
```
public static final SaveFormat Pdf
```


means saving without change of format, i.e. as PDF use it please instead of 'SaveFormat.None', that is obsolete one

### PdfXml {#PdfXml}
```
public static final SaveFormat PdfXml
```


Internal PDF document structure in XML format

### Plugin {#Plugin}
```
public static final SaveFormat Plugin
```


means saving with the aid of a plugin

### Pptx {#Pptx}
```
public static final SaveFormat Pptx
```


means saving in MHT(WebArchieve) ///

Convet document to Mht format. This code was experimental one used during works related to https://pdf.aspose.com/jira/browse/PDFNEWNET-36340 is not going on production, cause there are cross-browsers problems with created MHT - so, it can be used in the future if finally it will be necessary to create MHT itself. PDFNEWNET-36340 was resolved with usage of DataSceme URLs(embedding data into HTML http://en.wikipedia.org/wiki/Data\_URI\_scheme) So, this conversion really not used right now.

means saving in PPTX format

### Svg {#Svg}
```
public static final SaveFormat Svg
```


means saving in SVG format

### TeX {#TeX}
```
public static final SaveFormat TeX
```


means saving in TEX format i.e. format suitable for Latex text editor

### Xml {#Xml}
```
public static final SaveFormat Xml
```


means saving in XML format

### Xps {#Xps}
```
public static final SaveFormat Xps
```


means saving in XPS format

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SaveFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat)
### values() {#values--}
```
public static SaveFormat[] values()
```




**Returns:**
com.aspose.pdf.SaveFormat[]
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

