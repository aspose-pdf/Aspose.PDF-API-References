---
title: "System::Runtime::Serialization::SerializationInfo::SerializationInfo конструктор"
linktitle: "SerializationInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::SerializationInfo::SerializationInfo конструктор. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo constructor


Информация RTTI.

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const System::TypeInfo\& | Тип [System::TypeInfo](../../../system/typeinfo/) объекта для сериализации. |
| converter | const System::SharedPtr\<IFormatterConverter\>\& | Экземпляр [IFormatterConverter](../../iformatterconverter/) используется при десериализации. |
## Примечания


Создаёт новый экземпляр класса [SerializationInfo](../).
## См. также

* Class [TypeInfo](../../../system/typeinfo/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatterConverter](../../iformatterconverter/)
* Class [SerializationInfo](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
