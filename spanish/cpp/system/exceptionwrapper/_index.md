---
title: "Clase System::ExceptionWrapper"
linktitle: "ExceptionWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ExceptionWrapper. Plantilla que representa un contenedor de excepciones que derivan de la clase Exception en C++."
type: docs
weight: 2700
url: /es/cpp/system/exceptionwrapper/
---
## ExceptionWrapper class


Plantilla que representa un contenedor de excepciones que derivan de la clase [Exception](../exception/).

```cpp
template<typename T>class ExceptionWrapper
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Construye una instancia nula de la clase [ExceptionWrapper](./) que no representa ninguna excepción. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionPtr\&) | Construye una instancia de la clase [ExceptionWrapper](./) que contiene el puntero pasado. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionWrapper\&) | Constructor de copia. |
| [ExceptionWrapper](./exceptionwrapper/)(ExceptionWrapper\&&) | Constructor de movimiento. |
| explicit [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructor que reenvía los parámetros a los constructores de la clase [Exception](../exception/) y crea un puntero inteligente que contiene una nueva instancia de la clase [Exception](../exception/). |
| static [operator new](./operatornew/)(std::size_t) |  |
| static [operator new[]](./operatornew[]/)(std::size_t) |  |
| [operator SharedPtr< Object >](./operatorsharedptr_object_/)() | Operador de conversión implícita a [SharedPtr<Object>](../sharedptr/) |
| [operator->](./operator-_/)() const | Permite acceder a los miembros del objeto [Exception](../exception/). |
| [operator=](./operator=/)(const ExceptionWrapper\&) | Operador de asignación. |
| [operator=](./operator=/)(ExceptionWrapper\&&) | Operador de asignación por movimiento. |
| static [Type](./type/)() | Acceso rápido para obtener el objeto [System::TypeInfo](../typeinfo/) del tipo [Exception](../exception/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Utilizado para funciones de conversión. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
