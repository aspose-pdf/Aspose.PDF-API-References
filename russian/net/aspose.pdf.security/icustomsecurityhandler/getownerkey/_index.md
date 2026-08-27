---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод ICustomSecurityHandler. Создаёт закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пароль пользователя можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для подготовки и заполнения словаря шифрования. Значение будет доступно в CalculateEncryptionKey для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут быть не указаны или может быть указан только один."
type: docs
weight: 100
url: /ru/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Создаёт закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пароль пользователя можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для подготовки и заполнения словаря шифрования. Значение будет доступно в [`CalculateEncryptionKey`](../calculateencryptionkey/) для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут быть не указаны или может быть указан только один.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |

### Возвращаемое значение

Массив ключа владельца.

### См. также

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


