---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa enum rappresenta i tipi di password noti utilizzati per i documenti PDF protetti da password."
type: docs
weight: 3520
url: /it/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Questa enum rappresenta i tipi di password noti utilizzati per i documenti PDF protetti da password.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Inaccessible](#Inaccessible) | Il documento PDF è protetto da password, ma entrambe le password utente e proprietario non sono vuote e nessuna delle password è stata definita o la password fornita era errata. |
| [None](#None) | Il documento PDF non è protetto da password. |
| [Owner](#Owner) | Il documento PDF è stato aperto utilizzando la password per modificare i permessi (accesso completo). |
| [User](#User) | Il documento PDF è stato aperto utilizzando la password di apertura del documento (accesso limitato). |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Il documento PDF è protetto da password, ma entrambe le password utente e proprietario non sono vuote e nessuna delle password è stata definita o la password fornita era errata.

### None {#None}
```
public static final PasswordType None
```

Il documento PDF non è protetto da password.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Il documento PDF è stato aperto utilizzando la password per modificare i permessi (accesso completo).

### User {#User}
```
public static final PasswordType User
```

Il documento PDF è stato aperto utilizzando la password di apertura del documento (accesso limitato).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static PasswordType [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
