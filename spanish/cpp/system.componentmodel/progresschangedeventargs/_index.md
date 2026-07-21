---
title: "Clase System::ComponentModel::ProgressChangedEventArgs"
linktitle: "ProgressChangedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::ProgressChangedEventArgs. Una instancia de esta clase se pasa como argumento al delegado ProgressChangedEventHandler. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.componentmodel/progresschangedeventargs/
---
## ProgressChangedEventArgs class


Una instancia de esta clase se pasa como argumento al delegado ProgressChangedEventHandler. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class ProgressChangedEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ProgressPercentage](./get_progresspercentage/)() const | Obtiene el porcentaje de progreso de la tarea asincrónica. |
| [get_UserState](./get_userstate/)() const | Obtiene un estado de usuario único. |
| [ProgressChangedEventArgs](./progresschangedeventargs/)(int, System::SharedPtr\<System::Object\>) | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
