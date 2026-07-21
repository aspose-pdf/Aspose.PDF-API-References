---
title: "System::IO::BasicSystemOStreamWrapper class"
linktitle: "BasicSystemOStreamWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::BasicSystemOStreamWrapper. Representa un envoltorio similar a std::ostream que utilizó BasicSystemIOStreamBuf como búfer interno en C++."
type: docs
weight: 700
url: /es/cpp/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


Representa un envoltorio similar a std::ostream que utilizó [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemOStreamWrapper\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Construye una nueva instancia de [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const BasicSystemOStreamWrapper\&) | Constructor de copia. Eliminado. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(BasicSystemOStreamWrapper\&&) | Constructor de movimiento. |
| [operator=](./operator=/)(const BasicSystemOStreamWrapper\&) | Operador de asignación de copia. Eliminado. |
| [operator=](./operator=/)(BasicSystemOStreamWrapper\&&) | Operador de asignación por movimiento. |
| [swap](./swap/)(BasicSystemOStreamWrapper\&) | Llamada a intercambiar *this y **right**, si no son iguales. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
