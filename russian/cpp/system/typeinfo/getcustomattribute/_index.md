---
title: "Метод System::TypeInfo::GetCustomAttribute"
linktitle: "GetCustomAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::TypeInfo::GetCustomAttribute. Ищет пользовательский атрибут заданного типа, применённый к типу, представленному текущим объектом, в C++."
type: docs
weight: 3000
url: /ru/cpp/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute method


Ищет пользовательский атрибут указанного типа, применённый к типу, представленного текущим объектом.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeType | const TypeInfo\& | Константная ссылка на объект [TypeInfo](../), представляющий тип атрибута для поиска |

### ReturnValue

Указатель на объект, представляющий найденный атрибут, или нулевой указатель, если атрибут, соответствующий критериям поиска, не найден

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
