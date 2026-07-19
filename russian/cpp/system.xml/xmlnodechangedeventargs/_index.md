---
title: "Класс System::Xml::XmlNodeChangedEventArgs"
linktitle: "XmlNodeChangedEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlNodeChangedEventArgs. Предоставляет данные для событий XmlDocument::NodeChanged, XmlDocument::NodeChanging, XmlDocument::NodeInserted, XmlDocument::NodeInserting, XmlDocument::NodeRemoved и XmlDocument::NodeRemoving в C++."
type: docs
weight: 2600
url: /ru/cpp/system.xml/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs class


Предоставляет данные для событий **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** и **XmlDocument::NodeRemoving**.

```cpp
class XmlNodeChangedEventArgs : public System::EventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Action](./get_action/)() | Возвращает значение, указывающее тип происходящего события изменения узла. |
| [get_NewParent](./get_newparent/)() | Возвращает значение [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) после завершения операции. |
| [get_NewValue](./get_newvalue/)() | Возвращает новое значение узла. |
| [get_Node](./get_node/)() | Возвращает [XmlNode](../xmlnode/), который добавляется, удаляется или изменяется. |
| [get_OldParent](./get_oldparent/)() | Возвращает значение [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) до начала операции. |
| [get_OldValue](./get_oldvalue/)() | Возвращает исходное значение узла. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/)(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) | Инициализирует новый экземпляр класса [XmlNodeChangedEventArgs](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
