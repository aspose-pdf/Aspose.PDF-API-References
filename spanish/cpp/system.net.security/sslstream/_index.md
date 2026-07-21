---
title: "System::Net::Security::SslStream clase"
linktitle: "SslStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::SslStream clase. Un flujo que utiliza el protocolo SSL para autenticar al servidor y, opcionalmente, al cliente en C++."
type: docs
weight: 200
url: /es/cpp/system.net.security/sslstream/
---
## SslStream class


Un flujo que utiliza el protocolo SSL para autenticar al servidor y, opcionalmente, al cliente.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String) | Autentica el lado cliente de la conexión. |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) | Autentica el lado cliente de la conexión. |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación de lectura asíncrona. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación de escritura asíncrona. |
| [Close](./close/)() override | Cierra el flujo. |
| [Dispose](./dispose/)(bool) override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la operación de lectura asíncrona especificada se complete. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Finaliza una operación de escritura asíncrona. Espera hasta que la operación de escritura asíncrona especificada se complete. |
| [Flush](./flush/)() override | Limpia los búferes de este flujo y escribe todos los datos almacenados en el almacenamiento subyacente. |
| [get_CanRead](./get_canread/)() const override | Determina si el flujo es legible. |
| [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| [get_CanTimeout](./get_cantimeout/)() const override | Obtiene un valor que determina si el flujo actual puede expirar. |
| [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| virtual [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Devuelve un valor que indica si la lista de revocación de certificados se verifica durante el proceso de validación del certificado. |
| virtual [get_CipherAlgorithm](./get_cipheralgorithm/)() | Devuelve el algoritmo de cifrado. |
| virtual [get_CipherStrength](./get_cipherstrength/)() | Devuelve la fuerza del algoritmo de cifrado utilizado. |
| virtual [get_HashAlgorithm](./get_hashalgorithm/)() | Devuelve el algoritmo de hash. |
| virtual [get_HashStrength](./get_hashstrength/)() | Devuelve la fuerza del algoritmo de hash utilizado. |
| [get_IsAuthenticated](./get_isauthenticated/)() const override | Devuelve un valor que indica si la autenticación se ha pasado con éxito. |
| [get_IsEncrypted](./get_isencrypted/)() const override | Devuelve un valor que indica si los datos enviados mediante este flujo están cifrados. |
| [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Devuelve un valor que indica si un servidor y un cliente están autenticados. |
| [get_IsServer](./get_isserver/)() const override | Devuelve un valor que indica si el lado local de la conexión es el servidor. |
| [get_IsSigned](./get_issigned/)() const override | Devuelve un valor que indica si los datos enviados mediante este flujo están firmados. |
| virtual [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Devuelve la fuerza del algoritmo de intercambio de claves utilizado. |
| [get_Length](./get_length/)() const override | Devuelve la longitud del flujo en bytes. |
| virtual [get_LocalCertificate](./get_localcertificate/)() | Devuelve el certificado que se utiliza para autenticar el punto final local. |
| [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| virtual [get_RemoteCertificate](./get_remotecertificate/)() | Devuelve el certificado que se utiliza para autenticar el punto final remoto. |
| virtual [get_SslProtocol](./get_sslprotocol/)() | Devuelve el protocolo SSL. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo escribir antes de expirar. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Establece la posición del flujo representado por el objeto actual. |
| [set_Position](./set_position/)(int64_t) override | Establece la posición del flujo. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Establece un valor que determina si el flujo actual puede expirar. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Establece un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| [SetLength](./setlength/)(int64_t) override | Establece la longitud del flujo representado por el objeto actual. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>) | Construye una nueva instancia. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool) | Construye una nueva instancia. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) | Construye una nueva instancia. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) | Construye una nueva instancia. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) | Construye una nueva instancia. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&) | Escribe la matriz de bytes especificada en el flujo. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&) | Escribe la matriz de bytes especificada en el flujo. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Un flujo sin almacenamiento subyacente. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Información RTTI. |
| [StreamImplementationPtr](./streamimplementationptr/) | Tipo de puntero a la implementación. |
## Ver también

* Class [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
