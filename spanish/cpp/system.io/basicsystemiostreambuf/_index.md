---
title: "System::IO::BasicSystemIOStreamBuf class"
linktitle: "BasicSystemIOStreamBuf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSystemIOStreamBuf class. Representa un búfer que envuelve flujos similares a System::IO::Stream y permite que se usen como un búfer interno de flujos similar a std::iostream en C++."
type: docs
weight: 400
url: /es/cpp/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf class


Representa un búfer que envuelve [System::IO::Stream](../stream/)-like streams y permite que se usen como un búfer interno de flujos similar a std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamBuf\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Construye una nueva instancia de [BasicSystemIOStreamBuf](./). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) | Construye una nueva instancia de [BasicSystemIOStreamBuf](./). |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const BasicSystemIOStreamBuf\&) | Constructor de copia. Eliminado. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(BasicSystemIOStreamBuf\&&) | Constructor de movimiento. |
| [operator=](./operator=/)(const BasicSystemIOStreamBuf\&) | Operador de asignación de copia. Eliminado. |
| [operator=](./operator=/)(BasicSystemIOStreamBuf\&&) | Operador de asignación por movimiento. |
| [swap](./swap/)(BasicSystemIOStreamBuf\&) | Llamada a swap *this y right, si no son iguales. |
| [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [int_type](./int_type/) |  |
| [Mysb](./mysb/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [traits_type](./traits_type/) |  |
## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
