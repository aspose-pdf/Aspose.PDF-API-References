---
title: "Clase Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent"
linktitle: "UnsignedContent"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent. Encapsula los elementos de contenido no firmado extraídos de un documento PDF. Esta clase proporciona acceso a páginas, campos de formulario, XForms y anotaciones que forman parte del contenido no firmado dentro del documento en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.security/unsignedcontentabsorber/unsignedcontent/
---
## UnsignedContent class


Encapsula los elementos de contenido no firmado extraídos de un documento PDF. Esta clase proporciona acceso a páginas, campos de formulario, XForms y anotaciones que forman parte del contenido no firmado dentro del documento.

```cpp
class UnsignedContent : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Annotations](./get_annotations/)() const | Obtiene un diccionario de anotaciones modificadas que pueden haber cambiado o haberse añadido. |
| [get_Forms](./get_forms/)() const | Obtiene los campos de formulario que se han modificado o añadido de forma incremental. |
| [get_Pages](./get_pages/)() const | Obtiene una lista de páginas cuyo contenido no está firmado o ha sido modificado de forma incremental. |
| [get_XForms](./get_xforms/)() const | Obtiene un diccionario de objetos [XForm](../../../aspose.pdf/xform/) modificados que pueden haber cambiado, aunque la página en sí no haya cambiado (no está en la lista de Pages). |
## Ver también

* Class [Object](../../../system/object/)
* Class [UnsignedContentAbsorber](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
