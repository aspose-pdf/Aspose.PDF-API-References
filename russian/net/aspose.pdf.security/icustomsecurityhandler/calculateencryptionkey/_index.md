---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод ICustomSecurityHandler. Вычисляет EncryptionKey. Обычно ключ рассчитывается на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры на момент вызова. Это значение передаётся в качестве аргумента key в Encrypt и Decrypt."
type: docs
weight: 60
url: /ru/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Вычисляет EncryptionKey. Обычно ключ рассчитывается на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры на момент вызова. Это значение передаётся в качестве аргумента key в [`Encrypt`](../encrypt/) и [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | String | Пароль, введённый пользователем. |

### Возвращаемое значение

Массив ключа шифрования.

### См. также

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


