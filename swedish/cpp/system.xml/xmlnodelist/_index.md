---
title: "System::Xml::XmlNodeList-klass"
linktitle: "XmlNodeList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeList-klass. Representerar en ordnad samling av noder i C++."
type: docs
weight: 2700
url: /sv/cpp/system.xml/xmlnodelist/
---
## XmlNodeList class


Representerar en ordnad samling noder.

```cpp
class XmlNodeList : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                    public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_Count](./get_count/)() | Returnerar antalet noder i [XmlNodeList](./). |
| virtual [GetEnumerator](./getenumerator/)() | Tillhandahåller stöd för iteration över samlingen av noder i [XmlNodeList](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Returnerar en nod på det angivna indexet. |
| virtual [Item](./item/)(int32_t) | Hämtar en nod på det angivna indexet. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
