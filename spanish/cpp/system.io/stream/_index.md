---
title: "Clase System::IO::Stream"
linktitle: "Stream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::Stream. Una clase base para una variedad de implementaciones de flujo. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.io/stream/
---
## Stream class


Una clase base para una variedad de implementaciones de flujo. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Stream : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Inicia una operación de lectura asíncrona. |
| virtual [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Inicia una operación de escritura asíncrona. |
| virtual [Close](./close/)() | Cierra el flujo. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&) | Copia bytes al flujo especificado. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&, int32_t) | Copia bytes al flujo especificado, usando el tamaño de búfer especificado. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo. |
| virtual [EndRead](./endread/)(System::SharedPtr\<System::IAsyncResult\>) | Espera hasta que la operación de lectura asíncrona especificada se complete. |
| virtual [EndWrite](./endwrite/)(System::SharedPtr\<System::IAsyncResult\>) | Finaliza una operación de escritura asíncrona. Espera hasta que la operación de escritura asíncrona especificada se complete. |
| virtual [Flush](./flush/)() | Limpia los búferes de este flujo y escribe todos los datos almacenados en el almacenamiento subyacente. |
| virtual [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) | De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| [FlushAsync](./flushasync/)() | De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| virtual [get_CanRead](./get_canread/)() const | Determina si el flujo es legible. |
| virtual [get_CanSeek](./get_canseek/)() const | Determina si el flujo admite búsqueda. |
| virtual [get_CanTimeout](./get_cantimeout/)() const | Obtiene un valor que determina si el flujo actual puede expirar. |
| virtual [get_CanWrite](./get_canwrite/)() const | Determina si el flujo es escribible. |
| virtual [get_Length](./get_length/)() const | Devuelve la longitud del flujo en bytes. |
| virtual [get_Position](./get_position/)() const | Devuelve la posición actual del flujo. |
| virtual [get_ReadTimeout](./get_readtimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| virtual [get_WriteTimeout](./get_writetimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo escribir antes de expirar. |
| virtual [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| virtual [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| virtual [Read](./read/)(const System::Span\<uint8_t\>\&) | Lee el número especificado de bytes del flujo y los escribe en el span de bytes especificado. |
| virtual [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | De forma asíncrona, lee una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | De forma asíncrona, lee una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| virtual [ReadByte](./readbyte/)() | Lee un solo byte del flujo y devuelve un valor entero de 32 bits equivalente al valor del byte leído. |
| virtual [Seek](./seek/)(int64_t, SeekOrigin) | Establece la posición del flujo representado por el objeto actual. |
| virtual [set_Position](./set_position/)(int64_t) | Establece la posición del flujo. |
| virtual [set_ReadTimeout](./set_readtimeout/)(int) | Establece un valor que determina si el flujo actual puede expirar. |
| virtual [set_WriteTimeout](./set_writetimeout/)(int) | Establece un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| virtual [SetLength](./setlength/)(int64_t) | Establece la longitud del flujo representado por el objeto actual. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| virtual [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [Write](./write/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| virtual [Write](./write/)(const System::ReadOnlySpan\<uint8_t\>\&) | Escribe el subrango especificado de bytes del span de bytes especificado en el flujo. |
| virtual [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | De forma asíncrona, escribe una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | De forma asíncrona, escribe una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| virtual [WriteByte](./writebyte/)(uint8_t) | Escribe el valor entero sin signo de 8 bits especificado en el flujo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](./null/) | Un flujo sin almacenamiento subyacente. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a esta clase. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
