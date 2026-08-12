---
title: "enum System::Xml::ConformanceLevel"
linktitle: "ConformanceLevel"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "enum System::Xml::ConformanceLevel. Especifica la cantidad de comprobación de entrada o salida que realizan los objetos XmlReader y XmlWriter en C++."
type: docs
weight: 4600
url: /es/cpp/system.xml/conformancelevel/
---
## ConformanceLevel enum


Especifica la cantidad de comprobación de entrada o salida que realizan los objetos [XmlReader](../xmlreader/) y [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | 0 | El objeto [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/) detecta automáticamente si debe realizarse una verificación a nivel de documento o a nivel de fragmento, y realiza la verificación adecuada. Si estás envolviendo otro objeto [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/), el objeto externo no realiza ninguna verificación de conformidad adicional. La verificación de conformidad se deja al objeto subyacente. |
| Fragment | 1 | Los datos XML son un [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), según lo define el W3C. Este nivel de conformidad representa un documento XML que puede no tener un elemento raíz pero que, de otro modo, está bien formado. Este nivel de verificación garantiza que la secuencia que se lee o escribe pueda ser consumida por cualquier procesador como una [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Los datos XML cumplen con las reglas de un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) bien formado, según lo define el W3C. Este nivel de verificación garantiza que la secuencia que se lee o escribe pueda ser consumida por cualquier procesador como un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
