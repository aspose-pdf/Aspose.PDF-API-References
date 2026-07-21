---
title: "Aspose::Pdf::Facades::PdfXmpMetadata class"
linktitle: "PdfXmpMetadata"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfXmpMetadata class. Clase para manipular metadatos XMP en C++."
type: docs
weight: 3100
url: /es/cpp/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class


Clase para manipulación de metadatos XMP.

```cpp
class PdfXmpMetadata : public Aspose::Pdf::Facades::SaveableFacade,
                       public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Agrega un valor a los metadatos XMP. |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&, const System::String\&, const System::String\&, const System::String\&) | Agrega un campo de extensión a los metadatos. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Agrega un nuevo elemento al objeto diccionario. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Agrega un nuevo elemento al objeto diccionario. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Agrega un par con clave y valor al diccionario. |
| [Clear](./clear/)() override | Elimina todos los elementos del objeto. |
| [Contains](./contains/)(const System::String\&) const | Comprueba si el diccionario contiene la clave especificada. |
| [Contains](./contains/)(const DefaultMetadataProperties\&) const | Comprueba si el diccionario contiene la propiedad especificada. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Copia los metadatos en una matriz. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de elementos en la colección. |
| [get_ExtensionFields](./get_extensionfields/)() | Obtiene el diccionario de campos de extensión. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Devuelve true si la colección tiene tamaño fijo. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Devuelve true si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si la colección está sincronizada. |
| [get_Keys](./get_keys/)() const override | Obtiene las claves del diccionario. |
| [get_Values](./get_values/)() const override | Obtiene la colección de valores del diccionario. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el objeto enumerador del diccionario. |
| [GetNamespaceURIByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Obtiene el URI del espacio de nombres por prefijo. |
| [GetPrefixByNamespaceURI](./getprefixbynamespaceuri/)(const System::String\&) | Obtiene el prefijo por URI del espacio de nombres. |
| [GetXmpMetadata](./getxmpmetadata/)() | Obtiene el XmpMetadata del PDF de entrada en formato XML. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::String\&) | Obtiene una parte del XmpMetadata del PDF de entrada según un nombre de metadato. |
| [idx_get](./idx_get/)(const System::String\&) const override | Obtiene el valor por clave. |
| [idx_get](./idx_get/)(const DefaultMetadataProperties\&) const | Obtiene el valor de los metadatos XMP por clave. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Establece el valor por clave. |
| [idx_set](./idx_set/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Obtiene el valor de los metadatos XMP por clave. |
| [PdfXmpMetadata](./pdfxmpmetadata/)() | Constructor para [PdfXmpMetadata](./). |
| [PdfXmpMetadata](./pdfxmpmetadata/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfXmpMetadata](./) basado en el *documento*. |
| [RegisterNamespaceURI](./registernamespaceuri/)(const System::String\&, const System::String\&) | Registra el URI del espacio de nombres. |
| [Remove](./remove/)(DefaultMetadataProperties) | Elimina el elemento con la clave especificada. |
| [Remove](./remove/)(const System::String\&) override | Elimina la clave del diccionario. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Elimina el par clave/valor de la colección. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
