---
title: "Интерфейс ICustomSecurityHandler"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Интерфейс Aspose.Pdf.Security.ICustomSecurityHandler. Пользовательский интерфейс обработчика безопасности"
type: docs
weight: 10150
url: /ru/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

Интерфейс пользовательского обработчика безопасности.

```csharp
public interface ICustomSecurityHandler
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Получает имя фильтра. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Получает длину ключа. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Получает ревизию обработчика или алгоритма шифрования. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Получает имя субфильтра. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Получает версию обработчика или алгоритма шифрования. |

## Методы

| Имя | Описание |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Вычислить EncryptionKey. Обычно ключ вычисляется на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры на момент вызова. Это значение передаётся в качестве аргумента key в [`Encrypt`](./encrypt/) и [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Расшифровать массив данных. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Зашифровать массив данных. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Зашифровать поле разрешений документа. Результат будет записан в поле словаря шифрования Perms. При открытии документа значение можно получить в [`EncryptionParameters`](../encryptionparameters/) через поле Perms. Позволяет проверить, изменились ли разрешения документа. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Создаёт закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пользовательский пароль можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для подготовки и заполнения словаря шифрования. Значение будет доступно в [`CalculateEncryptionKey`](./calculateencryptionkey/) для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут не быть указаны или может быть указан только один. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Создаёт закодированный массив на основе пароля пользователя. Это значение обычно используется для проверки, принадлежит ли пароль пользователю или владельцу, и для получения ключа шифрования. Вызывается во время шифрования для подготовки и заполнения словаря шифрования. Указанный пользователем пароль передаётся в качестве аргумента при вызове шифрования документа. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Вызывается для инициализации текущего экземпляра для шифрования. Обратите внимание, что при шифровании он будет заполнен данными переданных свойств `ICustomSecurityHandler`, а при открытии документа из словаря шифрования. Если метод вызывается во время нового шифрования, то [`UserKey`](../encryptionparameters/userkey/) и [`OwnerKey`](../encryptionparameters/ownerkey/) будут равны null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Проверьте, является ли пароль паролем владельца документа. Метод вызывается после Initialize. Вызов метода используется в PDF API. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Проверьте, принадлежит ли пароль пользователю (пароль для открытия документа). Метод вызывается после Initialize. Вызов метода используется в PDF API. |

### См. также

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


