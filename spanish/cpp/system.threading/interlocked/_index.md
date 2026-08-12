---
title: "Clase System::Threading::Interlocked"
linktitle: "Interlocked"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Interlocked. Proporciona una API para operaciones seguras en hilos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de ella por ningún medio en C++."
type: docs
weight: 600
url: /es/cpp/system.threading/interlocked/
---
## Interlocked class


Proporciona una API para operaciones seguras en hilos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Interlocked
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(int32_t\&, int32_t) | Incrementa el valor de forma atómica. |
| static [Add](./add/)(int64_t\&, int64_t) | Incrementa el valor de forma atómica. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. No implementado. |
| static [CompareExchange](./compareexchange/)(int32_t\&, int32_t, int32_t, bool\&) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. |
| static [Decrement](./decrement/)(int32_t\&) | Decrementa el valor de forma atómica. |
| static [Decrement](./decrement/)(int64_t\&) | Decrementa el valor de forma atómica. |
| static [Exchange](./exchange/)(T\&, T) | Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. |
| static [Exchange](./exchange/)(T\&, T) | Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. No implementado. |
| static [ExchangeAdd](./exchangeadd/)(int32_t\&, int32_t) | Incrementa el valor de forma atómica mediante el procedimiento exchange-add. |
| static [ExchangeAdd](./exchangeadd/)(int64_t\&, int64_t) | Incrementa el valor de forma atómica mediante el procedimiento exchange-add. |
| static [Increment](./increment/)(int32_t\&) | Incrementa el valor de forma atómica. |
| static [Increment](./increment/)(int64_t\&) | Incrementa el valor de forma atómica. |
| static [Read](./read/)(int64_t\&) | Devuelve un valor de 64 bits, cargado como una operación atómica. |
## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
