---
title: "Класс Aspose::Pdf::Security::ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Security::ValidationOptions. Представляет параметры для проверки цифровой подписи в PDF‑документе в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.pdf.security/validationoptions/
---
## ValidationOptions class


Представляет параметры для проверки цифровой подписи в PDF‑документе.

```cpp
class ValidationOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CheckCertificateChain](./get_checkcertificatechain/)() const | Возвращает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. |
| [get_RequestTimeout](./get_requesttimeout/)() const | Возвращает продолжительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP. |
| [get_ValidationMethod](./get_validationmethod/)() const | Возвращает метод, используемый для проверки сертификата. |
| [get_ValidationMode](./get_validationmode/)() const | Возвращает режим проверки цифровых подписей в PDF‑документе. Свойство [ValidationMode](../validationmode/) определяет строгиесть процесса проверки. |
| [set_CheckCertificateChain](./set_checkcertificatechain/)(bool) | Устанавливает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. |
| [set_RequestTimeout](./set_requesttimeout/)(int32_t) | Устанавливает продолжительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP. |
| [set_ValidationMethod](./set_validationmethod/)(Aspose::Pdf::Security::ValidationMethod) | Устанавливает метод, используемый для проверки сертификата. |
| [set_ValidationMode](./set_validationmode/)(Aspose::Pdf::Security::ValidationMode) | Устанавливает режим проверки цифровых подписей в PDF‑документе. Свойство [ValidationMode](../validationmode/) определяет строгиесть процесса проверки. |
| [ValidationOptions](./validationoptions/)() | Создаёт экземпляр класса [ValidationOptions](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
