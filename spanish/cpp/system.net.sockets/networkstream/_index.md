---
title: "System::Net::Sockets::NetworkStream class"
linktitle: "NetworkStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::NetworkStream class. Proporciona el flujo subyacente de los datos para el acceso a la red. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Proporciona el flujo subyacente de los datos para el acceso a la red. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class NetworkStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación de lectura asíncrona. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación de escritura asíncrona. |
| [Close](./close/)(int) | Cierra la instancia actual después de que expire el tiempo especificado. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la operación de lectura asíncrona especificada se complete. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Finaliza una operación de escritura asíncrona. Espera hasta que la operación de escritura asíncrona especificada se complete. |
| [Flush](./flush/)() override | Limpia los búferes de este flujo y escribe todos los datos almacenados en el almacenamiento subyacente. |
| [get_CanRead](./get_canread/)() const override | Información RTTI. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanTimeout](./get_cantimeout/)() const override | Obtiene un valor que determina si el flujo actual puede expirar. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| [get_DataAvailable](./get_dataavailable/)() const | Devuelve un valor que indica si hay datos disponibles para leer. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo en bytes. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| [get_Socket](./get_socket/)() | Obtiene el [Socket](../socket/) subyacente. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo escribir antes de expirar. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Construye una nueva instancia. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Construye una nueva instancia. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Construye una nueva instancia. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Establece la posición del flujo. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Establece un valor que determina si el flujo actual puede expirar. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Establece un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| virtual [~NetworkStream](./~networkstream/)() | Destruye la instancia actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
