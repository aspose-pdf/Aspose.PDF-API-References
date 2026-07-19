---
title: "System::Net::Security::SslStream класс"
linktitle: "SslStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::SslStream класс. Поток, использующий протокол SSL для аутентификации сервера и, при необходимости, клиента в C++."
type: docs
weight: 200
url: /ru/cpp/system.net.security/sslstream/
---
## SslStream class


Поток, использующий протокол SSL для аутентификации сервера и, при необходимости, клиента.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String) | Аутентифицирует клиентскую сторону соединения. |
| virtual [AuthenticateAsClient](./authenticateasclient/)(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) | Аутентифицирует клиентскую сторону соединения. |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию чтения. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию записи. |
| [Close](./close/)() override | Закрывает поток. |
| [Dispose](./dispose/)(bool) override | Освобождает все ресурсы, используемые текущим объектом, и закрывает поток. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанной асинхронной операции чтения. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| [Flush](./flush/)() override | Очищает буферы этого потока и записывает все буферизованные данные в базовое хранилище. |
| [get_CanRead](./get_canread/)() const override | Определяет, доступен ли поток для чтения. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanTimeout](./get_cantimeout/)() const override | Получает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, доступен ли поток для записи. |
| virtual [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Возвращает значение, указывающее, проверяется ли список отзыва сертификатов во время процесса проверки сертификата. |
| virtual [get_CipherAlgorithm](./get_cipheralgorithm/)() | Возвращает алгоритм шифрования. |
| virtual [get_CipherStrength](./get_cipherstrength/)() | Возвращает силу используемого алгоритма шифрования. |
| virtual [get_HashAlgorithm](./get_hashalgorithm/)() | Возвращает алгоритм хеширования. |
| virtual [get_HashStrength](./get_hashstrength/)() | Возвращает силу используемого алгоритма хеширования. |
| [get_IsAuthenticated](./get_isauthenticated/)() const override | Возвращает значение, указывающее, успешно ли пройдена аутентификация. |
| [get_IsEncrypted](./get_isencrypted/)() const override | Возвращает значение, указывающее, зашифрованы ли данные, отправленные через этот поток. |
| [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Возвращает значение, указывающее, аутентифицированы ли сервер и клиент. |
| [get_IsServer](./get_isserver/)() const override | Возвращает значение, указывающее, является ли локальная сторона соединения сервером. |
| [get_IsSigned](./get_issigned/)() const override | Возвращает значение, указывающее, подписаны ли данные, отправленные через этот поток. |
| virtual [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Возвращает силу используемого алгоритма обмена ключами. |
| [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| virtual [get_LocalCertificate](./get_localcertificate/)() | Возвращает сертификат, используемый для аутентификации локальной конечной точки. |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| virtual [get_RemoteCertificate](./get_remotecertificate/)() | Возвращает сертификат, используемый для аутентификации удалённой конечной точки. |
| virtual [get_SslProtocol](./get_sslprotocol/)() | Возвращает протокол SSL. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм‑аута. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Устанавливает позицию потока. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Устанавливает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| [SetLength](./setlength/)(int64_t) override | Устанавливает длину потока, представленного текущим объектом. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>) | Создаёт новый экземпляр. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool) | Создаёт новый экземпляр. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) | Создаёт новый экземпляр. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) | Создаёт новый экземпляр. |
| [SslStream](./sslstream/)(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) | Создаёт новый экземпляр. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&) | Записывает указанный массив байтов в поток. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&) | Записывает указанный массив байтов в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Поток без базового хранилища. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Информация RTTI. |
| [StreamImplementationPtr](./streamimplementationptr/) | Тип указателя на реализацию. |
## См. также

* Class [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
