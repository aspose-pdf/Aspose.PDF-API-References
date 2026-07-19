---
title: "System::Text::RegularExpressions::Match класс"
linktitle: "Match"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::Match класс. Единственное совпадение регулярного выражения со строкой. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.text.regularexpressions/match/
---
## Match class


[Single](../../system/single/) match of regexp over string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Добавляет захват в совпадение. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Добавляет группу в совпадение. |
| static [get_Empty](./get_empty/)() | Доступ к пустому совпадению. |
| [get_Groups](./get_groups/)() | Получает список групп. |
| [Match](./match/)(const UStringPtr\&, int, int) | Конструктор. |
| [NextMatch](./nextmatch/)() | Итерация по совпадениям. |
| virtual [Result](./result/)(const String\&) | Форматирует строку, заменяя ссылки на подсовпадения их значениями. |
| [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
## См. также

* Class [Group](../group/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
