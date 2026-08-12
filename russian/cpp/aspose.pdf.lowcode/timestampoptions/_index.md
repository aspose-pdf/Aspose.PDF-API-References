---
title: "Класс Aspose::Pdf::LowCode::TimestampOptions"
linktitle: "TimestampOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::TimestampOptions. Параметры для плагина Timestamp Low‑Code в C++."
type: docs
weight: 9100
url: /ru/cpp/aspose.pdf.lowcode/timestampoptions/
---
## TimestampOptions class


Параметры для плагина Low‑Code [Timestamp](../timestamp/).

```cpp
class TimestampOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BasicAuthCredentials](./get_basicauthcredentials/)() const | Получает базовые учетные данные аутентификации, имя пользователя и пароль объединяются в строку "username:password". |
| [get_DigestHashAlgorithm](./get_digesthashalgorithm/)() const | Алгоритм хеширования Digest, используемый для метки времени. По умолчанию Sha256. |
| [get_OperationName](./get_operationname/)() override | Возвращает имя операции. |
| [get_PageNumber](./get_pagenumber/)() const | Номер [Page](../../aspose.pdf/page/), к которому будет применена подпись с меткой времени. |
| [get_Rectangle](./get_rectangle/)() const | [Rectangle](../../aspose.pdf/rectangle/), определяющий область аннотации (игнорируется, когда Visible равно false). |
| [get_ServerUrl](./get_serverurl/)() const | URL сервера метки времени. |
| [get_SigContact](./get_sigcontact/)() const | Контактная информация для подписи. |
| [get_SigLocation](./get_siglocation/)() const | Местоположение подписи. |
| [get_SigReason](./get_sigreason/)() const | Причина подписи. |
| [get_Visible](./get_visible/)() const | Флаг видимости – false для чистой метки времени (без видимой аннотации). |
| [set_BasicAuthCredentials](./set_basicauthcredentials/)(const System::String\&) | Устанавливает базовые учетные данные аутентификации, имя пользователя и пароль объединяются в строку "username:password". |
| [set_DigestHashAlgorithm](./set_digesthashalgorithm/)(Aspose::Pdf::DigestHashAlgorithm) | Алгоритм хеширования Digest, используемый для метки времени. По умолчанию Sha256. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Номер [Page](../../aspose.pdf/page/), к которому будет применена подпись с меткой времени. |
| [set_Rectangle](./set_rectangle/)(System::Drawing::Rectangle) | [Rectangle](../../aspose.pdf/rectangle/), определяющий область аннотации (игнорируется, когда Visible равно false). |
| [set_ServerUrl](./set_serverurl/)(const System::String\&) | URL сервера метки времени. |
| [set_SigContact](./set_sigcontact/)(const System::String\&) | Контактная информация для подписи. |
| [set_SigLocation](./set_siglocation/)(const System::String\&) | Местоположение подписи. |
| [set_SigReason](./set_sigreason/)(const System::String\&) | Причина подписи. |
| [set_Visible](./set_visible/)(bool) | Флаг видимости – false для чистой метки времени (без видимой аннотации). |
| [TimestampOptions](./timestampoptions/)(const System::String\&, const System::String\&) | Создаёт новый экземпляр с путём к файлу PFX и паролем. |
| [TimestampOptions](./timestampoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Создаёт новый экземпляр с потоком PFX и паролем. |
| [TimestampOptions](./timestampoptions/)() | Создаёт новый экземпляр со значениями по умолчанию. Используется для подписи TSA с файлом PFX. |
## См. также

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
