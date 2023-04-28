---
title: PasswordType
second_title: Aspose.PDF for Java API Reference
description: This enum represents known password types used for password protected pdf documents.
type: docs
weight: 271
url: /java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PasswordType extends System.Enum
```

This enum represents known password types used for password protected pdf documents.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Pdf document is not password protected. |
| [User](#User) | Pdf document was opened using document open password (restricted access). |
| [Owner](#Owner) | Pdf document was opened using change permissions password (full access). |
| [Inaccessible](#Inaccessible) | Pdf document is password protected but both user and owner passwords are not empty and none of the passwords was defined or supplied password was incorrect. |
### None {#None}
```
public static final int None
```


Pdf document is not password protected.

### User {#User}
```
public static final int User
```


Pdf document was opened using document open password (restricted access).

### Owner {#Owner}
```
public static final int Owner
```


Pdf document was opened using change permissions password (full access).

### Inaccessible {#Inaccessible}
```
public static final int Inaccessible
```


Pdf document is password protected but both user and owner passwords are not empty and none of the passwords was defined or supplied password was incorrect. So it impossible to deduce the type of the password.

