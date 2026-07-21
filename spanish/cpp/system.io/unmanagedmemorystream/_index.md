---
title: "System::IO::UnmanagedMemoryStream class"
linktitle: "UnmanagedMemoryStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::UnmanagedMemoryStream class. Proporciona acceso a memoria no administrada. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2800
url: /es/cpp/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream class


Proporciona acceso a memoria no administrada. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Flush](./flush/)() override | No hace nada. |
| [get_CanRead](./get_canread/)() const override | Determina si el flujo es legible. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| virtual [get_Capacity](./get_capacity/)() const | Devuelve la capacidad actual del búfer de memoria subyacente. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo en bytes. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [get_PositionPointer](./get_positionpointer/)() | NO IMPLEMENTADO. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Establece la posición del flujo. |
| [set_PositionPointer](./set_positionpointer/)(uint8_t *) | NO IMPLEMENTADO. |
| [SetLength](./setlength/)(int64_t) override | NO IMPLEMENTADO. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t) | Construye una nueva instancia de [UnmanagedMemoryStream](./). |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t, int64_t, FileAccess) | Construye una nueva instancia de [UnmanagedMemoryStream](./). |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | NO IMPLEMENTADO. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | NO IMPLEMENTADO. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
