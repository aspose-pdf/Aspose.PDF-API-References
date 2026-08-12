---
title: "Класс Aspose::Pdf::Security::ICustomSecurityHandler"
linktitle: "ICustomSecurityHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Security::ICustomSecurityHandler. Интерфейс пользовательского обработчика безопасности на C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler class


Интерфейс пользовательского обработчика безопасности.

```cpp
class ICustomSecurityHandler : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CalculateEncryptionKey](./calculateencryptionkey/)(System::String) | Вычислите EncryptionKey. Обычно ключ рассчитывается на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры во время вызова. Это значение передаётся в качестве аргумента key в [Encrypt](./encrypt/) и [Decrypt](./decrypt/). |
| virtual [Decrypt](./decrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Расшифруйте массив данных. |
| virtual [Encrypt](./encrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Зашифруйте массив данных. |
| virtual [EncryptPermissions](./encryptpermissions/)(int32_t) | Зашифруйте поле разрешений документа. Результат будет записан в поле словаря шифрования Perms. При открытии документа значение можно получить в [EncryptionParameters](../encryptionparameters/) через поле Perms. Позволяет проверить, изменились ли разрешения документа. |
| virtual [get_Filter](./get_filter/)() | Получает имя фильтра. |
| virtual [get_KeyLength](./get_keylength/)() | Получает длину ключа. |
| virtual [get_Revision](./get_revision/)() | Получает ревизию обработчика или алгоритма шифрования. |
| virtual [get_SubFilter](./get_subfilter/)() | Получает имя подфильтра. |
| virtual [get_Version](./get_version/)() | Получает версию обработчика или алгоритма шифрования. |
| virtual [GetOwnerKey](./getownerkey/)(System::String, System::String) | Создаёт закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пользовательский пароль можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Значение будет доступно в [CalculateEncryptionKey](./calculateencryptionkey/) для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут не быть указаны или может быть указана только одна. |
| virtual [GetUserKey](./getuserkey/)(System::String) | Создаёт закодированный массив на основе пароля пользователя. Это значение обычно используется для проверки, принадлежит ли пароль пользователю или владельцу, и для получения ключа шифрования. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Указанный пользователем пароль передаётся в качестве аргумента при вызове шифрования документа. |
| virtual [Initialize](./initialize/)(System::SharedPtr\<EncryptionParameters\>) | Вызывается для инициализации текущего экземпляра для шифрования. [Note](../../aspose.pdf/note/) что при шифровании он будет заполнен данными переданных свойств [ICustomSecurityHandler](./), а при открытии документа из словаря шифрования. Если метод вызывается во время нового шифрования, то [EncryptionParameters::UserKey](../) и [EncryptionParameters::OwnerKey](../) будут равны null. |
| virtual [IsOwnerPassword](./isownerpassword/)(System::String) | Проверьте, является ли пароль паролем владельца документа. Метод вызывается после Initialize. Вызов метода используется в PDF API. |
| virtual [IsUserPassword](./isuserpassword/)(System::String) | Проверьте, принадлежит ли пароль пользователю (пароль для открытия документа). Метод вызывается после Initialize. Вызов метода используется в PDF API. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
