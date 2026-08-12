---
title: "Класс System::Security::Cryptography::ICspAsymmetricAlgorithm"
linktitle: "ICspAsymmetricAlgorithm"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::ICspAsymmetricAlgorithm. Базовый класс для асимметричных алгоритмов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.security.cryptography/icspasymmetricalgorithm/
---
## ICspAsymmetricAlgorithm class


Базовый класс для асимметричных алгоритмов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ICspAsymmetricAlgorithm : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [ExportCspBlob](./exportcspblob/)(bool) | Экспортирует блоб с информацией о ключе. |
| virtual [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() | Информация RTTI. |
| virtual [ImportCspBlob](./importcspblob/)(ByteArrayPtr) | Импортирует информацию о ключе из блоба данных. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
