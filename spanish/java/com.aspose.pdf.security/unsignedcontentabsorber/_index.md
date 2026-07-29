---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para extraer contenido no firmado de un archivo PDF gestionado por firmas digitales."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Representa una clase para extraer contenido no firmado de un archivo PDF gestionado por firmas digitales.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Representa una clase utilizada para procesar contenido no firmado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Intenta recuperar el contenido no firmado del documento asociado. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Representa una clase utilizada para procesar contenido no firmado.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Intenta recuperar el contenido no firmado del documento asociado.

**Returns:**
Un objeto {@link UnsignedContentAbsorber.Result} que contiene detalles sobre el contenido no firmado, la cobertura de firmas digitales, el estado de éxito de la operación y un mensaje informativo.
