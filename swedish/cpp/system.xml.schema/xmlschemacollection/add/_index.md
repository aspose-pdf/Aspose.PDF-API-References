---
title: "System::Xml::Schema::XmlSchemaCollection::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaCollection::Add metod. Lägger till XmlSchema i samlingen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method


Lägger till [XmlSchema](../../xmlschema/) i samlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Den [XmlSchema](../../xmlschema/) att lägga till i samlingen. |

### ReturnValue

[XmlSchema](../../xmlschema/) objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lägger till [XmlSchema](../../xmlschema/) i samlingen. Den angivna [XmlResolver](../../../system.xml/xmlresolver/) används för att lösa eventuella externa referenser.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Den [XmlSchema](../../xmlschema/) att lägga till i samlingen. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include**- och **import**-element. Om detta är **nullptr** löses externa referenser inte. |

### ReturnValue

[XmlSchema](../../xmlschema/) som lagts till i schemasamlingen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method


Lägger till alla namnrymder som definierats i den angivna samlingen (inklusive deras associerade scheman) till denna samling.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchemaCollection\>\& | [XmlSchemaCollection](../) som du vill lägga till i den här samlingen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaCollection](../)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method


Lägger till schemat som finns i [XmlReader](../../../system.xml/xmlreader/) i schemasamlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const String\& | Namnutrymmes-URI som är associerad med schemat. För XML-scheman kommer detta vanligtvis att vara **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) som innehåller schemat att lägga till. |

### ReturnValue

[XmlSchema](../../xmlschema/) som lagts till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lägger till schemat som finns i [XmlReader](../../../system.xml/xmlreader/) i schemasamlingen. Den angivna [XmlResolver](../../../system.xml/xmlresolver/) används för att lösa eventuella externa resurser.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const String\& | Namnutrymmes-URI som är associerad med schemat. För XML-scheman kommer detta vanligtvis att vara **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) som innehåller schemat att lägga till. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include**- och **import**-element eller **x-schema**-attribut (XDR-scheman). Om detta är **nullptr** löses externa referenser inte. |

### ReturnValue

[XmlSchema](../../xmlschema/) som lagts till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const String\&) method


Lägger till schemat som finns på den angivna URL:en i schemasamlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const String\& | Namnutrymmes-URI som är associerad med schemat. För XML-scheman kommer detta vanligtvis att vara **targetNamespace**. |
| uri | const String\& | URL:en som specificerar schemat att läsa in. |

### ReturnValue

[XmlSchema](../../xmlschema/) som lagts till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
