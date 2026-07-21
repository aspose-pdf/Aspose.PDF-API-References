---
title: "System::DynamicWeakPtr::Reference clase"
linktitle: "Reference"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DynamicWeakPtr::Reference clase. Clase de referencia que asegura que DynamicWeakPtr::Apply sea llamado. Se usa si DynamicWeakPtr se pasa como parámetro de referencia SmartPtr a una función que pueda asignarle en C++."
type: docs
weight: 700
url: /es/cpp/system/dynamicweakptr/reference/
---
## Reference class


[Reference](./) class which ensures that DynamicWeakPtr::Apply is called. Used if [DynamicWeakPtr](../) is passed as [SmartPtr](../../smartptr/) reference parameter to function which may assign to it.

```cpp
class Reference
```

## Métodos

| Método | Descripción |
| --- | --- |
| [operator DynamicWeakPtr_ &](./operatordynamicweakptr_&/)() const | Operador de conversión. Permite usar [Reference](./) en contextos donde se necesita [DynamicWeakPtr_](../dynamicweakptr_/). |
| [Reference](./reference/)(DynamicWeakPtr_\&) | Crea una referencia de puntero inteligente. |
| [Reference](./reference/)(Reference\&&) | Construye por movimiento la referencia del puntero inteligente. |
| [~Reference](./~reference/)() | Destruye la referencia. Garantiza la llamada a Apply() en el puntero inteligente referenciado. |
## Ver también

* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
