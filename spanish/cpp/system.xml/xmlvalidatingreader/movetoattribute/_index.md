---
title: "Método System::Xml::XmlValidatingReader::MoveToAttribute"
linktitle: "MoveToAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlValidatingReader::MoveToAttribute. Se desplaza al atributo con el índice especificado en C++."
type: docs
weight: 3500
url: /es/cpp/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(int32_t) method


Se mueve al atributo con el índice especificado.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. |

## Ver también

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String, String) method


Se mueve al atributo con el nombre local y el Identificador Uniforme de Recursos (URI) de espacio de nombres especificados.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String) method


Se mueve al atributo con el nombre especificado.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
