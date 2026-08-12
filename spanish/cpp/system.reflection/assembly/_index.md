---
title: "Clase System::Reflection::Assembly"
linktitle: "Assembly"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Reflection::Assembly. Clase de reflexión que describe un ensamblado. El soporte es limitado ya que las reglas son bastante diferentes entre C# y C++. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.reflection/assembly/
---
## Assembly class


[Reflection](../) class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Assembly : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Assembly](./assembly/)() | Constructor. |
| virtual [get_CodeBase](./get_codebase/)() const | Obtiene el directorio del ensamblado actual. El soporte es limitado. |
| virtual [get_FullName](./get_fullname/)() const | Obtiene el nombre completo del ensamblado. |
| virtual [get_Location](./get_location/)() const | Obtiene la ubicación del ensamblado. No implementado. |
| static [GetAssembly](./getassembly/)(const TypeInfo\&) | Obtiene el ensamblado que define un tipo específico. |
| static [GetCallingAssembly](./getcallingassembly/)() | Obtiene el ensamblado llamador. |
| static [GetEntryAssembly](./getentryassembly/)() | Obtiene el ensamblado de entrada. |
| static [GetExecutingAssembly](./getexecutingassembly/)() | Obtiene el ensamblado en ejecución. |
| virtual [GetManifestResourceNames](./getmanifestresourcenames/)() const | Obtiene los nombres de los recursos del manifiesto. |
| virtual [GetManifestResourceStream](./getmanifestresourcestream/)(String) const | Obtiene el flujo conectado al recurso del manifiesto. |
| virtual [GetName](./getname/)() const | Obtiene el nombre del ensamblado. |
| virtual [GetTypes](./gettypes/)() const | Obtiene los tipos declarados por el ensamblado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
