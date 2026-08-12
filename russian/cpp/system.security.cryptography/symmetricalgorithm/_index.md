---
title: "System::Security::Cryptography::SymmetricAlgorithm класс"
linktitle: "SymmetricAlgorithm"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::SymmetricAlgorithm. Симметричный алгоритм, использующий один и тот же ключ для шифрования и дешифрования, базовый класс. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 4900
url: /ru/cpp/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm class


Симметричный алгоритм, использующий один и тот же ключ для шифрования и дешифрования, базовый класс. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)(const String\&) | Создаёт экземпляр алгоритма. |
| virtual [CreateDecryptor](./createdecryptor/)() | Создаёт дешифратор с параметрами, связанными с объектом алгоритма. |
| virtual [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Создаёт дешифратор с явными параметрами. |
| virtual [CreateEncryptor](./createencryptor/)() | Создаёт шифратор с параметрами, связанными с объектом алгоритма. |
| virtual [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Создаёт шифратор с явными параметрами. |
| virtual [GenerateIV](./generateiv/)() | Генерирует случайное начальное значение для алгоритма. Перезаписывает существующее (если есть). |
| virtual [GenerateKey](./generatekey/)() | Генерирует случайный ключ для алгоритма. Перезаписывает существующий (если есть). |
| virtual [get_BlockSize](./get_blocksize/)() | Получает размер блока криптографической операции. |
| virtual [get_FeedbackSize](./get_feedbacksize/)() | Получает размер обратной связи криптографической операции. |
| virtual [get_IV](./get_iv/)() | Получает начальное значение криптографической операции. Создаёт новое, если ещё не создано. |
| virtual [get_Key](./get_key/)() | Получает ключ криптографической операции. Создаёт новый, если ещё не создан. |
| virtual [get_KeySize](./get_keysize/)() | Получает размер ключа криптографической операции. |
| virtual [get_Mode](./get_mode/)() | Получает режим криптографической операции. |
| virtual [get_Padding](./get_padding/)() | Получает заполнение криптографической операции. |
| virtual [set_BlockSize](./set_blocksize/)(int) | Устанавливает размер блока криптографической операции. |
| virtual [set_FeedbackSize](./set_feedbacksize/)(int) | Устанавливает размер обратной связи криптографической операции. |
| virtual [set_IV](./set_iv/)(System::ArrayPtr\<uint8_t\>) | Устанавливает начальное значение криптографической операции. |
| virtual [set_Key](./set_key/)(System::ArrayPtr\<uint8_t\>) | Устанавливает ключ криптографической операции. |
| virtual [set_KeySize](./set_keysize/)(int) | Устанавливает размер ключа криптографической операции. |
| virtual [set_Mode](./set_mode/)(CipherMode) | Устанавливает режим криптографической операции. |
| virtual [set_Padding](./set_padding/)(PaddingMode) | Устанавливает заполнение криптографической операции. |
| [ValidKeySize](./validkeysize/)(int) | Проверяет, является ли размер ключа допустимым. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
