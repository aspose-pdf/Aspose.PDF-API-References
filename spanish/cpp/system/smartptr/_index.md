---
title: "Clase System::SmartPtr"
linktitle: "SmartPtr"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::SmartPtr. Clase de puntero para envolver tipos que se asignan en el heap. Úsela para gestionar la memoria de clases que heredan de Object. Este tipo de puntero sigue la semántica de punteros intrusivos. El contador de referencias se almacena ya sea en el propio Object o en una estructura de contador que está estrechamente vinculada a la instancia de Object. En cualquier caso, todas las instancias de SmartPtr forman un único grupo de propiedad sin importar cómo fueron creadas, lo que difiere del comportamiento de la clase std::shared_ptr. Convertir un puntero crudo a SmartPtr es seguro siempre que existan otras instancias de SmartPtr que mantengan referencias compartidas al mismo objeto. Una instancia de la clase SmartPtr puede estar en uno de dos estados: puntero compartido y puntero débil. Para mantener el objeto vivo, debe haber un recuento positivo de referencias compartidas al mismo. Tanto los punteros débiles como los compartidos pueden usarse para acceder al objeto apuntado (para llamar a métodos, leer o escribir campos, etc.), pero los punteros débiles no participan en el recuento de referencias del puntero compartido. El Object se elimina cuando el último puntero ''shared'' SmartPtr a él es destruido. Por lo tanto, asegúrese de que esto no ocurra cuando no existan otros punteros SmartPtr compartidos al objeto, p. ej. durante la construcción o destrucción del objeto. Use los objetos centinela System::Object::ThisProtector (en código C++) o los atributos CppCTORSelfReference o CppSelfReference (en código C# traducido) para corregir este problema. De manera similar, asegúrese de romper referencias cíclicas usando la clase de puntero System::WeakPtr o el modo de puntero System::SmartPtrMode::Weak (en código C++) o el atributo CppWeakPtr (en código C# traducido). Si dos o más objetos se referencian entre sí usando punteros ''shared'', nunca se eliminarán. Si el tipo de puntero (débil o compartido) debe cambiarse en tiempo de ejecución, use el método System::SmartPtr<T>::set_Mode() o la clase System::DynamicWeakPtr. La clase SmartPtr no contiene métodos virtuales. Sólo debe heredarla si está creando su propia estrategia de gestión de memoria. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 5800
url: /es/cpp/system/smartptr/
---
## SmartPtr class


Clase de puntero para envolver tipos que se asignan en el heap. Úsela para gestionar la memoria de clases que heredan de [Object](../object/). Este tipo de puntero sigue la semántica de punteros intrusivos. El contador de referencias se almacena ya sea en el propio [Object](../object/) o en una estructura de contador que está estrechamente vinculada a la instancia de [Object](../object/). En cualquier caso, todas las instancias de [SmartPtr](./) forman un único grupo de propiedad, sin importar cómo fueron creadas, lo que difiere del comportamiento de la clase std::shared_ptr. Convertir un puntero crudo a [SmartPtr](./) es seguro siempre que existan otras instancias de [SmartPtr](./) que mantengan referencias compartidas al mismo objeto. Una instancia de la clase [SmartPtr](./) puede estar en uno de dos estados: puntero compartido y puntero débil. Para mantener el objeto vivo, debe haber un recuento positivo de referencias compartidas al mismo. Tanto los punteros débiles como los compartidos pueden usarse para acceder al objeto apuntado (para llamar a métodos, leer o escribir campos, etc.), pero los punteros débiles no participan en el recuento de referencias del puntero compartido. [Object](../object/) se elimina cuando el último puntero 'shared' [SmartPtr](./) a él es destruido. Por lo tanto, asegúrese de que esto no ocurra cuando no existan otros punteros [SmartPtr](./) compartidos al objeto, p. ej. durante la construcción o destrucción del objeto. Use los objetos centinela System::Object::ThisProtector (en código C++) o los atributos CppCTORSelfReference o CppSelfReference (en código C# traducido) para corregir este problema. De manera similar, asegúrese de romper referencias cíclicas usando la clase de puntero [System::WeakPtr](../weakptr/) o el modo de puntero [System::SmartPtrMode::Weak](../smartptrmode/) (en código C++) o el atributo CppWeakPtr (en código C# traducido). Si dos o más objetos se referencian entre sí usando punteros 'shared', nunca se eliminarán. Si el tipo de puntero (débil o compartido) debe cambiarse en tiempo de ejecución, use el método [System::SmartPtr<T>::set_Mode()](./set_mode/) o la clase [System::DynamicWeakPtr](../dynamicweakptr/). La clase [SmartPtr](./) no contiene métodos virtuales. Sólo debe heredarla si está creando su propia estrategia de gestión de memoria. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
template<class T>class SmartPtr
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo del objeto apuntado. Debe ser [System::Object](../object/) o una subclase de este. |
## Métodos

| Método | Descripción |
| --- | --- |
| [begin](./begin/)() | Accesor del método [begin()](./begin/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [begin()](./begin/). |
| [begin](./begin/)() const | Accesor del método [begin()](./begin/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [begin()](./begin/). |
| [Cast](./cast/)() const | Convierte el puntero a su propio tipo. |
| [Cast](./cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| [Cast](./cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| [Cast](./cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| [cbegin](./cbegin/)() const | Accesor del método [cbegin()](./cbegin/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [cbegin()](./cbegin/). |
| [cend](./cend/)() const | Accesor del método [cend()](./cend/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [cend()](./cend/). |
| [const_pointer_cast](./const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast en el objeto apuntado. |
| [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast en el objeto apuntado. |
| [end](./end/)() | Accesor del método [end()](./end/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [end()](./end/). |
| [end](./end/)() const | Accesor del método [end()](./end/) de una colección subyacente. Sólo se compila si [SmartPtr_](./smartptr_/) es un tipo especializado con el método [end()](./end/). |
| [get](./get/)() const | Obtiene el objeto apuntado. |
| [get_Mode](./get_mode/)() const | Obtiene el modo del puntero. |
| [get_shared](./get_shared/)() const | Obtiene el objeto apuntado, pero afirma que el puntero está en modo compartido. |
| [get_shared_count](./get_shared_count/)() const | Obtiene el número de punteros compartidos existentes al objeto referenciado, incluido el actual. Afirma que el puntero actual está en modo compartido. |
| [GetHashCode](./gethashcode/)() const | Llama a [GetHashCode()](./gethashcode/) en el objeto apuntado. |
| [GetObjectNotNull](./getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si lo hay) o lanza una excepción. |
| [GetObjectOrNull](./getobjectornull/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Lo mismo que [get()](./get/). |
| [GetObjectOwner](./getobjectowner/)() const | Obtiene el objeto referenciado. |
| [GetPointer](./getpointer/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Lo mismo que [get()](./get/). |
| [Is](./is/)(const System::TypeInfo\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica de 'is' de C#. |
| [IsAliasingPtr](./isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto del que posee (creado por un constructor de alias). |
| [IsShared](./isshared/)() const | Comprueba si el puntero está en modo compartido. |
| [IsWeak](./isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit [operator bool](./operatorbool/)() const | Comprueba si el puntero no es nulo. |
| [operator!](./operator!/)() const | Comprueba si el puntero es nulo. |
| [operator*](./operator_/)() const | Obtiene una referencia al objeto apuntado. Asegura que el puntero no sea nulo. |
| [operator->](./operator-_/)() const | Permite acceder a los miembros del objeto referenciado. |
| [operator<](./operator_/)(Y *) const | Proporciona semántica de comparación menor para la clase [SmartPtr](./). |
| [operator<](./operator_/)(SmartPtr\<Y\> const\&) const | Proporciona semántica de comparación menor para la clase [SmartPtr](./). |
| [operator=](./operator=/)(SmartPtr_\&&) | Asigna por movimiento el objeto [SmartPtr](./). x queda inutilizable. |
| [operator=](./operator=/)(const SmartPtr_\&) | Asigna por copia el objeto [SmartPtr](./). |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Asigna por copia el objeto [SmartPtr](./). Realiza las conversiones de tipo necesarias. |
| [operator=](./operator=/)(Pointee_ *) | Asigna un puntero crudo al objeto [SmartPtr](./). |
| [operator=](./operator=/)(std::nullptr_t) | Establece el valor del puntero a nullptr. |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si el puntero apunta a nullptr. |
| [operator[]](./operator[]/)(IdxType) const | Accesor para los elementos del arreglo. Sólo se compila si [SmartPtr_](./smartptr_/) es una especialización de [System::Array](../array/). |
| [RemoveAliasing](./removealiasing/)() const | Elimina el alias (creado por un constructor de alias) del puntero, asegurándose de que gestione (si es compartido) o rastree (si es débil) el mismo objeto al que apunta. |
| [reset](./reset/)(Pointee_ *) | Establece el objeto apuntado. |
| [reset](./reset/)() | Hace que el puntero apunte a nullptr. |
| [set_Mode](./set_mode/)(SmartPtrMode) | Establece el modo del puntero. Puede alterar los recuentos de referencias del objeto referenciado. |
| [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(uint32_t) const | Llama al método SetTemplateWeakPtr() en el objeto apuntado (si lo hay). |
| [SmartPtr](./smartptr/)(SmartPtrMode) | Crea un objeto [SmartPtr](./) del modo requerido. |
| [SmartPtr](./smartptr/)(std::nullptr_t, SmartPtrMode) | Crea un objeto [SmartPtr](./) nulo del modo requerido. |
| [SmartPtr](./smartptr/)(Pointee_ *, SmartPtrMode) | Crea un [SmartPtr](./) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](./). |
| [SmartPtr](./smartptr/)(const SmartPtr_\&, SmartPtrMode) | Copia construye el objeto [SmartPtr](./). Ambos punteros apuntan al mismo objeto después. |
| [SmartPtr](./smartptr/)(const SmartPtr\<Q\>\&, SmartPtrMode) | Copia construye el objeto [SmartPtr](./). Ambos punteros apuntan al mismo objeto después. Realiza conversión de tipo si está permitida. |
| [SmartPtr](./smartptr/)(SmartPtr_\&&, SmartPtrMode) | Mueve construye el objeto [SmartPtr](./). Efectivamente, intercambia dos punteros, si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada. |
| explicit [SmartPtr](./smartptr/)(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) | Convierte el tipo del arreglo referenciado creando un nuevo arreglo de tipo diferente. Útil si en C# existe una conversión de tipo de arreglo que no está soportada en C++. |
| explicit [SmartPtr](./smartptr/)(const Y\&) | Inicializa un arreglo vacío. Utilizado para traducir algunas construcciones de código C#. |
| [SmartPtr](./smartptr/)(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) | Construye un [SmartPtr](./) que comparte la información de propiedad con el valor inicial de ptr, pero contiene un puntero p no relacionado y no administrado. |
| [static_pointer_cast](./static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast sobre el objeto apuntado. |
| [ToObjectPtr](./toobjectptr/)() const | Convierte cualquier tipo de puntero a un puntero a [Object](../object/). No requiere que el tipo [Pointee_](./pointee_/) esté completo. |
| static [Type](./type/)() | Atajo para obtener el objeto [System::TypeInfo](../typeinfo/) del tipo [Pointee_](./pointee_/). |
| [~SmartPtr](./~smartptr/)() | Destruye el objeto [SmartPtr](./). Si es necesario, disminuye el contador de referencias del objeto apuntado y elimina el objeto. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ArrayType](./arraytype/) | Igual que [Pointee_](./pointee_/), si es una especialización de [System::Array](../array/), y void en caso contrario. |
| [Pointee_](./pointee_/) | Tipo apuntado. |
| [SmartPtr_](./smartptr_/) | Tipo de puntero inteligente especializado. |
| [ValueType](./valuetype/) | Tipo de almacenamiento del arreglo apuntado. Solo tiene sentido si T es una especialización de [System::Array](../array/). |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
