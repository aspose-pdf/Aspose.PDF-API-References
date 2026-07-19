---
title: "System::Collections::BitArray::Enumerator класс"
linktitle: "Перечислитель"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::BitArray::Enumerator класс. Тип перечислителя для целей итерации в C++."
type: docs
weight: 2900
url: /ru/cpp/system.collections/bitarray/enumerator/
---
## Enumerator class


[Enumerator](./) type for iteration purposes.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<bool>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<BitArray\>\&) | Создаёт перечислитель. |
| [get_Current](./get_current/)() const override | Получает адресованный бит в булевой форме. |
| [MoveNext](./movenext/)() override | Переходит к следующему биту. |
| [Reset](./reset/)() override | Сбрасывает перечислитель в позицию перед первым элементом. |
## См. также

* Class [Object](../../../system/object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [BitArray](../)
* Namespace [System::Collections](../../)
* Library [Aspose.PDF for C++](../../../)
