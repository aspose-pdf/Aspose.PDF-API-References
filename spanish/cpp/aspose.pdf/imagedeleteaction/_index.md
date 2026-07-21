---
title: "Aspose::Pdf::ImageDeleteAction enum"
linktitle: "ImageDeleteAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::ImageDeleteAction enum. Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina en C++."
type: docs
weight: 24500
url: /es/cpp/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enum


Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina.

```cpp
enum class ImageDeleteAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| KeepContents | 0 | [Image](../image/) será eliminado de la colección. Si el contenido de la página contiene referencias a la imagen, no se eliminarán. [Document](../document/) puede quedar inválido. |
| None | 1 | [Image](../image/) será eliminado de la colección y del contenido de la página, pero el objeto de imagen no será borrado. El tamaño del archivo no disminuirá. |
| ForceDelete | 2 | [Image](../image/) será eliminado de la colección y el objeto de imagen será eliminado del documento. Si existen otras referencias al mismo objeto, el documento puede corromperse. |
| Check | 3 | [Image](../image/) será eliminado de la colección y el objeto de imagen será eliminado solo si no hay otras referencias a la imagen desde otras páginas. Esto puede requerir más tiempo en comparación con la opción ForceDelete. |

## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
