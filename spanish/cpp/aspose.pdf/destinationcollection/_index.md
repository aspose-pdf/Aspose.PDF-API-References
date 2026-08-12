---
title: "Aspose::Pdf::DestinationCollection class"
linktitle: "DestinationCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DestinationCollection class. La clase representa la colección de todas las destinaciones (un árbol de nombres que asigna cadenas de nombres a destinaciones (ver 12.3.2.3, \"Named Destinations\") y (ver 7.7.4, \"Name Dictionary\")) en el documento PDF en C++."
type: docs
weight: 3500
url: /es/cpp/aspose.pdf/destinationcollection/
---
## DestinationCollection class


Clase que representa la colección de todos los destinos (un árbol de nombres que asigna cadenas de nombres a destinos (ver 12.3.2.3, "Destinos con nombre") y (ver 7.7.4, "Diccionario de nombres")) en el documento pdf.

```cpp
class DestinationCollection : public System::Collections::Generic::ICollection<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Object>>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Agrega el elemento especificado. [Collection](../collection/) es de solo lectura. Siempre lanza una excepción NotSupportedException. |
| [Clear](./clear/)() override | [Collection](../collection/) es de solo lectura. Siempre lanza una excepción NotSupportedException. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) const override | Determina si esta instancia contiene el objeto. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\>, int32_t) override | Copia los elementos de la colección a una matriz, comenzando en un índice de matriz específico. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos contenidos en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador. |
| [GetExplicitDestination](./getexplicitdestination/)(const System::String\&, bool) | Devuelve el destino explícito por el nombre. |
| [GetPageNumber](./getpagenumber/)(const System::String\&, bool) | Devuelve el número de página del destino por el nombre. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el objeto de destino por índice. |
| [IndexOf](./indexof/)(System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>) const | Devuelve el índice del destino en la colección. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Elimina el elemento especificado. [Collection](../collection/) es de solo lectura. Siempre lanza la excepción NotSupportedException. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
