---
title: "System::IO::BasicSystemIStreamWrapper clase"
linktitle: "BasicSystemIStreamWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSystemIStreamWrapper clase. Representa un envoltorio similar a std::istream que utilizó BasicSystemIOStreamBuf como búfer interno en C++."
type: docs
weight: 600
url: /es/cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


Representa un envoltorio similar a std::istream que utilizó [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIStreamWrapper\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Construye una nueva instancia de [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const BasicSystemIStreamWrapper\&) | Constructor de copia. Eliminado. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(BasicSystemIStreamWrapper\&&) | Constructor de movimiento. |
| [operator=](./operator=/)(const BasicSystemIStreamWrapper\&) | Operador de asignación de copia. Eliminado. |
| [operator=](./operator=/)(BasicSystemIStreamWrapper\&&) | Operador de asignación por movimiento. |
| [swap](./swap/)(BasicSystemIStreamWrapper\&) | Llamada a intercambiar *this y **right**, si no son iguales. |
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
