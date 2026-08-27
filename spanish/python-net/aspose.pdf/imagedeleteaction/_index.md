---
title: "ImageDeleteAction"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina"
type: docs
weight: 6450
url: /es/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| KEEP_CONTENTS | La imagen será eliminada de la colección. Si el contenido de la página contiene referencias a la imagen, no se eliminarán. El documento podría quedar inválido. |
| NONE | La imagen será eliminada de la colección y del contenido de la página, pero el objeto imagen no será borrado. El tamaño del archivo no se reducirá. |
| FORCE_DELETE | La imagen será eliminada de la colección y el objeto imagen será eliminado del documento. Si existen otras referencias al mismo objeto, el documento podría corromperse. |
| CHECK | La imagen será eliminada de la colección y el objeto imagen será eliminado solo si no existen otras referencias a la imagen desde otras páginas. Esto puede requerir más tiempo en comparación con la opción ForceDelete. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

