---
title: "Clase Aspose::Pdf::Annotations::AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::AppearanceDictionary. Diccionario de apariencia de anotación que especifica cómo se presentará visualmente la anotación en la página en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class


[Annotation](../annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page.

```cpp
class AppearanceDictionary : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XForm>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XForm\>\&) override | Agregar formulario X para la clave especificada. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Agrega un par con clave y valor al diccionario. |
| [Clear](./clear/)() override | Elimina todos los elementos del diccionario. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) const override | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\&, int32_t) | Copia los elementos del diccionario a una Matriz, comenzando en un índice de Matriz particular. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) override | Copia los elementos de la ICollection a una Matriz, comenzando en un índice de Matriz particular. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos contenidos en el diccionario. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Obtiene un valor que indica si el diccionario tiene un tamaño fijo. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si el diccionario es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso al diccionario está sincronizado (seguro para subprocesos). |
| [get_Keys](./get_keys/)() const override | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [Keys](../) contains (N | R | Valores de D).state, donde N - apariencia normal, R - apariencia al pasar el cursor, D - apariencia presionada y state - el nombre del estado (p. ej. On, Off para casillas de verificación). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso al diccionario. |
| [get_Values](./get_values/)() const override | Obtiene la lista de los valores del diccionario. La colección de resultados contiene la lista de objetos [XForm](../../aspose.pdf/xform/). |
| [GetEnumerator](./getenumerator/)() override | Devuelve un objeto IDictionaryEnumerator para el diccionario. |
| [idx_get](./idx_get/)(const System::String\&) const override | Representa una forma conveniente de obtener flujos de apariencia. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XForm\>) override | Representa una forma conveniente de obtener flujos de apariencia. |
| [Remove](./remove/)(const System::String\&) override | Elimina la clave del diccionario. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Elimina el par clave/valor de la colección. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XForm\>\&) const override | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |
## Ver también

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
