---
title: "Clase System::IO::BasicSTDIOStreamWrapper"
linktitle: "BasicSTDIOStreamWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::BasicSTDIOStreamWrapper. Representa un contenedor similar a System.IO.Stream para std::basic_iostream y sus objetos derivados. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper class


Representa un contenedor similar a [System.IO.Stream](../stream/) para std::basic_iostream y sus objetos derivados. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) | Construye una nueva instancia de [BasicSTDIOStreamWrapper](./). |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const BasicSTDIOStreamWrapper\&) | Constructor de copia. Eliminado. |
| [Flush](./flush/)() override | Limpia los búferes de este flujo y escribe todos los datos almacenados en el almacenamiento subyacente. |
| [operator=](./operator=/)(const BasicSTDIOStreamWrapper\&) | Operador de asignación de copia. Eliminado. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Si el modo de envoltura es binario, lee el número especificado de bytes del flujo, de lo contrario lee el número especificado de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en el arreglo de bytes especificado. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [ReadByte](./readbyte/)() override | Si el modo de envoltura es binario, lee un solo byte del almacenamiento del último carácter decodificado, de lo contrario lee un solo carácter del flujo y lo convierte al tipo uint8_t. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Si el modo de envoltura es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes especificado, de lo contrario convierte el subrango especificado de bytes del arreglo de bytes especificado al tipo [char_type](./char_type/) y luego escribe el resultado en el flujo. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [WriteByte](./writebyte/)(uint8_t) override | Si el modo de envoltura es binario, escribe en el flujo el valor entero sin signo de 8 bits especificado, de lo contrario lo convierte al tipo [char_type](./char_type/) y luego escribe el resultado en el flujo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | Información RTTI. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Ver también

* Class [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Class [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
