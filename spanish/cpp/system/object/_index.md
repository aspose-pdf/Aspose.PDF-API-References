---
title: "Clase System::Object"
linktitle: "Objeto"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Object. Clase base que permite usar los métodos disponibles para la clase System.Object en C#. Todas las clases no triviales usadas con el entorno traducido deben heredarla en C++."
type: docs
weight: 5000
url: /es/cpp/system/object/
---
## Object class


Clase base que permite usar los métodos disponibles para la clase [System.Object](./) en C#. Todas las clases no triviales utilizadas con el entorno traducido deben heredarla.

```cpp
class Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Equals](./equals/)(ptr) | Compara objetos usando la semántica de C# [Object.Equals](./equals/). |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static [Equals](./equals/)(float const\&, float const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static [Equals](./equals/)(double const\&, double const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [GetCounter](./getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [GetHashCode](./gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](./gethashcode/). Permite generar hash de objetos personalizados. |
| virtual [GetType](./gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](./gettype/). |
| virtual [Is](./is/)(const TypeInfo\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| [Lock](./lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../lockcontext/). |
| virtual [MemberwiseClone](./memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](./memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](./object/)() | Crea un objeto. Inicializa todas las estructuras de datos internas. |
| [Object](./object/)(Object const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [operator=](./operator=/)(Object const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static [ReferenceEquals](./referenceequals/)(ptr const\&, ptr const\&) | Compara objetos por referencia. |
| static [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](./referenceequals/) para el caso de cadena y nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, String const\&) | Especialización de [Object::ReferenceEquals](./referenceequals/) para el caso de cadenas. |
| [RemovedSharedRefs](./removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| [SharedCount](./sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [SharedRefAdded](./sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [ToString](./tostring/)() const | Análogo al método C# [Object.ToString()](./tostring/). Permite convertir objetos personalizados a cadena. |
| static [Type](./type/)() | Implementa la construcción C# typeof([System.Object](./)). |
| [Unlock](./unlock/)() | Implementa el desbloqueo de la sentencia lock() de C#. Llámalo directamente o usa el objeto centinela [LockContext](../lockcontext/). |
| [WeakRefAdded](./weakrefadded/)() | Incrementa el contador de referencia débil. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [WeakRefRemoved](./weakrefremoved/)() | Decrementa el contador de referencia débil. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [~Object](./~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ptr](./ptr/) | Alias para el tipo de puntero inteligente. |
## Observaciones


Junto con los métodos disponibles en la clase C# [System.Object](./), también habilita soporte para algunos conceptos específicos del entorno de código traducido. Esto incluye el conteo de referencias usado por las clases de punteros inteligentes ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) y otros servicios relacionados con la gestión de memoria, depuración, etc.

Cada [Object](./) tiene dos contadores de referencia: contador de referencia compartida y contador de referencia débil. El contador de referencia débil siempre se almacena en una estructura de datos separada en lugar de en el propio [Object](./), lo que permite que los punteros débiles sobrevivan al objeto referenciado. El contador de referencia inteligente se almacena ya sea en el propio objeto o en la misma estructura separada, dependiendo del estado de la macro ENABLE_EXTERNAL_REFCOUNT. Por defecto, está habilitado en compilaciones de depuración y deshabilitado en compilaciones de lanzamiento. Si el contador del puntero inteligente se almacena en el propio objeto, la estructura de datos separada se crea solo si existen punteros débiles al objeto. De lo contrario, se crea junto con el propio objeto.

Todos los punteros inteligentes utilizan estos dos contadores de referencia y contribuyen al mismo y único grupo de propiedad.

Si una subclase de [Object](./) se crea en la pila, no se pueden crear punteros inteligentes hacia ella; de lo contrario, hay un problema de eliminación de la pila.

Este tipo puede asignarse ya sea en la pila como tipo valor o en el montón usando la función [System::MakeObject()](../makeobject/). Una vez que el objeto está asignado, nunca mezcle estos dos casos de uso: tener punteros [SmartPtr](../smartptr/) a objetos asignados en la pila está estrictamente prohibido.
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
