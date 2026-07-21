---
title: "Clase Aspose::Pdf::Metadata"
linktitle: "Metadata"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Metadata. Proporciona acceso al flujo de metadatos XMP en C++."
type: docs
weight: 11200
url: /es/cpp/aspose.pdf/metadata/
---
## Metadata class


Proporciona acceso al flujo de metadatos XMP.

```cpp
class Metadata : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Agrega un valor a los metadatos. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Agrega un valor a los metadatos. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Agrega la extensión pdf a los metadatos. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Agrega un par con clave y valor al diccionario. |
| [Clear](./clear/)() override | Borra los metadatos. |
| [Contains](./contains/)(const System::String\&) const | Comprueba si la clave está contenida en los metadatos. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Copia los elementos de la colección en una matriz. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de elementos en la colección. |
| [get_ExtensionFields](./get_extensionfields/)() | Obtiene el diccionario de campos de extensión. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Comprueba si la colección tiene tamaño fijo. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Comprueba si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Comprueba si la colección está sincronizada. |
| [get_Keys](./get_keys/)() const override | Obtiene la colección de claves de metadatos. |
| [get_NamespaceManager](./get_namespacemanager/)() | Obtiene el administrador de espacios de nombres. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto de sincronización de la colección. |
| [get_Values](./get_values/)() const override | Obtiene los valores en los metadatos. |
| [GetEnumerator](./getenumerator/)() override | Devuelve enumerador del diccionario. |
| [GetNamespaceUriByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Devuelve el URI del espacio de nombres por prefijo. |
| [GetPrefixByNamespaceUri](./getprefixbynamespaceuri/)(const System::String\&) | Devuelve el prefijo por URI del espacio de nombres. |
| [idx_get](./idx_get/)(const System::String\&) const override | Obtiene datos de los metadatos. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Establece datos de los metadatos. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&) | Registra el URI del espacio de nombres. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&, const System::String\&) | Registra el URI del espacio de nombres. |
| [Remove](./remove/)(const System::String\&) override | Elimina la entrada de los metadatos. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Elimina el par clave/valor de la colección. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |
## Ver también

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
