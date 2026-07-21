---
title: "Método System::Xml::XmlTextReader::LookupNamespace"
linktitle: "LookupNamespace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlTextReader::LookupNamespace. Resuelve un prefijo de espacio de nombres en el ámbito del elemento actual en C++."
type: docs
weight: 3700
url: /es/cpp/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace method


Resuelve un prefijo de espacio de nombres en el alcance del elemento actual.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | const String\& | El prefijo cuyo URI de espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase una cadena vacía. Esta cadena no tiene que estar atomizada. |

### ReturnValue

El URI de espacio de nombres al que se asigna el prefijo o **nullptr** si no se encuentra un prefijo coincidente.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
