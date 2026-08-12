---
title: "System::Diagnostics::ProcessStartInfo clase"
linktitle: "ProcessStartInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Diagnostics::ProcessStartInfo. Describe los parámetros de inicio del proceso. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.diagnostics/processstartinfo/
---
## ProcessStartInfo class


Describe los parámetros de inicio del proceso. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ProcessStartInfo : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Arguments](./get_arguments/)() const | Obtiene los argumentos del proceso. |
| [get_CreateNoWindow](./get_createnowindow/)() const | Obtiene la propiedad NoWindow. |
| [get_EnvironmentVariables](./get_environmentvariables/)() const | Obtiene las variables de entorno del proceso. |
| [get_FileName](./get_filename/)() const | Obtiene el nombre de archivo del proceso. |
| [get_RedirectStandardError](./get_redirectstandarderror/)() const | Obtiene la propiedad RedirectStandardError. |
| [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Obtiene la propiedad RedirectStandardInput. |
| [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Obtiene la propiedad RedirectStandardOutput. |
| [get_UseShellExecute](./get_useshellexecute/)() const | Obtiene la propiedad UseShellExecute. |
| [get_WindowStyle](./get_windowstyle/)() const | Obtiene el estilo de ventana. |
| [get_WorkingDirectory](./get_workingdirectory/)() const | Obtiene el directorio de trabajo del proceso. |
| [ProcessStartInfo](./processstartinfo/)() | Crea un objeto de información de inicio vacío. |
| [ProcessStartInfo](./processstartinfo/)(const String\&) | Crea un objeto de información de inicio. |
| [ProcessStartInfo](./processstartinfo/)(const String\&, const String\&) | Crea un objeto de información de inicio. |
| [set_Arguments](./set_arguments/)(const String\&) | Establece los argumentos del proceso. |
| [set_CreateNoWindow](./set_createnowindow/)(bool) | Establece la propiedad NoWindow. |
| [set_FileName](./set_filename/)(const String\&) | Establece el nombre de archivo del proceso. |
| [set_RedirectStandardError](./set_redirectstandarderror/)(bool) | Establece la propiedad RedirectStandardError. |
| [set_RedirectStandardInput](./set_redirectstandardinput/)(bool) | Establece la propiedad RedirectStandardInput. |
| [set_RedirectStandardOutput](./set_redirectstandardoutput/)(bool) | Establece la propiedad RedirectStandardOutput. |
| [set_UseShellExecute](./set_useshellexecute/)(bool) | Establece la propiedad UseShellExecute. |
| [set_WindowStyle](./set_windowstyle/)(ProcessWindowStyle) | Establece el estilo de ventana. |
| [set_WorkingDirectory](./set_workingdirectory/)(const String\&) | Establece el directorio de trabajo del proceso. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
