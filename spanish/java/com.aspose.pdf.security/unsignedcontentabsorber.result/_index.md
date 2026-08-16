---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Encapsula el resultado de una operación que intenta extraer contenido no firmado de un documento PDF. Esta clase proporciona información sobre el éxito de la operación, detalles de."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Encapsula el resultado de una operación que intenta extraer contenido no firmado de un documento PDF. Esta clase proporciona información sobre el éxito de la operación, detalles del contenido no firmado, un mensaje que describe el resultado y el estado de cobertura de las firmas del documento.

## Métodos

| Método | Descripción |
| --- | --- |
| [getCoverage](#getCoverage--) | Obtiene un valor que indica hasta qué punto el documento está cubierto por firmas digitales válidas. |
| [getMessage](#getMessage--) | Obtiene un mensaje que describe el resultado de la operación. |
| [getSuccess](#getSuccess--) | Obtiene un valor que indica si la operación para recuperar contenido no firmado del documento fue exitosa. |
| [getUnsignedContent](#getUnsignedContent--) | Obtiene un contenido no firmado. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Obtiene un valor que indica hasta qué punto el documento está cubierto por firmas digitales válidas.

**Returns:**
un valor que indica hasta qué punto el documento está cubierto por firmas digitales válidas.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Obtiene un mensaje que describe el resultado de la operación.

**Returns:**
un mensaje que describe el resultado de la operación.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Obtiene un valor que indica si la operación para recuperar contenido no firmado del documento fue exitosa.

**Returns:**
un valor que indica si la operación para recuperar contenido no firmado del documento fue exitosa.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Obtiene un contenido no firmado.

**Returns:**
un contenido no firmado.
