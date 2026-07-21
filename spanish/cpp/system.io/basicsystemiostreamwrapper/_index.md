---
title: "System::IO::BasicSystemIOStreamWrapper clase"
linktitle: "BasicSystemIOStreamWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSystemIOStreamWrapper clase. Representa un envoltorio similar a std::iostream que utilizó BasicSystemIOStreamBuf como búfer interno en C++."
type: docs
weight: 500
url: /es/cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


Representa un envoltorio similar a std::iostream que utilizó [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamWrapper\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Construye una nueva instancia de [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const BasicSystemIOStreamWrapper\&) | Constructor de copia. Eliminado. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(BasicSystemIOStreamWrapper\&&) | Constructor de movimiento. |
| [operator=](./operator=/)(const BasicSystemIOStreamWrapper\&) | Operador de asignación de copia. Eliminado. |
| [operator=](./operator=/)(BasicSystemIOStreamWrapper\&&) | Operador de asignación por movimiento. |
| [swap](./swap/)(BasicSystemIOStreamWrapper\&) | Llamada a intercambiar *this y **right**, si no son iguales. |
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
