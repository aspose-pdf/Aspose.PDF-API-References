---
title: DuplexKind
second_title: Aspose.PDF for Java API Reference
description: Specifies the printers duplex setting.
type: docs
weight: 11
url: /java/com.aspose.pdf.printing/duplexkind/
---
**Inheritance:**
java.lang.Object
```
public class DuplexKind
```

Specifies the printer's duplex setting.
## Constructors

| Constructor | Description |
| --- | --- |
| [DuplexKind()](#DuplexKind--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | The printer's default duplex setting. |
| [Horizontal](#Horizontal) | Double-sided, horizontal printing. |
| [Simplex](#Simplex) | Single-sided printing. |
| [Vertical](#Vertical) | Double-sided, vertical printing. |
## Methods

| Method | Description |
| --- | --- |
| [toString(int pdfPrintRange)](#toString-int-) | Duplex kind name |
| [getNames()](#getNames--) | Array of Duplex kind names |
### DuplexKind() {#DuplexKind--}
```
public DuplexKind()
```


### Default {#Default}
```
public static final int Default
```


The printer's default duplex setting.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Double-sided, horizontal printing.

### Simplex {#Simplex}
```
public static final int Simplex
```


Single-sided printing.

### Vertical {#Vertical}
```
public static final int Vertical
```


Double-sided, vertical printing.

### toString(int pdfPrintRange) {#toString-int-}
```
public static String toString(int pdfPrintRange)
```


Duplex kind name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfPrintRange | int | PaperKind element |

**Returns:**
java.lang.String - Paper format name
### getNames() {#getNames--}
```
public static String[] getNames()
```


Array of Duplex kind names

**Returns:**
java.lang.String[] - String[] object
