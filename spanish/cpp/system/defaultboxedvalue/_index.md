---
title: "Clase System::DefaultBoxedValue"
linktitle: "DefaultBoxedValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::DefaultBoxedValue. Implementación de la clase BoxedValue. Permite que las especializaciones de BoxingValue se declaren sin duplicar código común. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system/defaultboxedvalue/
---
## DefaultBoxedValue class


[BoxedValue](../boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Construye una nueva instancia de la clase [DefaultBoxedValue](./) que representa el valor especificado. |
| [Equals](./equals/)(ptr) override | Determina la igualdad de los valores empaquetados representados por el objeto actual y los objetos especificados. |
| [GetHashCode](./gethashcode/)() const override | Devuelve un código hash para el objeto actual. |
| [GetType](./gettype/)() const override | Obtiene el tipo real del objeto. |
| [is](./is/)() const | Determina si el tipo del valor empaquetado representado por el objeto actual es **V**. |
| [ToString](./tostring/)() const override | Devuelve la representación en cadena del valor empaquetado. |
| [unbox](./unbox/)() const | Desempaqueta el valor empaquetado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
