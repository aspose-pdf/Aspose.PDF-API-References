---
title: "System::IO::BasicSTDIStreamWrapper class"
linktitle: "BasicSTDIStreamWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSTDIStreamWrapper class. Representa un contenedor similar a System.IO.Stream para std::basic_istream y sus objetos derivados. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper class


Representa un contenedor similar a [System.IO.Stream](../stream/) para std::basic_istream y sus objetos derivados. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) | Construye una nueva instancia de [BasicSTDIStreamWrapper](./). |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const BasicSTDIStreamWrapper\&) | Constructor de copia. Eliminado. |
| [Flush](./flush/)() override | Borra los búferes de este flujo y escribe todos los datos almacenados en el almacenamiento subyacente. ¡No soportado! |
| [operator=](./operator=/)(const BasicSTDIStreamWrapper\&) | Operador de asignación de copia. Eliminado. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Si el modo de envoltura es binario, lee el número especificado de bytes del flujo, de lo contrario lee el número especificado de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en el arreglo de bytes especificado. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [ReadByte](./readbyte/)() override | Si el modo de envoltura es binario, lee un solo byte del almacenamiento del último carácter decodificado, de lo contrario lee un solo carácter del flujo y lo convierte al tipo uint8_t. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. ¡No soportado! |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Si el modo de envoltura es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes indicado; de lo contrario, convierte el subrango especificado de bytes del arreglo indicado al tipo [char_type](./char_type/) y luego escribe el resultado en el flujo. ¡No soportado! |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [WriteByte](./writebyte/)(uint8_t) override | Si el modo de envoltura es binario, escribe en el flujo el valor entero sin signo de 8 bits especificado; de lo contrario, lo convierte al tipo [char_type](./char_type/) y luego escribe el resultado en el flujo. ¡No soportado! |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | Información RTTI. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Ver también

* Class [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
