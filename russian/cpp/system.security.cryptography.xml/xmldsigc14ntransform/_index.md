---
title: "System::Security::Cryptography::Xml::XmlDsigC14NTransform класс"
linktitle: "XmlDsigC14NTransform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::Xml::XmlDsigC14NTransform класс. Представляет трансформацию канонизации XML C14N для цифровой подписи без комментариев. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1400
url: /ru/cpp/system.security.cryptography.xml/xmldsigc14ntransform/
---
## XmlDsigC14NTransform class


Представляет трансформацию канонизации XML C14N для цифровой подписи без комментариев. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class XmlDsigC14NTransform : public System::Security::Cryptography::Xml::Transform
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_InputTypes](./get_inputtypes/)() override |  |
| [get_OutputTypes](./get_outputtypes/)() override |  |
| [GetDigestedOutput](./getdigestedoutput/)(SharedPtr\<HashAlgorithm\>) override |  |
| [GetOutput](./getoutput/)() override |  |
| [GetOutput](./getoutput/)(const TypeInfo\&) override |  |
| [LoadInnerXml](./loadinnerxml/)(SharedPtr\<System::Xml::XmlNodeList\>) override |  |
| [LoadInput](./loadinput/)(SharedPtr\<Object\>) override |  |
| [XmlDsigC14NTransform](./xmldsigc14ntransform/)() |  |
| [XmlDsigC14NTransform](./xmldsigc14ntransform/)(bool) |  |
## См. также

* Class [Transform](../transform/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
