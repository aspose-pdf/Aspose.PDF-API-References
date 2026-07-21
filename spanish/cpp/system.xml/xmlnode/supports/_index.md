---
title: "Método System::Xml::XmlNode::Supports"
linktitle: "Supports"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlNode::Supports. Prueba si la implementación DOM implementa una característica específica en C++."
type: docs
weight: 4400
url: /es/cpp/system.xml/xmlnode/supports/
---
## XmlNode::Supports method


Comprueba si la implementación DOM implementa una característica específica.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| característica | String | El nombre del paquete de la característica a probar. Este nombre no distingue entre mayúsculas y minúsculas. |
| versión | String | El número de versión del nombre del paquete a probar. Si la versión no se especifica (null), admitir cualquier versión de la característica hace que el método devuelva true. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Observaciones



La siguiente tabla describe las combinaciones que devuelven **true**. |||
|-|-|
| Funcionalidad | Versión |
| XML | 1.0 |
| XML | 2.0 |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
