---
title: "Метод System::Equals< float, float >"
linktitle: "Equals< float, float >"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Equals< float, float >. Специализация для значений одинарной точности с плавающей запятой. Хотя два значения NaN в плавающей точке определены IEC 60559:1989 как всегда неравные, контракт System.Object.Equals требует, чтобы переопределения удовлетворяли требованиям оператора эквивалентности. Поэтому System.Double.Equals и System.Single.Equals возвращают True при сравнении двух NaN, тогда как оператор равенства возвращает False в этом случае, как того требует стандарт C++."
type: docs
weight: 18900
url: /ru/cpp/system/equals_float,float_/
---
## System::Equals< float, float > method


Специализация для значений одинарной точности с плавающей запятой. Хотя два значения NaN в плавающей точке определены IEC 60559:1989 как всегда неравные, контракт для [System.Object.Equals](../object/equals/) требует, чтобы переопределения удовлетворяли требованиям оператора эквивалентности. Поэтому System.Double.Equals и System.Single.Equals возвращают True при сравнении двух NaN, тогда как оператор равенства возвращает False в этом случае, как того требует стандарт.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const float\& | Первый сравниваемый операнд |
| b | const float\& | Второй сравниваемый операнд |

### ReturnValue

True, если оба значения NaN или равны, иначе — false

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
