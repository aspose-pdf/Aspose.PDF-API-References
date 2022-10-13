---
title: DocumentPrivilege
second_title: Aspose.PDF for Java API Reference
description: Represents the privileges for accessing Pdf file.
type: docs
weight: 18
url: /java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public final class DocumentPrivilege implements Comparable
```

Represents the privileges for accessing Pdf file. Refer to PdfFileSecurity . There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3.

--------------------

> ```
> //Way1: Using predefined privilege directly.
>   DocumentPrivilege privilege = DocumentPrivilege.getPrint();
>   //Way2: Based on a predefined privilege and change some specifical permissions.
>   DocumentPrivilege privilege = DocumentPrivilege.getAllowAll();
>   privilege.setAllowPrint(false);
>   privilege.setAllowModifyContents(false);
>   //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
>   DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
>   privilege.setChangeAllowLevel(1);
>   privilege.setPrintAllowLevel(2);
>   //Way4: Mixes the way2 and way3
>   DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
>   privilege.setChangeAllowLevel(1);
>   privilege.setAllowPrint(true);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentPrivilege(int value)](#DocumentPrivilege-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) |  |
| [getAllowPrint()](#getAllowPrint--) | Sets the permission which allow print or not. |
| [setAllowPrint(boolean value)](#setAllowPrint-boolean-) |  |
| [getAllowDegradedPrinting()](#getAllowDegradedPrinting--) | Sets the permission which allow degraded printing or not. |
| [setAllowDegradedPrinting(boolean value)](#setAllowDegradedPrinting-boolean-) |  |
| [getAllowModifyContents()](#getAllowModifyContents--) | Sets the permission which allow modify contents or not. |
| [setAllowModifyContents(boolean value)](#setAllowModifyContents-boolean-) |  |
| [getAllowCopy()](#getAllowCopy--) | Sets the permission which allow copy or not. |
| [setAllowCopy(boolean value)](#setAllowCopy-boolean-) |  |
| [getAllowModifyAnnotations()](#getAllowModifyAnnotations--) | Sets the permission which allow modify annotations or not. |
| [setAllowModifyAnnotations(boolean value)](#setAllowModifyAnnotations-boolean-) |  |
| [getAllowFillIn()](#getAllowFillIn--) | Sets the permission which allow fill in forms or not. |
| [setAllowFillIn(boolean value)](#setAllowFillIn-boolean-) |  |
| [getAllowScreenReaders()](#getAllowScreenReaders--) | Sets the permission which allow screen readers or not. |
| [setAllowScreenReaders(boolean value)](#setAllowScreenReaders-boolean-) |  |
| [getAllowAssembly()](#getAllowAssembly--) | Sets the permission which allow assembly or not. |
| [setAllowAssembly(boolean value)](#setAllowAssembly-boolean-) |  |
| [setPrintAllowLevel(int value)](#setPrintAllowLevel-int-) | Sets the print level of document's privilege. |
| [setChangeAllowLevel(int value)](#setChangeAllowLevel-int-) | Sets the change level of document's privilege. |
| [setCopyAllowLevel(int value)](#setCopyAllowLevel-int-) | Sets the copy level of document's privilege. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares two  DocumentPrivilege  objects. |
| [getDegradedPrinting()](#getDegradedPrinting--) | Allows degraded printing. |
| [getPrint()](#getPrint--) | Allows printing file. |
| [getModifyContents()](#getModifyContents--) | Allows modifying file. |
| [getCopy()](#getCopy--) | Allows copying file. |
| [getModifyAnnotations()](#getModifyAnnotations--) | Allows modifying annotations of file. |
| [getFillIn()](#getFillIn--) | Allows filling forms in file. |
| [getScreenReaders()](#getScreenReaders--) | Allows to reader on screen only. |
| [getAssembly()](#getAssembly--) | Allows assemblying file. |
| [getAllowAll()](#getAllowAll--) | All allowed. |
| [getForbidAll()](#getForbidAll--) | All Forbidded. |
### DocumentPrivilege(int value) {#DocumentPrivilege-int-}
```
public DocumentPrivilege(int value)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### getAllowPrint() {#getAllowPrint--}
```
public boolean getAllowPrint()
```


Sets the permission which allow print or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowPrint(boolean value) {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowDegradedPrinting() {#getAllowDegradedPrinting--}
```
public boolean getAllowDegradedPrinting()
```


Sets the permission which allow degraded printing or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowDegradedPrinting(boolean value) {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowModifyContents() {#getAllowModifyContents--}
```
public boolean getAllowModifyContents()
```


Sets the permission which allow modify contents or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowModifyContents(boolean value) {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowCopy() {#getAllowCopy--}
```
public boolean getAllowCopy()
```


Sets the permission which allow copy or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowCopy(boolean value) {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowModifyAnnotations() {#getAllowModifyAnnotations--}
```
public boolean getAllowModifyAnnotations()
```


Sets the permission which allow modify annotations or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowModifyAnnotations(boolean value) {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowFillIn() {#getAllowFillIn--}
```
public boolean getAllowFillIn()
```


Sets the permission which allow fill in forms or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowFillIn(boolean value) {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowScreenReaders() {#getAllowScreenReaders--}
```
public boolean getAllowScreenReaders()
```


Sets the permission which allow screen readers or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowScreenReaders(boolean value) {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowAssembly() {#getAllowAssembly--}
```
public boolean getAllowAssembly()
```


Sets the permission which allow assembly or not. true is allow and false is forbidden.

**Returns:**
boolean
### setAllowAssembly(boolean value) {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPrintAllowLevel(int value) {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```


Sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setChangeAllowLevel(int value) {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```


Sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCopyAllowLevel(int value) {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```


Sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public int compareTo(Object obj)
```


Compares two  DocumentPrivilege  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with. |

**Returns:**
int
### getDegradedPrinting() {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```


Allows degraded printing.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getPrint() {#getPrint--}
```
public static DocumentPrivilege getPrint()
```


Allows printing file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getModifyContents() {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```


Allows modifying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getCopy() {#getCopy--}
```
public static DocumentPrivilege getCopy()
```


Allows copying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getModifyAnnotations() {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```


Allows modifying annotations of file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getFillIn() {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```


Allows filling forms in file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getScreenReaders() {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```


Allows to reader on screen only.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getAssembly() {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```


Allows assemblying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getAllowAll() {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```


All allowed.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
### getForbidAll() {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```


All Forbidded.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege)
