---
title: "System::IO::FileStream class"
linktitle: "FileStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileStream class. Representa un flujo de archivo que admite operaciones de lectura y escritura síncronas y asíncronas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1500
url: /es/cpp/system.io/filestream/
---
## FileStream class


Representa un flujo de archivo que admite operaciones de lectura y escritura síncronas y asíncronas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class FileStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cierra el objeto [FileStream](./) actual. |
| [FileStream](./filestream/)(const String\&, FileMode) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
| [FileStream](./filestream/)(const FileStream\&) |  |
| [Flush](./flush/)() override | Borra los búferes de este flujo y escribe todos los datos almacenados en el archivo subyacente. |
| [Flush](./flush/)(bool) | Borra los búferes de este flujo y escribe todos los datos almacenados en el archivo subyacente. Sinónimo del método [Flush()](./flush/). |
| [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) override | De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| [get_CanRead](./get_canread/)() const override | Determina si el flujo es legible. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo en bytes. |
| [get_Name](./get_name/)() const | Devuelve el nombre del archivo encapsulado por el objeto [FileStream](./) actual. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [operator=](./operator=/)(const FileStream\&) |  |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | De forma asíncrona, lee una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| [ReadByte](./readbyte/)() override | Lee un solo byte del flujo y devuelve un valor entero de 32 bits equivalente al valor del byte leído. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Vacia el flujo y luego establece la posición del flujo. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | De forma asíncrona, escribe una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| [WriteByte](./writebyte/)(uint8_t) override | Escribe el valor entero sin signo de 8 bits especificado en el flujo. |
| [~FileStream](./~filestream/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Valor predeterminado del número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
