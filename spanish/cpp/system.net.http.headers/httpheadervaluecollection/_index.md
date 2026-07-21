---
title: "System::Net::Http::Headers::HttpHeaderValueCollection clase"
linktitle: "HttpHeaderValueCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::HttpHeaderValueCollection. Representa la colección de los valores de los encabezados. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.net.http.headers/httpheadervaluecollection/
---
## HttpHeaderValueCollection class


Representa la colección de los valores de los encabezados. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class HttpHeaderValueCollection : public System::Collections::Generic::ICollection<T>
```


| Parámetro | Descripción |
| --- | --- |
| El | tipo de los valores de los encabezados representado en la colección. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const T\&) override | Agrega un elemento a la colección. |
| [Clear](./clear/)() override | Elimina todos los elementos de la colección. |
| [Contains](./contains/)(const T\&) const override | Comprueba si el elemento está presente en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Copia todos los elementos de la colección a los elementos existentes del arreglo. |
| [get_Count](./get_count/)() const override | Información RTTI. |
| [get_IsReadOnly](./get_isreadonly/)() | Obtiene un valor que indica si la colección actual es de solo lectura. |
| [get_IsSpecialValueSet](./get_isspecialvalueset/)() | Obtiene un valor que indica si la colección actual contiene un "valor especial". |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [GetHeaderStringWithoutSpecial](./getheaderstringwithoutspecial/)() | Devuelve una representación en cadena de la colección actual sin un "valor especial". |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>) | Construye una nueva instancia. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Construye una nueva instancia. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T) | Construye una nueva instancia. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Construye una nueva instancia. |
| [ParseAdd](./parseadd/)(String) | Analiza una representación en cadena de un encabezado y lo agrega a la colección actual. |
| [Remove](./remove/)(const T\&) override | Elimina el elemento de la colección. |
| [RemoveSpecialValue](./removespecialvalue/)() | Elimina un "valor especial". |
| [SetSpecialValue](./setspecialvalue/)() | Establece un "valor especial". |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [TryParseAdd](./tryparseadd/)(String) | Intenta analizar una representación en cadena de un encabezado y agregarla a la colección actual. |

## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
