---
title: "Clase System::Threading::Tasks::ValueTask"
linktitle: "ValueTask"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Tasks::ValueTask. Proporciona un resultado awaitable de una operación asincrónica en C++."
type: docs
weight: 800
url: /es/cpp/system.threading.tasks/valuetask/
---
## ValueTask class


Proporciona un resultado esperable de una operación asíncrona.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AsTask](./astask/)() const | Convierte este [ValueTask](./) a un puntero compartido a [Task](../task/). |
| [ConfigureAwait](./configureawait/)(bool) const | Configura un awaiter para esta tarea. |
| [Equals](./equals/)(ValueTask) override | Determina si esta instancia es igual a otra instancia de [ValueTask](./). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si esta instancia es igual a otro objeto. |
| [get_IsCanceled](./get_iscanceled/)() const | Obtiene un valor que indica si la tarea se completó debido a que fue cancelada. |
| [get_IsCompleted](./get_iscompleted/)() const | Obtiene un valor que indica si la tarea ha finalizado. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Obtiene un valor que indica si la tarea se completó con éxito. |
| [get_IsFaulted](./get_isfaulted/)() const | Obtiene un valor que indica si la tarea se completó debido a una excepción no controlada. |
| [GetAwaiter](./getawaiter/)() const | Obtiene un awaiter para esta tarea para soportar expresiones await. |
| [operator!=](./operator!=/)(const ValueTask\&) const | Operador de desigualdad para [ValueTask](./). |
| [operator==](./operator==/)(const ValueTask\&) const | Operador de igualdad para [ValueTask](./). |
| [ValueTask](./valuetask/)() | Construye un [ValueTask](./) vacío y sin inicializar. |
| [ValueTask](./valuetask/)(const TaskPtr\&) | Construye un [ValueTask](./) a partir de un puntero compartido a un [Task](../task/). |
## Ver también

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
