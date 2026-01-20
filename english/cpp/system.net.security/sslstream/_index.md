---
title: System::Net::Security::SslStream class
linktitle: SslStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream class. A stream that uses the SSL protocol to authenticate the server and optionally the client in C++.'
type: docs
weight: 200
url: /cpp/system.net.security/sslstream/
---
## SslStream class


A stream that uses the SSL protocol to authenticate the server and optionally the client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String) | Authenticates the client-side of the connection. |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) | Authenticates the client-side of the connection. |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous read operation. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous write operation. |
| [Close](./close/)() override | Closes the stream. |
| [Dispose](./dispose/)(bool) override | Releases all resources used by the current object and closes the stream. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous read operation completes. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| [Flush](./flush/)() override | Clears this stream's buffers and writes all buffered data to the underlying storage. |
| [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanTimeout](./get_cantimeout/)() const override | Gets a value that determines whether the current stream can time out. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| virtual [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Returns a value that indicates if the certificate revocation list is checked during the certificate validation process. |
| virtual [get_CipherAlgorithm](./get_cipheralgorithm/)() | Returns the encryption algorithm. |
| virtual [get_CipherStrength](./get_cipherstrength/)() | Returns the strength of the used encryption algorithm. |
| virtual [get_HashAlgorithm](./get_hashalgorithm/)() | Returns the hash algorithm. |
| virtual [get_HashStrength](./get_hashstrength/)() | Returns the strength of the used hash algorithm. |
| [get_IsAuthenticated](./get_isauthenticated/)() const override | Returns a value that indicates if authentication is successfully passed. |
| [get_IsEncrypted](./get_isencrypted/)() const override | Returns a value that indicates if the data sent using this stream is encrypted. |
| [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Returns a value that indicates if a server and a client are authenticated. |
| [get_IsServer](./get_isserver/)() const override | Returns a value that indicates if the local side of the connection is the server. |
| [get_IsSigned](./get_issigned/)() const override | Returns a value that indicates if the data sent using this stream is signed. |
| virtual [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Returns the strength of the used key exchange algorithm. |
| [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| virtual [get_LocalCertificate](./get_localcertificate/)() | Returns the certificate that is used to authenticate the local endpoint. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual [get_RemoteCertificate](./get_remotecertificate/)() | Returns the certificate that is used to authenticate the remote endpoint. |
| virtual [get_SslProtocol](./get_sslprotocol/)() | Returns the SSL protocol. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to write before timing out. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Sets the stream's position. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Sets a value that determines whether the current stream can time out. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>) | Constructs a new instance. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool) | Constructs a new instance. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) | Constructs a new instance. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) | Constructs a new instance. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) | Constructs a new instance. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&) | Writes the specified byte array to the stream. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&) | Writes the specified byte array to the stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | RTTI information. |
| [StreamImplementationPtr](./streamimplementationptr/) | Type of pointer to the implementation. |
## See Also

* Class [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
