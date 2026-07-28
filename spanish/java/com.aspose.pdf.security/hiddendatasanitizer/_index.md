---
title: "HiddenDataSanitizer"
linktitle: "HiddenDataSanitizer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para sanitizar datos ocultos."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

Representa una clase para sanitizar datos ocultos.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | Proporciona funcionalidad para sanitizar datos ocultos de un documento PDF, asegurando que información sensible o innecesaria como metadatos, anotaciones, JavaScripts o contenido privado sea eliminada o transformada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | Sanitiza un documento PDF dado eliminando o transformando datos ocultos. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. Además, elimina completamente todos los elementos interactivos. El documento se convierte en imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método principal de la clase. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. También elimina completamente todos los elementos interactivos. El documento se convierte en imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método principal de la clase. |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
Proporciona funcionalidad para sanitizar datos ocultos de un documento PDF, asegurando que información sensible o innecesaria como metadatos, anotaciones, JavaScripts o contenido privado sea eliminada o transformada.

### sanitize {#sanitize-com.aspose.pdf.Document-}
Sanitiza un documento PDF dado eliminando o transformando datos ocultos.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. Además, elimina completamente todos los elementos interactivos. El documento se convierte en imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método principal de la clase.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. También elimina completamente todos los elementos interactivos. El documento se convierte en imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método principal de la clase.
