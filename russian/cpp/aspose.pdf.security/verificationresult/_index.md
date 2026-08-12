---
title: "Aspose::Pdf::Security::VerificationResult класс"
linktitle: "VerificationResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::VerificationResult класс. Представляет результат проверки цифровой подписи в PDF‑файле на C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.security/verificationresult/
---
## VerificationResult class


Представляет результат проверки цифровой подписи в PDF‑файле.

```cpp
class VerificationResult : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_IsCompromised](./get_iscompromised/)() const | Указывает, вероятно ли структура цифровой подписи скомпрометирована. Это означает изменение, позволяющее обойти проверку подписи средствами PDF. См. [Message](../) для получения более подробной информации. |
| [get_Message](./get_message/)() const | Получает сообщение, связанное с результатом проверки. Значение свойства предоставляет дополнительные сведения о результате проверки, такие как описания ошибок или сообщения об успехе. |
| [get_State](./get_state/)() const | Представляет состояние проверки цифровой подписи в PDF‑файле. Указывает, является ли подпись действительной, недействительной или неопределённой. |
| [get_VerificationException](./get_verificationexception/)() const | Получает исключение, связанное с процессом проверки, если оно присутствует. Это свойство предоставляет сведения об ошибках или проблемах, возникших при проверке цифровой подписи в PDF‑файле. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
