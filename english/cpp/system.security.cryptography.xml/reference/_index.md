---
title: System::Security::Cryptography::Xml::Reference class
linktitle: Reference
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Xml::Reference class. Facilitates creation of the XML signatures. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.security.cryptography.xml/reference/
---
## Reference class


Facilitates creation of the XML signatures. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Reference : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddTransform](./addtransform/)(SharedPtr\<Transform\>) |  |
| [get_DigestMethod](./get_digestmethod/)() |  |
| [get_DigestValue](./get_digestvalue/)() |  |
| [get_Id](./get_id/)() |  |
| [get_TransformChain](./get_transformchain/)() |  |
| [get_Type](./get_type/)() |  |
| [get_Uri](./get_uri/)() |  |
| [GetXml](./getxml/)() |  |
| [LoadXml](./loadxml/)(SharedPtr\<System::Xml::XmlElement\>) |  |
| [Reference](./reference/)() |  |
| [Reference](./reference/)(SharedPtr\<IO::Stream\>) |  |
| [Reference](./reference/)(String) |  |
| [set_DigestMethod](./set_digestmethod/)(String) |  |
| [set_DigestValue](./set_digestvalue/)(ArrayPtr\<uint8_t\>) |  |
| [set_Id](./set_id/)(String) |  |
| [set_TransformChain](./set_transformchain/)(SharedPtr\<TransformChain\>) |  |
| [set_Type](./set_type/)(String) |  |
| [set_Uri](./set_uri/)(String) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
