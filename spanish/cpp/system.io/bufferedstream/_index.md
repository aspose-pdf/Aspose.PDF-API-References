---
title: "Clase System::IO::BufferedStream"
linktitle: "BufferedStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::BufferedStream. Añade una capa de almacenamiento intermedio sobre otro flujo. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.io/bufferedstream/
---
## BufferedStream class


Añade una capa de almacenamiento intermedio sobre otro flujo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class BufferedStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&) | Construye un objeto [BufferedStream](./) que envuelve el flujo especificado y utiliza un búfer de 4096 bytes de longitud. |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&, int) | Construye un objeto [BufferedStream](./) que envuelve el flujo especificado y utiliza un búfer del tamaño especificado. |
| [Flush](./flush/)() override | Escribe el contenido del búfer en el flujo subyacente. |
| [get_CanRead](./get_canread/)() const override | Determina si el flujo es legible. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada. |
| [ReadByte](./readbyte/)() override | Lee un solo byte del flujo subyacente y devuelve un valor entero de 32 bits equivalente al valor del byte leído. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Vacia el búfer al flujo subyacente y luego establece la posición del flujo. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada en el flujo subyacente. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada en el flujo subyacente. |
| [WriteByte](./writebyte/)(uint8_t) override | Escribe el valor entero sin signo de 8 bits especificado en el flujo subyacente. |
| virtual [~BufferedStream](./~bufferedstream/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
