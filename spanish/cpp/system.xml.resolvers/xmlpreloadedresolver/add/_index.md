---
title: "Método System::Xml::Resolvers::XmlPreloadedResolver::Add"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Resolvers::XmlPreloadedResolver::Add. Agrega una matriz de bytes al almacén XmlPreloadedResolver y la asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method


Agrega una matriz de bytes al almacén [XmlPreloadedResolver](../) y la asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| valor | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes con los datos que corresponden al URI proporcionado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Agrega una matriz de bytes al almacén [XmlPreloadedResolver](../) y la asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| valor | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes con los datos que corresponden al URI proporcionado. |
| desplazamiento | int32_t | El desplazamiento en la matriz de bytes proporcionada donde comienzan los datos. |
| count | int32_t | El número de bytes a leer de la matriz de bytes, comenzando en el desplazamiento proporcionado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method


Agrega un Stream al almacén [XmlPreloadedResolver](../) y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| valor | const SharedPtr\<IO::Stream\>\& | Un Stream con los datos que corresponden al URI proporcionado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method


Agrega una cadena con datos precargados al almacén [XmlPreloadedResolver](../) y la asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| value | const String\& | Una [String](../../../system/string/) con los datos que corresponden al URI proporcionado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
