---
title: PasswordType
linktitle: PasswordType
second_title: Aspose.PDF for Java API Reference
description: This enum represents known password types used for password protected pdf documents.
type: docs
weight: 3520
url: /java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

This enum represents known password types used for password protected pdf documents.

## Fields

| Field | Description |
| --- | --- |
| [Inaccessible](#Inaccessible) | Pdf document is password protected but both user and owner passwords are not empty and none of the passwords was defined or supplied password was incorrect. |
| [None](#None) | Pdf document is not password protected. |
| [Owner](#Owner) | Pdf document was opened using change permissions password (full access). |
| [User](#User) | Pdf document was opened using document open password (restricted access). |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Pdf document is password protected but both user and owner passwords are not empty and none of the passwords was defined or supplied password was incorrect.

### None {#None}
```
public static final PasswordType None
```

Pdf document is not password protected.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Pdf document was opened using change permissions password (full access).

### User {#User}
```
public static final PasswordType User
```

Pdf document was opened using document open password (restricted access).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static PasswordType [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
