---
title: "Clase System::Diagnostics::Process"
linktitle: "Process"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Diagnostics::Process. Encapsula información y manipulación del proceso. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.diagnostics/process/
---
## Process class


Encapsula información y manipulación del proceso. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Process : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_EnableRaisingEvents](./get_enableraisingevents/)() const | Obtiene si el evento Exited debe activarse cuando el proceso termina. |
| [get_ExitCode](./get_exitcode/)() const | Obtiene el código de salida del proceso. |
| [get_PrivateMemorySize64](./get_privatememorysize64/)() const | Obtiene el tamaño del conjunto de memoria privada del proceso. |
| [get_ProcessName](./get_processname/)() const | Obtiene el nombre del proceso. |
| [get_StandardError](./get_standarderror/)() const | Proporciona un lector para leer la salida de error del proceso. No implementado. |
| [get_StandardOutput](./get_standardoutput/)() const | Proporciona un lector para leer la salida estándar del proceso. No implementado. |
| [get_StartInfo](./get_startinfo/)() const | Obtiene la información de inicio del proceso. |
| [get_WorkingSet64](./get_workingset64/)() const | Obtiene el tamaño del conjunto de trabajo de la memoria del proceso. |
| static [GetCurrentProcess](./getcurrentprocess/)() | Obtiene información sobre el proceso actual. Solo [Windows](../../system.windows/) . |
| [GetOutputText](./getoutputtext/)() const | Obtiene el texto de salida del proceso. |
| [set_EnableRaisingEvents](./set_enableraisingevents/)(bool) | Establece si el evento Exited debe activarse cuando el proceso termina. |
| [Start](./start/)() | Inicia el proceso con parámetros predefinidos. |
| static [Start](./start/)(const String\&, const String\&) | Inicia el proceso con la ruta y los argumentos especificados. |
| static [Start](./start/)(const SharedPtr\<ProcessStartInfo\>\&) | Inicia el proceso con la ruta y los argumentos especificados. |
| [WaitForExit](./waitforexit/)(int) | Espera a que el proceso termine. No implementado. |
| [WaitForExit](./waitforexit/)() | Espera a que el proceso termine, no regresa hasta que haya finalizado. |
| virtual [~Process](./~process/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
