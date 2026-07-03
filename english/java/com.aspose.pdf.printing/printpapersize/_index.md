---
title: PrintPaperSize
second_title: Aspose.PDF for Java API Reference
description: Specifies the size of a piece of paper.
type: docs
weight: 100
url: /java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Specifies the size of a piece of paper.

## Constructors

| Constructor | Description |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Initializes a new instance of the PaperSize class. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Initializes a new instance of the PaperSize class. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Initializes a new instance of the PaperSize class. |

## Methods

| Method | Description |
| --- | --- |
| [getHeight](#getHeight--) | Gets or sets the height of the paper, in hundredths of an inch. |
| [getKind](#getKind--) | Gets the type of paper. |
| [getPaperName](#getPaperName--) | Gets or sets the name of the type of paper. |
| [getRawKind](#getRawKind--) | Gets or sets an integer representing one of the PaperSize values or a custom value. |
| [getWidth](#getWidth--) | Gets or sets the width of the paper, in hundredths of an inch. |
| [setHeight](#setHeight-int-) | Gets or sets the height of the paper, in hundredths of an inch. |
| [setPaperName](#setPaperName-java.lang.String-) | Gets the name of the type of paper. |
| [setWidth](#setWidth-int-) | Sets the width of the paper, in hundredths of an inch. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Converts {@link PaperSize} to Windows-specific System.Drawing.Printing.PaperSize. |
| [toString](#toString--) | Gets the name of this instance. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Initializes a new instance of the PaperSize class.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Initializes a new instance of the PaperSize class.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Initializes a new instance of the PaperSize class.

### getHeight {#getHeight--}
```
public int getHeight()
```

Gets or sets the height of the paper, in hundredths of an inch.

**Returns:**
int value

### getKind {#getKind--}
```
public int getKind()
```

Gets the type of paper.

**Returns:**
int value @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Gets or sets the name of the type of paper.

**Returns:**
String value

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Gets or sets an integer representing one of the PaperSize values or a custom value.

**Returns:**
int value

### getWidth {#getWidth--}
```
public int getWidth()
```

Gets or sets the width of the paper, in hundredths of an inch.

**Returns:**
int value

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Gets or sets the height of the paper, in hundredths of an inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPaperName {#setPaperName-java.lang.String-}
Gets the name of the type of paper.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Sets the width of the paper, in hundredths of an inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Converts {@link PaperSize} to Windows-specific System.Drawing.Printing.PaperSize.

### toString {#toString--}
```
public String toString()
```

Gets the name of this instance.

**Returns:**
String value
