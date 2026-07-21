---
title: "Método System::Xml::XmlWriter::WriteStartElement"
linktitle: "WriteStartElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlWriter::WriteStartElement. Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado en C++."
type: docs
weight: 3200
url: /es/cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&) method


Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del elemento. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&) method


Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres dado.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del elemento. |
| ns | const String\& | El URI del espacio de nombres que se asociará con el elemento. Si este espacio de nombres ya está en alcance y tiene un prefijo asociado, el escritor escribe automáticamente también ese prefijo. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y el prefijo dados.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | const String\& | El prefijo de espacio de nombres del elemento. |
| localName | const String\& | El nombre local del elemento. |
| ns | const String\& | El URI del espacio de nombres que se asociará con el elemento. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
