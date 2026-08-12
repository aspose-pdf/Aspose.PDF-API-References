---
title: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class"
linktitle: "HiddenDataSanitizer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class. Representa una clase para sanitizar datos ocultos en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/
---
## HiddenDataSanitizer class


Representa una clase para sanitizar datos ocultos.

```cpp
class HiddenDataSanitizer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [HiddenDataSanitizer](./hiddendatasanitizer/)(const System::SharedPtr\<HiddenDataSanitizationOptions\>\&) | Proporciona funcionalidad para sanitizar datos ocultos de un documento PDF, asegurando que la información sensible o innecesaria como metadatos, anotaciones, JavaScripts o contenido privado sea eliminada o transformada. |
| [Sanitize](./sanitize/)(const System::SharedPtr\<Document\>\&) | Sanitiza un documento PDF dado eliminando o transformando datos ocultos. |
| static [SanitizeAllToImages](./sanitizealltoimages/)(const System::SharedPtr\<Document\>\&, int32_t) | Reemplaza el contenido de la página con imágenes y elimina otros datos ocultos. Permite eliminar texto oculto con un color de fondo, así como texto oculto bajo imágenes. También elimina completamente todos los elementos interactivos. El documento se convierte a imágenes tal cual, y luego se limpia de cualquier dato oculto restante. Si necesita limpiar primero y luego convertir, use el método de la clase principal. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
