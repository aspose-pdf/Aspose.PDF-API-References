---
title: "Clase System::ComponentModel::BackgroundWorker"
linktitle: "BackgroundWorker"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::BackgroundWorker. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | Información RTTI. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Obtiene un valor que indica si el [System::ComponentModel::BackgroundWorker](./) puede informar actualizaciones de progreso. |
| [ReportProgress](./reportprogress/)(int) | Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged**. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged** con el objeto userState. |
| [RunWorkerAsync](./runworkerasync/)() | Inicia la ejecución de una operación en segundo plano. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Inicia la ejecución de una operación en segundo plano. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Establece un valor que indica si el [System::ComponentModel::BackgroundWorker](./) puede informar actualizaciones de progreso. |
| [~BackgroundWorker](./~backgroundworker/)() | Destructor. |
## Ver también

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
