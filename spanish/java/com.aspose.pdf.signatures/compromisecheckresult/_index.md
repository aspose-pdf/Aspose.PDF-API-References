---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para comprobar la posible vulnerabilidad de las firmas digitales del documento."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Representa una clase para comprobar la posible vulnerabilidad de las firmas digitales del documento.

## Campos

| Campo | Descripción |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Obtiene una colección de firmas digitales que han sido identificadas como comprometidas. Esta propiedad contiene la lista de todas las firmas comprometidas detectadas en el documento. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Obtiene el estado de cobertura de firmas digitales en un documento. Si es igual a {@code SignaturesCoverage#Undefined}, entonces una de las firmas está comprometida. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indica si hay alguna firma digital comprometida en el documento. Devuelve true si al menos una firma está comprometida; de lo contrario, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Obtiene una colección de firmas digitales que han sido identificadas como comprometidas. Esta propiedad contiene la lista de todas las firmas comprometidas detectadas en el documento.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Obtiene el estado de cobertura de firmas digitales en un documento. Si es igual a {@code SignaturesCoverage#Undefined}, entonces una de las firmas está comprometida.

**Returns:**
Elemento SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indica si hay alguna firma digital comprometida en el documento. Devuelve true si al menos una firma está comprometida; de lo contrario, false.

**Returns:**
valor booleano
