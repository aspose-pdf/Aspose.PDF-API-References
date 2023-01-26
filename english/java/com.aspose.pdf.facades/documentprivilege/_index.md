---
title: DocumentPrivilege
second_title: Aspose.PDF for Java API Reference
description: Represents the privileges for accessing Pdf file.
type: docs
weight: 19
url: /java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public final class DocumentPrivilege implements Comparable<Object>
```

Represents the privileges for accessing Pdf file. Refer to PdfFileSecurity . There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3.

--------------------

```
//Way1: Using predefined privilege directly.
  DocumentPrivilege privilege = DocumentPrivilege.getPrint();
  //Way2: Based on a predefined privilege and change some specifical permissions.
  DocumentPrivilege privilege = DocumentPrivilege.getAllowAll();
  privilege.setAllowPrint(false);
  privilege.setAllowModifyContents(false);
  //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setPrintAllowLevel(2);
  //Way4: Mixes the way2 and way3
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setAllowPrint(true);
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentPrivilege(int value)](#DocumentPrivilege-int-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets value |
| [isAllowPrint()](#isAllowPrint--) | Sets the permission which allow print or not. |
| [setAllowPrint(boolean value)](#setAllowPrint-boolean-) | Sets the permission which allow print or not. |
| [isAllowDegradedPrinting()](#isAllowDegradedPrinting--) | Sets the permission which allow degraded printing or not. |
| [setAllowDegradedPrinting(boolean value)](#setAllowDegradedPrinting-boolean-) | Sets the permission which allow degraded printing or not. |
| [isAllowModifyContents()](#isAllowModifyContents--) | Sets the permission which allow modify contents or not. |
| [setAllowModifyContents(boolean value)](#setAllowModifyContents-boolean-) | Sets the permission which allow modify contents or not. |
| [isAllowCopy()](#isAllowCopy--) | Sets the permission which allow copy or not. |
| [setAllowCopy(boolean value)](#setAllowCopy-boolean-) | Sets the permission which allow copy or not. |
| [isAllowModifyAnnotations()](#isAllowModifyAnnotations--) | Sets the permission which allow modify annotations or not. |
| [setAllowModifyAnnotations(boolean value)](#setAllowModifyAnnotations-boolean-) | Sets the permission which allow modify annotations or not. |
| [isAllowFillIn()](#isAllowFillIn--) | Sets the permission which allow fill in forms or not. |
| [setAllowFillIn(boolean value)](#setAllowFillIn-boolean-) | Sets the permission which allow fill in forms or not. |
| [isAllowScreenReaders()](#isAllowScreenReaders--) | Sets the permission which allow screen readers or not. |
| [setAllowScreenReaders(boolean value)](#setAllowScreenReaders-boolean-) | Sets the permission which allow screen readers or not. |
| [isAllowAssembly()](#isAllowAssembly--) | Sets the permission which allow assembly or not. |
| [setAllowAssembly(boolean value)](#setAllowAssembly-boolean-) | Sets the permission which allow assembly or not. |
| [setPrintAllowLevel(int value)](#setPrintAllowLevel-int-) | Sets the print level of document's privilege. |
| [setChangeAllowLevel(int value)](#setChangeAllowLevel-int-) | Sets the change level of document's privilege. |
| [setCopyAllowLevel(int value)](#setCopyAllowLevel-int-) | Sets the copy level of document's privilege. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares two  DocumentPrivilege  objects. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether some other object is "equal to" this one. |
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


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | document's Permissions |

### getValue() {#getValue--}
```
public int getValue()
```


Gets value

**Returns:**
int - int value
### isAllowPrint() {#isAllowPrint--}
```
public boolean isAllowPrint()
```


Sets the permission which allow print or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowPrint(boolean value) {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```


Sets the permission which allow print or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowDegradedPrinting() {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```


Sets the permission which allow degraded printing or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowDegradedPrinting(boolean value) {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```


Sets the permission which allow degraded printing or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowModifyContents() {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```


Sets the permission which allow modify contents or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowModifyContents(boolean value) {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```


Sets the permission which allow modify contents or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowCopy() {#isAllowCopy--}
```
public boolean isAllowCopy()
```


Sets the permission which allow copy or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowCopy(boolean value) {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```


Sets the permission which allow copy or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowModifyAnnotations() {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```


Sets the permission which allow modify annotations or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowModifyAnnotations(boolean value) {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```


Sets the permission which allow modify annotations or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowFillIn() {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```


Sets the permission which allow fill in forms or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowFillIn(boolean value) {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```


Sets the permission which allow fill in forms or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowScreenReaders() {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```


Sets the permission which allow screen readers or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowScreenReaders(boolean value) {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```


Sets the permission which allow screen readers or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAllowAssembly() {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```


Sets the permission which allow assembly or not. true is allow and false is forbidden.

**Returns:**
boolean - boolean value
### setAllowAssembly(boolean value) {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```


Sets the permission which allow assembly or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPrintAllowLevel(int value) {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```


Sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setChangeAllowLevel(int value) {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```


Sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setCopyAllowLevel(int value) {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```


Sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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
int - A signed integer that indicates the relative values of this instance and value. Less than zero this instance is less than value. Zero this instance is equal to value. Greater than zero this instance is greater than value.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hashtables such as those provided by `java.util.Hashtable`.

The general contract of `hashCode` is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the hashCode method must consistently return the same integer, provided no information used in equals comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the equals(Object) method, then calling the `hashCode` method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object)\#equals(java.lang.Object) method, then calling the hashCode method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hashtables.

As much as is reasonably practical, the hashCode method defined by class Object does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the JavaTM programming language.)

**Returns:**
int - a hash code value for this object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether some other object is "equal to" this one.

The `equals` method implements an equivalence relation on non-null object references:

 *  It is *reflexive*: for any non-null reference value `x`, `x.equals(x)` should return `true`.
 *  It is *symmetric*: for any non-null reference values `x` and `y`, `x.equals(y)` should return `true` if and only if `y.equals(x)` returns `true`.
 *  It is *transitive*: for any non-null reference values `x`, `y`, and `z`, if `x.equals(y)` returns `true` and `y.equals(z)` returns `true`, then `x.equals(z)` should return `true`.
 *  It is *consistent*: for any non-null reference values `x` and `y`, multiple invocations of x.equals(y) consistently return `true` or consistently return `false`, provided no information used in `equals` comparisons on the objects is modified.
 *  For any non-null reference value `x`, `x.equals(null)` should return `false`.

The equals method for class `Object` implements the most discriminating possible equivalence relation on objects; that is, for any non-null reference values `x` and `y`, this method returns `true` if and only if `x` and `y` refer to the same object (`x == y` has the value `true`).

Note that it is generally necessary to override the hashCode method whenever this method is overridden, so as to maintain the general contract for the hashCode method, which states that equal objects must have equal hash codes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | the reference object with which to compare. |

**Returns:**
boolean - `true` if this object is the same as the obj argument; `false` otherwise.
### getDegradedPrinting() {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```


Allows degraded printing.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getPrint() {#getPrint--}
```
public static DocumentPrivilege getPrint()
```


Allows printing file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getModifyContents() {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```


Allows modifying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getCopy() {#getCopy--}
```
public static DocumentPrivilege getCopy()
```


Allows copying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getModifyAnnotations() {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```


Allows modifying annotations of file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getFillIn() {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```


Allows filling forms in file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getScreenReaders() {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```


Allows to reader on screen only.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getAssembly() {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```


Allows assemblying file.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getAllowAll() {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```


All allowed.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
### getForbidAll() {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```


All Forbidded.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege element
