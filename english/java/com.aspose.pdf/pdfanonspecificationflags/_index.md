---
title: PdfFormatConversionOptions.PdfANonSpecificationFlags
second_title: Aspose.PDF for Java API Reference
description: This class holds flags to control PDF/A conversion for cases when source PDF document doesnt correspond to PDF specification.
type: docs
weight: 10
url: /java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object
```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags
```

This class holds flags to control PDF/A conversion for cases when source PDF document doesn't correspond to PDF specification. If flags of this clas are used it decreases performance but it's necessary when source PDF document can't be convert into PDF/A format by usual way. By default all flags are set to false.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfANonSpecificationFlags()](#PdfANonSpecificationFlags--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckDifferentNamesInFontDictionaries()](#getCheckDifferentNamesInFontDictionaries--) | Some PDF documents contain fonts which have different names in internal data. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCheckDifferentNamesInFontDictionaries(boolean value)](#setCheckDifferentNamesInFontDictionaries-boolean-) | Some PDF documents contain fonts which have different names in internal data. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfANonSpecificationFlags() {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```


Constructor

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
### getCheckDifferentNamesInFontDictionaries() {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```


Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different.

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setCheckDifferentNamesInFontDictionaries(boolean value) {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```


Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

