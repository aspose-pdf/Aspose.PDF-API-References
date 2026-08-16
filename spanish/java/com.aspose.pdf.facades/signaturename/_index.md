---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para un nombre de firma. Representa un nombre de firma más preciso. Se usa en lugar de nombres de cadena. Permite presentar firmas con los mismos nombres de cadena."
type: docs
weight: 690
url: /es/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Representa una clase para un nombre de firma. Representa un nombre de firma más preciso. Se usa en lugar de nombres de cadena. Permite presentar firmas con los mismos nombres de cadena.

## Campos

| Campo | Descripción |
| --- | --- |
| [FullName](#FullName) | Obtiene el nombre completo de la firma, proporcionando un identificador único y preciso para el campo de firma. |
| [Name](#Name) | Obtiene el nombre de una firma. |

## Métodos

| Método | Descripción |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina si esta instancia y un objeto especificado son iguales. |
| [getSignatureDictionary](#getSignatureDictionary--) | Obtiene el diccionario de la firma. |
| [hashCode](#hashCode--) | Devuelve un código hash para esta instancia basado en la propiedad FullName. |
| [hasSignature](#hasSignature--) | Indica si la firma está presente o no. |
| [toString](#toString--) | Devuelve una representación en cadena de la instancia {@link SignatureName}, utilizando principalmente su nombre. |

### FullName {#FullName}
```
public final String FullName
```

Obtiene el nombre completo de la firma, proporcionando un identificador único y preciso para el campo de firma.

### Name {#Name}
```
public final String Name
```

Obtiene el nombre de una firma.

### equals {#equals-java.lang.Object-}
Determina si esta instancia y un objeto especificado son iguales.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Obtiene el diccionario de la firma.

**Returns:**
El diccionario de la firma o null si no se encuentra.

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un código hash para esta instancia basado en la propiedad FullName.

**Returns:**
Un entero que representa el código hash de la propiedad FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Indica si la firma está presente o no.

**Returns:**
valor booleano

### toString {#toString--}
```
public String toString()
```

Devuelve una representación en cadena de la instancia {@link SignatureName}, utilizando principalmente su nombre.

**Returns:**
Una cadena que representa el nombre de la firma.
