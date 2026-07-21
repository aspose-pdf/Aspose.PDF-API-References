---
title: "System::Xml::Schema::XmlSeverityType enum"
linktitle: "XmlSeverityType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSeverityType enum. Representa la gravedad del evento de validación en C++."
type: docs
weight: 8100
url: /es/cpp/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum


Representa la gravedad del evento de validación.

```cpp
enum class XmlSeverityType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Error | 0 | Indica que se produjo un error de validación al validar el documento de instancia. Esto se aplica a definiciones de tipo de documento (DTDs) y esquemas de lenguaje de definición XML [Schema](../) (XSD). Las restricciones de validez del Consorcio de la World Wide [Web](../../system.web/) (W3C) se consideran errores. Si no se ha creado un controlador de eventos de validación, los errores lanzan una excepción. |
| Warning | 1 | Indica que se produjo un evento de validación que no es un error. Normalmente se emite una advertencia cuando no hay DTD, o XML [Schema](../) para validar un elemento o atributo particular. A diferencia de los errores, las advertencias no lanzan una excepción si no hay un controlador de eventos de validación. |

## Ver también

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
