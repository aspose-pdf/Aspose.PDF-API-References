---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna uppräkning representerar kända lösenordstyper som används för lösenordsskyddade PDF-dokument."
type: docs
weight: 3520
url: /sv/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Denna uppräkning representerar kända lösenordstyper som används för lösenordsskyddade PDF-dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Inaccessible](#Inaccessible) | Pdf-dokumentet är lösenordsskyddat men både användar- och ägarlösenorden är inte tomma och inget av lösenorden var definierat eller det angivna lösenordet var felaktigt. |
| [None](#None) | Pdf-dokumentet är inte lösenordsskyddat. |
| [Owner](#Owner) | Pdf-dokumentet öppnades med lösenord för att ändra behörigheter (full åtkomst). |
| [User](#User) | Pdf-dokumentet öppnades med lösenord för dokumentöppning (begränsad åtkomst). |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Pdf-dokumentet är lösenordsskyddat men både användar- och ägarlösenorden är inte tomma och inget av lösenorden var definierat eller det angivna lösenordet var felaktigt.

### None {#None}
```
public static final PasswordType None
```

Pdf-dokumentet är inte lösenordsskyddat.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Pdf-dokumentet öppnades med lösenord för att ändra behörigheter (full åtkomst).

### User {#User}
```
public static final PasswordType User
```

Pdf-dokumentet öppnades med lösenord för dokumentöppning (begränsad åtkomst).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static PasswordType [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
