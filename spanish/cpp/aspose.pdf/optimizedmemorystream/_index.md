---
title: "Clase Aspose::Pdf::OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::OptimizedMemoryStream. Define un MemoryStream que puede contener mayor capacidad estándar en C++."
type: docs
weight: 12400
url: /es/cpp/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class


Define un MemoryStream que puede contener una mayor capacidad estándar.

```cpp
class OptimizedMemoryStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Flush](./flush/)() override | La función sobrescrita. |
| [get_BufferSize](./get_buffersize/)() const | Obtiene el tamaño de los buffers subyacentes. |
| [get_CanRead](./get_canread/)() const override | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite lectura. |
| [get_CanSeek](./get_canseek/)() const override | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite búsqueda. |
| [get_CanWrite](./get_canwrite/)() const override | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite escritura. |
| [get_FreeOnDispose](./get_freeondispose/)() const | Obtiene un valor que indica si liberar los buffers subyacentes al desechar. |
| [get_Length](./get_length/)() const override | Cuando se sobrescribe en una clase derivada, obtiene la longitud en bytes del flujo. |
| [get_Position](./get_position/)() const override | Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual. |
| [OptimizedMemoryStream](./optimizedmemorystream/)() | Inicializa una nueva instancia de la clase [OptimizedMemoryStream](./). |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t, const System::ArrayPtr\<uint8_t\>\&) | Inicializa una nueva instancia de la clase [OptimizedMemoryStream](./) basada en la matriz de bytes especificada. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t) | Inicializa una nueva instancia de la clase [OptimizedMemoryStream](./). |
| [OptimizedMemoryStream](./optimizedmemorystream/)(const System::ArrayPtr\<uint8_t\>\&) | Inicializa una nueva instancia de la clase [OptimizedMemoryStream](./) basada en la matriz de bytes especificada. |
| [Read](./read/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Cuando se sobrescribe en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| [ReadByte](./readbyte/)() override | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| [Seek](./seek/)(int64_t, System::IO::SeekOrigin) override | Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual. |
| [set_BufferSize](./set_buffersize/)(int32_t) | Establece el tamaño de los buffers subyacentes. |
| [set_FreeOnDispose](./set_freeondispose/)(bool) | Establece un valor que indica si liberar los buffers subyacentes al desechar. |
| [set_Position](./set_position/)(int64_t) override | Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual. |
| [SetLength](./setlength/)(int64_t) override | Cuando se sobrescribe en una clase derivada, establece la longitud del flujo actual. |
| [ToArray](./toarray/)() | Convierte el flujo actual a una matriz de bytes. |
| [Write](./write/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Cuando se sobrescribe en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| [WriteByte](./writebyte/)(uint8_t) override | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| [WriteTo](./writeto/)(const System::SharedPtr\<System::IO::Stream\>\&) | Escribe en el flujo especificado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valor predeterminado del tamaño del buffer en bytes. |
| static [Null](../../system.io/stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../../system.io/stream/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
