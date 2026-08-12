---
title: "Clase System::Collections::Specialized::NameValueCollection"
linktitle: "NameValueCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Specialized::NameValueCollection. Colección de claves String asociadas y valores String que pueden accederse tanto por la clave como por el índice en C++."
type: docs
weight: 200
url: /es/cpp/system.collections.specialized/namevaluecollection/
---
## NameValueCollection class


Colección de claves [String](../../system/string/) asociadas y valores [String](../../system/string/) que pueden accederse tanto por la clave como por el índice.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const String\&) override | Sobrescribir método [ICollection](../../system.collections/icollection/) - no implementado. |
| [Add](./add/)(const System::SharedPtr\<NameValueCollection\>\&) | Copia las entradas de la [NameValueCollection](./) especificada al actual. |
| virtual [Add](./add/)(const String\&, const String\&) | Agrega una entrada con el nombre y valor especificados. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Contains](./contains/)(const String\&) const override | Comprueba si el elemento está presente en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override | Copia los elementos de la colección en elementos de matriz existentes. |
| virtual [Get](./get/)(const String\&) | Obtiene los valores asociados con la clave especificada. |
| virtual [get_AllKeys](./get_allkeys/)() | Obtiene todas las claves. |
| [get_Count](./get_count/)() const override | Obtiene el número de pares clave/valor. |
| virtual [get_Keys](./get_keys/)() | Obtiene todas las claves. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través de la colección. |
| virtual [GetValues](./getvalues/)(const String\&) | Obtiene los valores asociados con la clave especificada. |
| [HasKeys](./haskeys/)() | Obtiene un valor que indica si la [NameValueCollection](./) contiene claves que no son nulas. |
| [idx_get](./idx_get/)(const String\&) | Obtiene el valor en el índice especificado. |
| [idx_set](./idx_set/)(const String\&, const String\&) | Establece el valor de una entrada. |
| [NameValueCollection](./namevaluecollection/)() | Inicializa una nueva instancia de la clase [NameValueCollection](./) que está vacía. |
| [NameValueCollection](./namevaluecollection/)(const System::SharedPtr\<NameValueCollection\>\&) | Copia las entradas de la [NameValueCollection](./) especificada a una nueva [NameValueCollection](./). |
| [Remove](./remove/)(const String\&) override | Elimina el elemento específico. |
| virtual [Set](./set/)(const String\&, const String\&) | Establece el valor de una entrada. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
