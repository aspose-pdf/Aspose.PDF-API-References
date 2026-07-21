---
title: "Aspose::Pdf::Facades::DefaultMetadataProperties enum"
linktitle: "DefaultMetadataProperties"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::DefaultMetadataProperties enum. Enumeración de propiedades XMP estándar en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.pdf.facades/defaultmetadataproperties/
---
## DefaultMetadataProperties enum


Enumeración de propiedades estándar XMP.

```cpp
enum class DefaultMetadataProperties
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Advisory | 0 | xmp:Advisory property. Una matriz no ordenada que especifica propiedades que fueron editadas fuera de la aplicación de autoría. Cada elemento debe contener un solo /// namespace y XPath separados por un espacio ASCII. |
| BaseURL | 1 | xmp:BaseURL property. La URL base para URLs relativas en el contenido del documento. Si este documento contiene enlaces a Internet, y esos enlaces son relativos, /// son relativos a esta URL base. Esta propiedad proporciona una forma estándar para que las URLs relativas incrustadas sean interpretadas por las herramientas. /// Las herramientas de autoría web deben establecer el valor basándose en su noción de dónde se interpretarán las URLs. |
| CreateDate | 2 | xmp:CreateDate property. La fecha y hora en que el recurso fue creado originalmente. |
| CreatorTool | 3 | xmp:CreatorTool property. El nombre de la primera herramienta conocida utilizada para crear el recurso. |
| Identifier | 4 | xmp:Identifier property. Una matriz no ordenada de cadenas de texto que identifican de manera inequívoca el recurso dentro de un contexto dado |
| MetadataDate | 5 | xmp:MetadataDate property. La fecha y hora en que cualquier metadato de este recurso fue modificado por última vez |
| ModifyDate | 6 | xmp:ModifyDate property. La fecha y hora en que el recurso fue modificado por última vez. |
| Nickname | 7 | xmp:Nickname property. Un nombre corto e informal para el recurso. |
| Thumbnails | 8 | xmp:Thumbnails property. Una matriz alternativa de imágenes en miniatura para un archivo, que pueden diferir en características como el tamaño o la codificación de la imagen. |

## Ver también

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
