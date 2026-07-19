---
title: "Класс System::Xml::XmlProcessingInstruction"
linktitle: "XmlProcessingInstruction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlProcessingInstruction. Представляет инструкцию обработки, которую XML определяет для хранения специфической для процессора информации в тексте документа в C++."
type: docs
weight: 3100
url: /ru/cpp/system.xml/xmlprocessinginstruction/
---
## XmlProcessingInstruction class


Представляет инструкцию обработки, которую XML определяет для сохранения специфической для процессора информации в тексте документа.

```cpp
class XmlProcessingInstruction : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_Data](./get_data/)() | Возвращает содержимое инструкции обработки, исключая цель. |
| [get_InnerText](./get_innertext/)() override | Возвращает конкатенированные значения узла и всех его дочерних узлов. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_Target](./get_target/)() | Возвращает цель инструкции обработки. |
| [get_Value](./get_value/)() override | Возвращает значение узла. |
| [set_Data](./set_data/)(const String\&) | Устанавливает содержимое инструкции обработки, исключая цель. |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает конкатенированные значения узла и всех его дочерних элементов. |
| [set_Value](./set_value/)(String) override | Устанавливает значение узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). Поскольку узлы ProcessingInstruction не имеют дочерних элементов, этот метод не оказывает влияния. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
