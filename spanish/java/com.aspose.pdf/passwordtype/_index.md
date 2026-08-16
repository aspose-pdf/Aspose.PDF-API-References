---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Este enum representa los tipos de contraseña conocidos utilizados para documentos PDF protegidos con contraseña."
type: docs
weight: 3520
url: /es/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Este enum representa los tipos de contraseña conocidos utilizados para documentos PDF protegidos con contraseña.

## Campos

| Campo | Descripción |
| --- | --- |
| [Inaccessible](#Inaccessible) | El documento PDF está protegido con contraseña, pero ambas contraseñas de usuario y propietario no están vacías y ninguna de las contraseñas fue definida o la contraseña suministrada era incorrecta. |
| [None](#None) | El documento PDF no está protegido con contraseña. |
| [Owner](#Owner) | El documento PDF se abrió usando la contraseña de cambio de permisos (acceso completo). |
| [User](#User) | El documento PDF se abrió usando la contraseña de apertura del documento (acceso restringido). |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

El documento PDF está protegido con contraseña, pero ambas contraseñas de usuario y propietario no están vacías y ninguna de las contraseñas fue definida o la contraseña suministrada era incorrecta.

### None {#None}
```
public static final PasswordType None
```

El documento PDF no está protegido con contraseña.

### Owner {#Owner}
```
public static final PasswordType Owner
```

El documento PDF se abrió usando la contraseña de cambio de permisos (acceso completo).

### User {#User}
```
public static final PasswordType User
```

El documento PDF se abrió usando la contraseña de apertura del documento (acceso restringido).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static PasswordType [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
