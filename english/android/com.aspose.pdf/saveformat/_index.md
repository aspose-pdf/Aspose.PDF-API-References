---
title: SaveFormat
second_title: Aspose.PDF for Java API Reference
description: Specifies format
type: docs
weight: 257
url: /java/com.aspose.pdf/saveformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SaveFormat extends System.Enum
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
### Pdf {#Pdf}
```
public static final int Pdf
```


means saving without change of format, i.e. as PDF use it please instead of 'SaveFormat.None', that is obsolete one

### None {#None}
```
public static final int None
```


means saving without change of format, i.e. as PDF It's obsolete one and will be deleted eventually, please use instead 'SaveFormat.Pdf'

### Doc {#Doc}
```
public static final int Doc
```


means saving in DOC format

### Xps {#Xps}
```
public static final int Xps
```


means saving in XPS format

### Html {#Html}
```
public static final int Html
```


means saving in HTML format

### Xml {#Xml}
```
public static final int Xml
```


means saving in XML format

### TeX {#TeX}
```
public static final int TeX
```


means saving in TEX format i.e. format suitable for Latex text editor

### DocX {#DocX}
```
public static final int DocX
```


means saving in DOCX format

### Svg {#Svg}
```
public static final int Svg
```


means saving in SVG format

### MobiXml {#MobiXml}
```
public static final int MobiXml
```


means saving in MobiXML format(special format of e-books)

### Excel {#Excel}
```
public static final int Excel
```


means saving in MsExcel format

### Epub {#Epub}
```
public static final int Epub
```


means saving in EPUB format(special format of e-books)

### Plugin {#Plugin}
```
public static final int Plugin
```


means saving with the aid of a plugin

### Pptx {#Pptx}
```
public static final int Pptx
```


means saving in MHT(WebArchieve) ///

Convet document to Mht format. This code was experimental one used during works related to https://pdf.aspose.com/jira/browse/PDFNEWNET-36340 is not going on production, cause there are cross-browsers problems with created MHT - so, it can be used in the future if finally it will be necessary to create MHT itself. PDFNEWNET-36340 was resolved with usage of DataSceme URLs(embedding data into HTML http://en.wikipedia.org/wiki/Data\_URI\_scheme) So, this conversion really not used right now.

means saving in PPTX format

