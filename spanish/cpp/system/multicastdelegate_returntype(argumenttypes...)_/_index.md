---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> clase"
linktitle: "MulticastDelegate< ReturnType(ArgumentTypes...)>"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> clase. Representa una colección de delegados. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 4700
url: /es/cpp/system/multicastdelegate_returntype(argumenttypes...)_/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> class


Representa una colección de delegados. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parámetro | Descripción |
| --- | --- |
| ReturnType | Tipo de retorno de las entidades invocables a las que apunta cada delegado en la colección |
| ArgumentTypes | Lista de argumentos de las entidades invocables a las que apunta cada delegado en la colección |
## Métodos

| Método | Descripción |
| --- | --- |
| [BeginInvoke](./begininvoke/)(ArgumentTypes..., const AsyncCallback\&, const CallbackArgumentType\&) | NO IMPLEMENTADO. |
| [connect](./connect/)(Callback) | Agrega el delegado especificado a la colección. |
| [connect](./connect/)(std::function\<R(Args...)>) | Agrega el objeto función especificado a la colección de delegados. El objeto función se convierte al tipo de delegado [Callback](./callback/) antes de ser agregado a la colección. |
| [connect](./connect/)(MulticastDelegate\&) | Agrega el objeto MulticastDelegate especificado a la colección de delegados. |
| [connect](./connect/)(MemberType ClassType::*, ClassType *) | Agrega el método no estático especificado del objeto especificado a la colección de delegados. |
| [connect](./connect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Agrega el método no estático especificado del objeto especificado a la colección de delegados. |
| [disconnect](./disconnect/)(Callback) | Elimina el delegado especificado de la colección de delegados. |
| [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Elimina el método no estático especificado del objeto especificado de la colección de delegados. |
| [disconnect](./disconnect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Elimina el método no estático especificado del objeto especificado de la colección de delegados. |
| [disconnect](./disconnect/)(MulticastDelegate\&) | Elimina el objeto MulticastDelegate especificado de la colección de delegados. |
| [disconnect_all_slots](./disconnect_all_slots/)() | Elimina todos los delegados de la colección de delegados. |
| [empty](./empty/)() const | Determina si la colección de delegados está vacía. |
| [EndInvoke](./endinvoke/)(const SharedPtr\<IAsyncResult\>\&) | NO IMPLEMENTADO. |
| [Equals](./equals/)(const MulticastDelegate\&) |  |
| [GetHashCode](./gethashcode/)() const |  |
| [GetType](./gettype/)() const |  |
| [invoke](./invoke/)(ArgumentTypes...) const | Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El método se bloquea mientras se ejecutan los delegados. |
| [IsNull](./isnull/)() const | Determina si la colección de delegados está vacía. |
| [MulticastDelegate](./multicastdelegate/)() | Construye una colección vacía. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalente al constructor por defecto. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Realiza una copia superficial de la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Constructor de movimiento. |
| [MulticastDelegate](./multicastdelegate/)(Callback\&&) | Construye una instancia y coloca el delegado especificado en la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)(T) | Construye una instancia y coloca el valor especificado en la colección de delegados. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Construye una instancia y coloca el valor especificado en la colección de delegados. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Determina si la colección de delegados no está vacía. |
| [operator!=](./operator!=/)(const MulticastDelegate\&) const | Determina si dos instancias de MulticastDelegate - el objeto actual y el objeto especificado - son desiguales. |
| [operator()](./operator()/)(ArgumentTypes...) const | Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron añadidos a la colección. El operador se bloquea mientras se ejecutan los delegados. |
| [operator+=](./operator+=/)(Callback) | Agrega el delegado especificado a la colección. |
| [operator-=](./operator-=/)(Callback) | Elimina el delegado especificado de la colección de delegados. |
| [operator=](./operator=/)(const MulticastDelegate\&) | Asigna la colección de delegados representada por el objeto especificado al objeto actual. Como resultado, ambos objetos apuntan a la misma colección de delegados. |
| [operator=](./operator=/)(MulticastDelegate\&&) | Operador de asignación por movimiento. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Determina si la colección de delegados está vacía. |
| [operator==](./operator==/)(const MulticastDelegate\&) const | Determina si dos instancias de MulticastDelegate - el objeto actual y el objeto especificado - son iguales. |
| [remove_empty_callbacks](./remove_empty_callbacks/)() const | Elimina los callbacks contenidos que están vacíos (no llaman a nada). |
| [ToString](./tostring/)() const |  |
| static [Type](./type/)() | Devuelve una referencia al objeto [TypeInfo](../typeinfo/) que representa la información de tipo de la clase MulticastDelegate. |
| [~MulticastDelegate](./~multicastdelegate/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Callback](./callback/) | El tipo de los delegados representados por la clase MulticastDelegate. |
| [Function](./function/) | El tipo de la función relacionada con la firma del delegado. |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
