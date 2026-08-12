---
title: "System::Collections::Specialized::BitVector32 класс"
linktitle: "BitVector32"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Specialized::BitVector32 класс. Предоставляет простой лёгкий битовый вектор с удобным целочисленным или Boolean доступом к 32‑битному хранилищу в C++."
type: docs
weight: 100
url: /ru/cpp/system.collections.specialized/bitvector32/
---
## BitVector32 class


Предоставляет простой лёгкий битовый вектор с удобным целочисленным или [Boolean](../../system/boolean/) доступом к 32‑битному хранилищу.

```cpp
class BitVector32
```

## Nested classes

* Class [Section](./section/)
## Методы

| Метод | Описание |
| --- | --- |
| [BitVector32](./bitvector32/)() | Инициализирует новый пустой экземпляр [BitVector32](./). |
| [BitVector32](./bitvector32/)(int32_t) | Инициализирует новый экземпляр структуры [BitVector32](./) с указанными внутренними данными. |
| [BitVector32](./bitvector32/)(const BitVector32\&) | Инициализирует новый экземпляр структуры [BitVector32](./) с информацией из указанного значения. |
| static [CreateMask](./createmask/)() | Создаёт первую маску в серии. |
| static [CreateMask](./createmask/)(int32_t) | Создаёт следующую маску в серии. |
| static [CreateSection](./createsection/)(int16_t) | Создаёт первый раздел в серии с указанным максимальным значением. |
| static [CreateSection](./createsection/)(int16_t, BitVector32::Section) | Создаёт следующий раздел в серии с указанным максимальным значением. |
| [Equals](./equals/)(const BitVector32\&) | Определяет, является ли указанный объект тем же, что и текущий. |
| [get_Data](./get_data/)() | возвращает необработанные данные, хранящиеся в этом битовом векторе... |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего объекта. |
| [idx_get](./idx_get/)(int32_t) | Получает значение, указывающее, установлены ли все указанные биты. |
| [idx_get](./idx_get/)(BitVector32::Section) | Получает значение для указанного раздела. |
| [idx_set](./idx_set/)(int32_t, bool) | Устанавливает значение, указывающее, установлены ли все указанные биты. |
| [idx_set](./idx_set/)(BitVector32::Section, int32_t) | Устанавливает значение для указанного раздела. |
| static [ToString](./tostring/)(const BitVector32\&) | Преобразует значение, представленное параметром value, в строку. |
| [ToString](./tostring/)() const | Преобразует значение, представленное текущим объектом, в строку. |
## См. также

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
