---
title: "System::Security::Cryptography::CipherMode перечисление"
linktitle: "CipherMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::CipherMode перечисление. Режим блочного шифрования в C++."
type: docs
weight: 5300
url: /ru/cpp/system.security.cryptography/ciphermode/
---
## CipherMode enum


Режим блочного шифра. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
enum class CipherMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining, который комбинирует текущий блок с предыдущим для улучшения шифрования. |
| ECB | 2 | Режим Electronic codebook без влияния между блоками; приводит к более слабому шифрованию. |
| OFB | 3 | Режим Output feedback, который обрабатывает большие входные блоки небольшими частями. |
| CFB | 4 | Режим Cipher feedback, который обрабатывает большие входные блоки небольшими частями. Правила перемешивания отличаются от правил OFB. |
| CTS | 5 | Режим Cipher text stealing, ведёт себя как CBC для всех блоков, кроме двух последних. |

## См. также

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
