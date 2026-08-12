---
title: "System::Xml::XmlNodeReader::MoveToAttribute método"
linktitle: "MoveToAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeReader::MoveToAttribute método. Se desplaza al atributo con el índice especificado en C++."
type: docs
weight: 2600
url: /es/cpp/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(int32_t) method


Se mueve al atributo con el índice especificado.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeIndex | int32_t | El índice del atributo. |

## Ver también

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String) method


Se mueve al atributo con el nombre especificado.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String, String) method


Se mueve al atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
