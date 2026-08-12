---
title: "System::Xml::XmlValidatingReader::LookupNamespace method"
linktitle: "LookupNamespace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlValidatingReader::LookupNamespace method. Resuelve un prefijo de espacio de nombres en el alcance del elemento actual'' en C++."
type: docs
weight: 3400
url: /es/cpp/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace method


Resuelve un prefijo de espacio de nombres en el alcance del elemento actual.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | const String\& | El prefijo cuyo Identificador Uniforme de Recursos (URI) de espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase una cadena vacía. |

### ReturnValue

El URI de espacio de nombres al que se asigna el prefijo o **nullptr** si no se encuentra un prefijo coincidente.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
