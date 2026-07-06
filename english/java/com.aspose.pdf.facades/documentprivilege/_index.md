---
title: DocumentPrivilege
linktitle: DocumentPrivilege
second_title: Aspose.PDF for Java API Reference
description: "Represents the privileges for accessing Pdf file. Refer to{@code PdfFileSecurity}. There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a."
type: docs
weight: 110
url: /java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Represents the privileges for accessing Pdf file. Refer to{@code PdfFileSecurity}. There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Methods

| Method | Description |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Compares two {@code DocumentPrivilege} objects. |
| [equals](#equals-java.lang.Object-) | Indicates whether some other object is "equal to" this one. <p> The <code>equals</code> method implements an equivalence relation on non-null object references: <ul> <li>It is <i>reflexive</i>: for any non-null reference value <code>x</code>, <code>x.equals(x)</code> should return <code>true</code>. <li>It is <i>symmetric</i>: for any non-null reference values <code>x</code> and <code>y</code>, <code>x.equals(y)</code> should return <code>true</code> if and only if <code>y.equals(x)</code> returns <code>true</code>. <li>It is <i>transitive</i>: for any non-null reference values <code>x</code>, <code>y</code>, and <code>z</code>, if <code>x.equals(y)</code> returns <code>true</code> and <code>y.equals(z)</code> returns <code>true</code>, then <code>x.equals(z)</code> should return <code>true</code>. <li>It is <i>consistent</i>: for any non-null reference values <code>x</code> and <code>y</code>, multiple invocations of <tt>x.equals(y)</tt> consistently return <code>true</code> or consistently return <code>false</code>, provided no information used in <code>equals</code> comparisons on the objects is modified. <li>For any non-null reference value <code>x</code>, <code>x.equals(null)</code> should return <code>false</code>. </ul> <p> The <tt>equals</tt> method for class <code>Object</code> implements the most discriminating possible equivalence relation on objects; that is, for any non-null reference values <code>x</code> and <code>y</code>, this method returns <code>true</code> if and only if <code>x</code> and <code>y</code> refer to the same object (<code>x == y</code> has the value <code>true</code>). <p> Note that it is generally necessary to override the <tt>hashCode</tt> method whenever this method is overridden, so as to maintain the general contract for the <tt>hashCode</tt> method, which states that equal objects must have equal hash codes. |
| [getAllowAll](#getAllowAll--) | All allowed. |
| [getAssembly](#getAssembly--) | Allows assemblying file. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. If the property has a value of -1, then the level is undefined. |
| [getCopy](#getCopy--) | Allows copying file. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. If the property has a value of -1, then the level is undefined. |
| [getDegradedPrinting](#getDegradedPrinting--) | Allows degraded printing. |
| [getFillIn](#getFillIn--) | Allows filling forms in file. |
| [getForbidAll](#getForbidAll--) | All Forbidded. |
| [getModifyAnnotations](#getModifyAnnotations--) | Allows modifying annotations of file. |
| [getModifyContents](#getModifyContents--) | Allows modifying file. |
| [getPrint](#getPrint--) | Allows printing file. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. If the property has a value of -1, then the level is undefined. |
| [getScreenReaders](#getScreenReaders--) | Allows to reader on screen only. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Returns a hash code value for the object. This method is supported for the benefit of hashtables such as those provided by <code>java.util.Hashtable</code>. <p> The general contract of <code>hashCode</code> is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the <tt>hashCode</tt> method must consistently return the same integer, provided no information used in <tt>equals</tt> comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the <tt>equals(Object)</tt> method, then calling the <code>hashCode</code> method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the <tt>hashCode</tt> method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hashtables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class <tt>Object</tt> does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.) |
| [isAllowAssembly](#isAllowAssembly--) | Sets the permission which allow assembly or not. true is allow and false is forbidden. |
| [isAllowCopy](#isAllowCopy--) | Sets the permission which allow copy or not. true is allow and false is forbidden. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Sets the permission which allow degraded printing or not. true is allow and false is forbidden. When set, printing will be limited to a low-level representation of the appearance, possibly of degraded quality. |
| [isAllowFillIn](#isAllowFillIn--) | Sets the permission which allow fill in forms or not. true is allow and false is forbidden. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Sets the permission which allow modify annotations or not. true is allow and false is forbidden. |
| [isAllowModifyContents](#isAllowModifyContents--) | Sets the permission which allow modify contents or not. true is allow and false is forbidden. |
| [isAllowPrint](#isAllowPrint--) | Sets the permission which allow print or not. true is allow and false is forbidden. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Sets the permission which allow screen readers or not. true is allow and false is forbidden. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Sets the permission which allow assembly or not. true is allow and false is forbidden. |
| [setAllowCopy](#setAllowCopy-boolean-) | Sets the permission which allow copy or not. true is allow and false is forbidden. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Sets the permission which allow degraded printing or not. true is allow and false is forbidden. When set, printing will be limited to a low-level representation of the appearance, possibly of degraded quality. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Sets the permission which allow fill in forms or not. true is allow and false is forbidden. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Sets the permission which allow modify annotations or not. true is allow and false is forbidden. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Sets the permission which allow modify contents or not. true is allow and false is forbidden. |
| [setAllowPrint](#setAllowPrint-boolean-) | Sets the permission which allow print or not. true is allow and false is forbidden. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Sets the permission which allow screen readers or not. true is allow and false is forbidden. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. If the property has a value of -1, then the level is undefined. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. If the property has a value of -1, then the level is undefined. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. If the property has a value of -1, then the level is undefined. |

### compareTo {#compareTo-java.lang.Object-}
Compares two {@code DocumentPrivilege} objects.

### equals {#equals-java.lang.Object-}
Indicates whether some other object is "equal to" this one. <p> The <code>equals</code> method implements an equivalence relation on non-null object references: <ul> <li>It is <i>reflexive</i>: for any non-null reference value <code>x</code>, <code>x.equals(x)</code> should return <code>true</code>. <li>It is <i>symmetric</i>: for any non-null reference values <code>x</code> and <code>y</code>, <code>x.equals(y)</code> should return <code>true</code> if and only if <code>y.equals(x)</code> returns <code>true</code>. <li>It is <i>transitive</i>: for any non-null reference values <code>x</code>, <code>y</code>, and <code>z</code>, if <code>x.equals(y)</code> returns <code>true</code> and <code>y.equals(z)</code> returns <code>true</code>, then <code>x.equals(z)</code> should return <code>true</code>. <li>It is <i>consistent</i>: for any non-null reference values <code>x</code> and <code>y</code>, multiple invocations of <tt>x.equals(y)</tt> consistently return <code>true</code> or consistently return <code>false</code>, provided no information used in <code>equals</code> comparisons on the objects is modified. <li>For any non-null reference value <code>x</code>, <code>x.equals(null)</code> should return <code>false</code>. </ul> <p> The <tt>equals</tt> method for class <code>Object</code> implements the most discriminating possible equivalence relation on objects; that is, for any non-null reference values <code>x</code> and <code>y</code>, this method returns <code>true</code> if and only if <code>x</code> and <code>y</code> refer to the same object (<code>x == y</code> has the value <code>true</code>). <p> Note that it is generally necessary to override the <tt>hashCode</tt> method whenever this method is overridden, so as to maintain the general contract for the <tt>hashCode</tt> method, which states that equal objects must have equal hash codes.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

All allowed.

**Returns:**
DocumentPrivilege element

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Allows assemblying file.

**Returns:**
DocumentPrivilege element

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. If the property has a value of -1, then the level is undefined.

**Returns:**
int value

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Allows copying file.

**Returns:**
DocumentPrivilege element

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. If the property has a value of -1, then the level is undefined.

**Returns:**
int value

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Allows degraded printing.

**Returns:**
DocumentPrivilege element

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Allows filling forms in file.

**Returns:**
DocumentPrivilege element

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

All Forbidded.

**Returns:**
DocumentPrivilege element

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Allows modifying annotations of file.

**Returns:**
DocumentPrivilege element

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Allows modifying file.

**Returns:**
DocumentPrivilege element

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Allows printing file.

**Returns:**
DocumentPrivilege element

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. If the property has a value of -1, then the level is undefined.

**Returns:**
int value

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Allows to reader on screen only.

**Returns:**
DocumentPrivilege element

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Returns a hash code value for the object. This method is supported for the benefit of hashtables such as those provided by <code>java.util.Hashtable</code>. <p> The general contract of <code>hashCode</code> is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the <tt>hashCode</tt> method must consistently return the same integer, provided no information used in <tt>equals</tt> comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the <tt>equals(Object)</tt> method, then calling the <code>hashCode</code> method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the <tt>hashCode</tt> method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hashtables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class <tt>Object</tt> does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.)

**Returns:**
a hash code value for this object. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Sets the permission which allow assembly or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Sets the permission which allow copy or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Sets the permission which allow degraded printing or not. true is allow and false is forbidden. When set, printing will be limited to a low-level representation of the appearance, possibly of degraded quality.

**Returns:**
boolean value

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Sets the permission which allow fill in forms or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Sets the permission which allow modify annotations or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Sets the permission which allow modify contents or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Sets the permission which allow print or not. true is allow and false is forbidden.

**Returns:**
boolean value

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Sets the permission which allow screen readers or not. true is allow and false is forbidden.

**Returns:**
boolean value

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Sets the permission which allow assembly or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Sets the permission which allow copy or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Sets the permission which allow degraded printing or not. true is allow and false is forbidden. When set, printing will be limited to a low-level representation of the appearance, possibly of degraded quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Sets the permission which allow fill in forms or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Sets the permission which allow modify annotations or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Sets the permission which allow modify contents or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Sets the permission which allow print or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Sets the permission which allow screen readers or not. true is allow and false is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. If the property has a value of -1, then the level is undefined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. If the property has a value of -1, then the level is undefined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. If the property has a value of -1, then the level is undefined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
