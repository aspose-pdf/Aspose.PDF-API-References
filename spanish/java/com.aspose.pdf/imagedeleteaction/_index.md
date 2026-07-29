---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina"
type: docs
weight: 2290
url: /es/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina

## Campos

| Campo | Descripción |
| --- | --- |
| [Check](#Check) | La imagen se eliminará de la colección y el objeto de imagen se eliminará solo si no hay otras referencias a la imagen desde otras páginas. Esto puede requerir más tiempo en comparación con la opción ForceDelete. |
| [ForceDelete](#ForceDelete) | La imagen se eliminará de la colección y el objeto de imagen se eliminará del documento. Si existen otras referencias al mismo objeto, el documento puede quedar corrupto. |
| [KeepContents](#KeepContents) | La imagen se eliminará de la colección. Si el contenido de la página contiene referencias a la imagen, no se eliminarán. El documento puede quedar inválido. |
| [None](#None) | La imagen se eliminará de la colección y del contenido de la página, pero el objeto de imagen no se eliminará. El tamaño del archivo no se reducirá. |

### Check {#Check}
```
public static final int Check
```

La imagen se eliminará de la colección y el objeto de imagen se eliminará solo si no hay otras referencias a la imagen desde otras páginas. Esto puede requerir más tiempo en comparación con la opción ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

La imagen se eliminará de la colección y el objeto de imagen se eliminará del documento. Si existen otras referencias al mismo objeto, el documento puede quedar corrupto.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

La imagen se eliminará de la colección. Si el contenido de la página contiene referencias a la imagen, no se eliminarán. El documento puede quedar inválido.

### None {#None}
```
public static final int None
```

La imagen se eliminará de la colección y del contenido de la página, pero el objeto de imagen no se eliminará. El tamaño del archivo no se reducirá.
