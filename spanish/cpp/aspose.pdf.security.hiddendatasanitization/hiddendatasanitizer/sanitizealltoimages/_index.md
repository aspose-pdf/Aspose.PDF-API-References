---
title: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages método"
linktitle: "SanitizeAllToImages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages método. Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. También elimina completamente todos los elementos interactivos. El documento se convierte en imágenes tal cual, y luego se limpian los datos ocultos restantes. Si necesita limpiar primero y luego convertir, use el método principal de la clase en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/sanitizealltoimages/
---
## HiddenDataSanitizer::SanitizeAllToImages method


Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. También elimina completamente todos los elementos interactivos. El documento se convierte a imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método de la clase principal.

```cpp
static void Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages(const System::SharedPtr<Document> &document, int32_t dpi=150)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | const System::SharedPtr\<Document\>\& | El objeto docunent. |
| dpi | int32_t | Los dpi de las imágenes de las páginas. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [HiddenDataSanitizer](../)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../../)
* Library [Aspose.PDF for C++](../../../)
