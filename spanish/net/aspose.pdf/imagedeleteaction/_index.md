---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Enum ImageDeleteAction de Aspose.Pdf. Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina
type: docs
weight: 5870
url: /es/net/aspose.pdf/imagedeleteaction/
---
## Enumeración ImageDeleteAction

Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina

```csharp
public enum ImageDeleteAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| KeepContents | `0` | La imagen será eliminada de la colección. Si el contenido de la página contiene referencias a la imagen, no serán eliminadas. El documento puede volverse inválido. |
| None | `1` | La imagen será eliminada de la colección y del contenido de la página, pero el objeto de imagen no será eliminado. El tamaño del archivo no disminuirá. |
| ForceDelete | `2` | La imagen será eliminada de la colección y el objeto de imagen será eliminado del documento. Si existen otras referencias al mismo objeto, el documento puede quedar dañado. |
| Check | `3` | La imagen será eliminada de la colección y el objeto de imagen será eliminado solo si no hay otras referencias a la imagen desde otras páginas. Esto puede requerir más tiempo en comparación con la opción ForceDelete. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)