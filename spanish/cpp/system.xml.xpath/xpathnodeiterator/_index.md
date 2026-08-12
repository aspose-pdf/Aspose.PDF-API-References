---
title: "System::Xml::XPath::XPathNodeIterator class"
linktitle: "XPathNodeIterator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNodeIterator class. Proporciona un iterador sobre un conjunto seleccionado de nodos en C++."
type: docs
weight: 600
url: /es/cpp/system.xml.xpath/xpathnodeiterator/
---
## XPathNodeIterator class


Proporciona un iterador sobre un conjunto seleccionado de nodos.

```cpp
class XPathNodeIterator : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XPath::XPathNavigator>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clone](./clone/)() | Cuando se sobrescribe en una clase derivada, devuelve una copia de este objeto [XPathNodeIterator](./). |
| virtual [get_Count](./get_count/)() | Devuelve el índice del último nodo en el conjunto seleccionado de nodos. |
| virtual [get_Current](./get_current/)() | Cuando se sobrescribe en una clase derivada, obtiene el objeto [XPathNavigator](../xpathnavigator/) para este [XPathNodeIterator](./), posicionado en el nodo de contexto actual. |
| virtual [get_CurrentPosition](./get_currentposition/)() | Cuando se sobrescribe en una clase derivada, obtiene el índice de la posición actual en el conjunto seleccionado de nodos. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un objeto IEnumerator para iterar a través del conjunto de nodos seleccionado. |
| virtual [MoveNext](./movenext/)() | Cuando se sobrescribe en una clase derivada, mueve el objeto [XPathNavigator](../xpathnavigator/) devuelto por el método [XPathNodeIterator::get_Current](./get_current/) al siguiente nodo en el conjunto de nodos seleccionado. |
| [XPathNodeIterator](./xpathnodeiterator/)() | Inicializa una nueva instancia de la clase [XPathNodeIterator](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
