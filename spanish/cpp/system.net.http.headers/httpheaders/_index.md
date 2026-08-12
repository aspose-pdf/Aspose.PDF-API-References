---
title: "Clase System::Net::Http::Headers::HttpHeaders"
linktitle: "HttpHeaders"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::HttpHeaders. La colección de los encabezados HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.net.http.headers/httpheaders/
---
## HttpHeaders class


La colección de los encabezados HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpHeaders : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Collections::Generic::IEnumerable<System::String>>>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Valida un nuevo par nombre-valor y lo agrega a la colección actual. |
| [Add](./add/)(String, String) | Valida un nuevo par nombre-valor y lo agrega a la colección actual. |
| virtual [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) | Concatena la instancia especificada de HttpHeaders con la actual. |
| [AddParsedValue](./addparsedvalue/)(String, System::SharedPtr\<Object\>) | Obtiene un encabezado por el nombre especificado y agrega un valor analizado al encabezado. |
| [Clear](./clear/)() | Elimina todos los elementos de la colección. |
| [Contains](./contains/)(String) |  |
| [ContainsParsedValue](./containsparsedvalue/)(String, System::SharedPtr\<Object\>) | Comprueba si el encabezado contiene el valor especificado. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [GetHeaderString](./getheaderstring/)(String) | Devuelve una representación en cadena de los valores por el nombre de encabezado especificado. |
| [GetHeaderString](./getheaderstring/)(String, System::SharedPtr\<Object\>) | Devuelve una representación en cadena de los valores por el nombre de encabezado especificado. |
| [GetHeaderStrings](./getheaderstrings/)() | Devuelve una colección que contiene representaciones en cadena de los valores de los encabezados. |
| [GetParsedValues](./getparsedvalues/)(String) | Devuelve los valores analizados por el nombre de encabezado especificado. |
| [GetValues](./getvalues/)(String) | Devuelve los valores correspondientes por el nombre especificado. |
| static [ParsedValuesAsList](./parsedvaluesaslist/)(const System::SharedPtr\<Object\>) | Convierte los valores analizados a una lista. |
| [Remove](./remove/)(String) | Intenta eliminar un elemento por el nombre especificado. |
| [RemoveParsedValue](./removeparsedvalue/)(String, System::SharedPtr\<Object\>) | Obtiene un encabezado por el nombre especificado y elimina un valor analizado del encabezado. |
| [SetConfiguration](./setconfiguration/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, System::SharedPtr\<HttpHeaderParser\>\>\>, System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) |  |
| [SetOrRemoveParsedValue](./setorremoveparsedvalue/)(String, System::SharedPtr\<Object\>) | Obtiene un encabezado por el nombre especificado y establece o elimina su valor. El valor del encabezado se eliminará cuando el parámetro 'value' sea nullptr, de lo contrario se establecerá un valor analizado. |
| [SetParsedValue](./setparsedvalue/)(String, System::SharedPtr\<Object\>) | Obtiene un encabezado por el nombre especificado y establece un valor analizado en el encabezado. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, String) | Intenta agregar un nuevo par nombre-valor a la colección actual. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Agrega una colección de pares nombre-valor a la colección actual. |
| [TryGetValues](./trygetvalues/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) | Intenta obtener los valores correspondientes por el nombre especificado. |
| [TryParseAndAddValue](./tryparseandaddvalue/)(String, String) | Intenta analizar el valor especificado y agregarlo a los valores de encabezado. |
## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
