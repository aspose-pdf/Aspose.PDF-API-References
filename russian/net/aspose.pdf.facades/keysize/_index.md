---
title: KeySize
second_title: Aspose.PDF для справочника API .NET
description: Определяет различные размеры ключей которые можно использовать для шифрования pdf-документов.
type: docs
weight: 2400
url: /ru/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Определяет различные размеры ключей, которые можно использовать для шифрования pdf-документов.

```csharp
public enum KeySize
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| x40 | `0` | 40-битный ключ. Такой размер ключа используется с алгоритмом RC4 и обеспечивает низкий уровень безопасности. Тем не менее, старые версии pdf-документов могут быть зашифрованы только такими ключами (версия 1.3 и ниже); |
| x128 | `1` | 128-битный ключ. Алгоритмы RC4 и AES могут использовать такой размер ключа. |
| x256 | `2` | 256-битный ключ. Такой размер ключа может использоваться только с AES и распознается последними версиями Adobe Reader (начиная с v.9). |

### Смотрите также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->