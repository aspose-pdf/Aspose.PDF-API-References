---
title: SaveFormat
second_title: Aspose.PDF for Java API Reference
description: Specifies format
type: docs
weight: 446
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
| [Pdf](#Pdf) | means saving without change of format, i.e. as PDF use it please instead of 'SaveFormat.None', that is obsolete one |
| [None](#None) | means saving without change of format, i.e. as PDF It's obsolete one and will be deleted eventually, please use instead 'SaveFormat.Pdf' |
| [Doc](#Doc) | means saving in DOC format |
| [Xps](#Xps) | means saving in XPS format |
| [Html](#Html) | means saving in HTML format |
| [Xml](#Xml) | means saving in XML format |
| [TeX](#TeX) | means saving in TEX format i.e. format suitable for Latex text editor |
| [DocX](#DocX) | means saving in DOCX format |
| [Svg](#Svg) | means saving in SVG format |
| [MobiXml](#MobiXml) | means saving in MobiXML format(special format of e-books) |
| [Excel](#Excel) | means saving in MsExcel format |
| [Epub](#Epub) | means saving in EPUB format(special format of e-books) |
| [Plugin](#Plugin) | means saving with the aid of a plugin |
| [Pptx](#Pptx) | means saving in MHT(WebArchieve) /// |
| [Aps](#Aps) | Saving as APS XML file. |
| [PdfXml](#PdfXml) | Internal PDF document structure in XML format |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) |  |
### Pdf {#Pdf}
```
public static final SaveFormat Pdf
```


means saving without change of format, i.e. as PDF use it please instead of 'SaveFormat.None', that is obsolete one

### None {#None}
```
public static final SaveFormat None
```


means saving without change of format, i.e. as PDF It's obsolete one and will be deleted eventually, please use instead 'SaveFormat.Pdf'

### Doc {#Doc}
```
public static final SaveFormat Doc
```


means saving in DOC format

### Xps {#Xps}
```
public static final SaveFormat Xps
```


means saving in XPS format

### Html {#Html}
```
public static final SaveFormat Html
```


means saving in HTML format

### Xml {#Xml}
```
public static final SaveFormat Xml
```


means saving in XML format

### TeX {#TeX}
```
public static final SaveFormat TeX
```


means saving in TEX format i.e. format suitable for Latex text editor

### DocX {#DocX}
```
public static final SaveFormat DocX
```


means saving in DOCX format

### Svg {#Svg}
```
public static final SaveFormat Svg
```


means saving in SVG format

### MobiXml {#MobiXml}
```
public static final SaveFormat MobiXml
```


means saving in MobiXML format(special format of e-books)

### Excel {#Excel}
```
public static final SaveFormat Excel
```


means saving in MsExcel format

### Epub {#Epub}
```
public static final SaveFormat Epub
```


means saving in EPUB format(special format of e-books)

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

### Aps {#Aps}
```
public static final SaveFormat Aps
```


Saving as APS XML file.

### PdfXml {#PdfXml}
```
public static final SaveFormat PdfXml
```


Internal PDF document structure in XML format

### values() {#values--}
```
public static SaveFormat[] values()
```




**Returns:**
com.aspose.pdf.SaveFormat[]
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
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
