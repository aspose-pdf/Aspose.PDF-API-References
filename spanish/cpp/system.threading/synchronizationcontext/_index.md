---
title: "Clase System::Threading::SynchronizationContext"
linktitle: "SynchronizationContext"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::SynchronizationContext. Proporciona la funcionalidad básica para propagar un contexto de sincronización a través de varias operaciones de sincronización en C++."
type: docs
weight: 1100
url: /es/cpp/system.threading/synchronizationcontext/
---
## SynchronizationContext class


Proporciona la funcionalidad básica para propagar un contexto de sincronización a través de varias operaciones de sincronización.

```cpp
class SynchronizationContext : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [get_Current](./get_current/)() | Obtiene el contexto de sincronización para el hilo actual. |
| virtual [Post](./post/)(SendOrPostCallback, SharedPtr\<Object\>) | Ejecuta la devolución de llamada de forma asíncrona. |
| virtual [Send](./send/)(SendOrPostCallback, SharedPtr\<Object\>) | Ejecuta la devolución de llamada de forma síncrona. |
| static [SetSynchronizationContext](./setsynchronizationcontext/)(const SharedPtr\<SynchronizationContext\>\&) | Establece el contexto de sincronización para el hilo actual. |
| [SynchronizationContext](./synchronizationcontext/)() | Información RTTI. |
## Observaciones


Esta clase permite la propagación del contexto de sincronización entre hilos y se utiliza para enviar devoluciones de llamada o invocaciones al hilo o contexto de sincronización apropiado.
Implementación ficticia.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
