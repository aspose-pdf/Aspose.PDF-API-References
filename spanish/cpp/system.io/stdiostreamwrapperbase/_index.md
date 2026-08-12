---
title: "Clase System::IO::STDIOStreamWrapperBase"
linktitle: "STDIOStreamWrapperBase"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::STDIOStreamWrapperBase. Representa una clase base para envoltorios similares a System.IO.Stream. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase class


Representa una clase base para envoltorios similares a [System.IO.Stream](../stream/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CanRead](./get_canread/)() const override | Determina si el flujo admite lectura. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo admite escritura. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [operator=](./operator=/)(const STDIOStreamWrapperBase\&) | Operador de asignación de copia. Eliminado. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Establece la posición del flujo. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const STDIOStreamWrapperBase\&) | Constructor de copia. Eliminado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | Información RTTI. |
| [int_type](./int_type/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Ver también

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
