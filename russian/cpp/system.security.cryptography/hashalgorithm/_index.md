---
title: "Класс System::Security::Cryptography::HashAlgorithm"
linktitle: "HashAlgorithm"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::HashAlgorithm. Базовый класс для алгоритмов хеширования. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1600
url: /ru/cpp/system.security.cryptography/hashalgorithm/
---
## HashAlgorithm class


Базовый класс для алгоритмов хеширования. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HashAlgorithm : public System::Security::Cryptography::ICryptoTransform
```

## Методы

| Метод | Описание |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Хеширует буфер. |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&, int, int) | Хеширует часть буфера. |
| [ComputeHash](./computehash/)(SharedPtr\<IO::Stream\> const\&) | Читает поток до конца и вычисляет хеш прочитанных данных. |
| static [Create](./create/)(const String\&) | Создаёт алгоритм хеширования по имени. |
| virtual [get_Hash](./get_hash/)() | Получает значение вычисленного хеш‑кода. |
| virtual [get_HashSize](./get_hashsize/)() | Получает размер вычисленного хеш‑значения в байтах. |
| [get_InputBlockSize](./get_inputblocksize/)() override | Размер входного блока. |
| [get_OutputBlockSize](./get_outputblocksize/)() override | Размер выходного блока. |
| virtual [Initialize](./initialize/)() | Сбрасывает хешер в начальное состояние. |
| [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Обрабатывает блок данных и копирует данные в выходной массив. |
| [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) override | Обрабатывает последний блок данных и вычисляет хеш. |
| virtual [~HashAlgorithm](./~hashalgorithm/)() | Деструктор. |
## См. также

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
