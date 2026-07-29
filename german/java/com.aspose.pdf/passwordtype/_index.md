---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Dieses Enum stellt bekannte Passworttypen dar, die für passwortgeschützte PDF-Dokumente verwendet werden."
type: docs
weight: 3520
url: /de/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Dieses Enum stellt bekannte Passworttypen dar, die für passwortgeschützte PDF-Dokumente verwendet werden.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Inaccessible](#Inaccessible) | PDF-Dokument ist passwortgeschützt, aber sowohl Benutzer‑ als auch Eigentümerpasswort sind nicht leer und keines der Passwörter wurde definiert oder das angegebene Passwort war falsch. |
| [None](#None) | PDF-Dokument ist nicht passwortgeschützt. |
| [Owner](#Owner) | PDF-Dokument wurde mit dem Passwort zum Ändern von Berechtigungen (voller Zugriff) geöffnet. |
| [User](#User) | PDF-Dokument wurde mit dem Dokument‑Öffnen‑Passwort (eingeschränkter Zugriff) geöffnet. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

PDF-Dokument ist passwortgeschützt, aber sowohl Benutzer‑ als auch Eigentümerpasswort sind nicht leer und keines der Passwörter wurde definiert oder das angegebene Passwort war falsch.

### None {#None}
```
public static final PasswordType None
```

PDF-Dokument ist nicht passwortgeschützt.

### Owner {#Owner}
```
public static final PasswordType Owner
```

PDF-Dokument wurde mit dem Passwort zum Ändern von Berechtigungen (voller Zugriff) geöffnet.

### User {#User}
```
public static final PasswordType User
```

PDF-Dokument wurde mit dem Dokument‑Öffnen‑Passwort (eingeschränkter Zugriff) geöffnet.

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static PasswordType [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
