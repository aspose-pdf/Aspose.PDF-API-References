---
title: "System::Net::Security::SslStream klass"
linktitle: "SslStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream klass. En ström som använder SSL-protokollet för att autentisera servern och eventuellt klienten i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.security/sslstream/
---
## SslStream class


En ström som använder SSL‑protokollet för att autentisera servern och valfritt även klienten.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String) | Autentiserar klientdelen av anslutningen. |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) | Autentiserar klientdelen av anslutningen. |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron läsoperation. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron skrivoperation. |
| [Close](./close/)() override | Stänger strömmen. |
| [Dispose](./dispose/)(bool) override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona läsoperationen är klar. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| [Flush](./flush/)() override | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande lagringen. |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanTimeout](./get_cantimeout/)() const override | Hämtar ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| virtual [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Returnerar ett värde som indikerar om certifikatåterkallningslistan kontrolleras under certifikatvalideringsprocessen. |
| virtual [get_CipherAlgorithm](./get_cipheralgorithm/)() | Returnerar krypteringsalgoritmen. |
| virtual [get_CipherStrength](./get_cipherstrength/)() | Returnerar styrkan för den använda krypteringsalgoritmen. |
| virtual [get_HashAlgorithm](./get_hashalgorithm/)() | Returnerar hash-algoritmen. |
| virtual [get_HashStrength](./get_hashstrength/)() | Returnerar styrkan för den använda hash-algoritmen. |
| [get_IsAuthenticated](./get_isauthenticated/)() const override | Returnerar ett värde som indikerar om autentiseringen har lyckats. |
| [get_IsEncrypted](./get_isencrypted/)() const override | Returnerar ett värde som indikerar om data som skickas via denna ström är krypterad. |
| [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Returnerar ett värde som indikerar om en server och en klient är autentiserade. |
| [get_IsServer](./get_isserver/)() const override | Returnerar ett värde som indikerar om den lokala sidan av anslutningen är servern. |
| [get_IsSigned](./get_issigned/)() const override | Returnerar ett värde som indikerar om data som skickas via denna ström är signerad. |
| virtual [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Returnerar styrkan för den använda nyckelutbytesalgoritmen. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| virtual [get_LocalCertificate](./get_localcertificate/)() | Returnerar certifikatet som används för att autentisera den lokala ändpunkten. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual [get_RemoteCertificate](./get_remotecertificate/)() | Returnerar certifikatet som används för att autentisera den fjärrändpunkten. |
| virtual [get_SslProtocol](./get_sslprotocol/)() | Returnerar SSL-protokollet. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka skriva innan tidsgränsen nås. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Ställer in strömmens position. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Ställer in ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Ställer in ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>) | Skapar en ny instans. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool) | Skapar en ny instans. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) | Skapar en ny instans. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) | Skapar en ny instans. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) | Skapar en ny instans. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&) | Skriver den angivna bytearrayen till strömmen. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&) | Skriver den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | RTTI-information. |
| [StreamImplementationPtr](./streamimplementationptr/) | Typ av pekare till implementationen. |
## Se även

* Class [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
