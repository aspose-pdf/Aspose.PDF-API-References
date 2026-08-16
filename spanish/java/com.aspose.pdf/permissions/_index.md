---
title: "Permisos"
linktitle: "Permisos"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Bandera binaria Este enum representa los permisos del usuario para un pdf."
type: docs
weight: 3830
url: /es/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Bandera binaria Este enum representa los permisos del usuario para un pdf.

## Campos

| Campo | Descripción |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Controladores de seguridad de la revisión 3 o superior) Ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si {@code ModifyContent} está desactivado. |
| [ExtractContent](#ExtractContent) | (Controladores de seguridad de la revisión 2) Copiar o extraer de otro modo texto y gráficos del documento, incluida la extracción de texto y gráficos (para apoyar la accesibilidad de usuarios con discapacidades o para otros fines). (Controladores de seguridad de la revisión 3 o superior) Copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a las controladas por {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Controladores de seguridad de la revisión 3 o superior) Extraer texto y gráficos (para apoyar la accesibilidad de usuarios con discapacidades o para otros fines). |
| [FillForm](#FillForm) | (Controladores de seguridad de la revisión 3 o superior) Rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si {@code ModifyTextAnnotations} está desactivado. |
| [ModifyContent](#ModifyContent) | Modificar el contenido del documento mediante operaciones distintas a las controladas por {@code ModifyTextAnnotations}, {@code FillForm} y 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Agregar o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si {@code ModifyContent} también está habilitado, crear o modificar campos de formulario interactivo (incluidos los campos de firma). |
| [PrintDocument](#PrintDocument) | (Controladores de seguridad de la revisión 2) Imprimir el documento. (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento (posiblemente no al nivel de mayor calidad, dependiendo de si {@code PrintingQuality} también está habilitado). |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Controladores de seguridad de la revisión 3 o superior) Ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si {@code ModifyContent} está desactivado.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Controladores de seguridad de la revisión 2) Copiar o extraer de otro modo texto y gráficos del documento, incluida la extracción de texto y gráficos (para apoyar la accesibilidad de usuarios con discapacidades o para otros fines). (Controladores de seguridad de la revisión 3 o superior) Copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a las controladas por {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Controladores de seguridad de la revisión 3 o superior) Extraer texto y gráficos (para apoyar la accesibilidad de usuarios con discapacidades o para otros fines).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Controladores de seguridad de la revisión 3 o superior) Rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si {@code ModifyTextAnnotations} está desactivado.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modificar el contenido del documento mediante operaciones distintas a las controladas por {@code ModifyTextAnnotations}, {@code FillForm} y 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Agregar o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si {@code ModifyContent} también está habilitado, crear o modificar campos de formulario interactivo (incluidos los campos de firma).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Controladores de seguridad de la revisión 2) Imprimir el documento. (Controladores de seguridad de la revisión 3 o superior) Imprimir el documento (posiblemente no al nivel de mayor calidad, dependiendo de si {@code PrintingQuality} también está habilitado).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.
