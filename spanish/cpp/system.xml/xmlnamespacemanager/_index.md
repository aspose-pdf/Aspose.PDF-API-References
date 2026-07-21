---
title: "Clase System::Xml::XmlNamespaceManager"
linktitle: "XmlNamespaceManager"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlNamespaceManager. Resuelve, agrega y elimina espacios de nombres en una colección y proporciona gestión de alcance para estos espacios de nombres en C++."
type: docs
weight: 2300
url: /es/cpp/system.xml/xmlnamespacemanager/
---
## XmlNamespaceManager class


Resuelve, agrega y elimina espacios de nombres en una colección y proporciona gestión de alcance para estos espacios de nombres.

```cpp
class XmlNamespaceManager : public System::Xml::IXmlNamespaceResolver,
                            public System::Collections::Generic::IEnumerable<String>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddNamespace](./addnamespace/)(String, String) | Agrega el espacio de nombres proporcionado a la colección. |
| virtual [get_DefaultNamespace](./get_defaultnamespace/)() | Devuelve el URI del espacio de nombres para el espacio de nombres predeterminado. |
| virtual [get_NameTable](./get_nametable/)() | Devuelve la [XmlNameTable](../xmlnametable/) asociada con este objeto. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para usar al iterar a través de los espacios de nombres en el [XmlNamespaceManager](./). |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Devuelve una colección de nombres de espacios de nombres indexados por prefijo que pueden usarse para enumerar los espacios de nombres actualmente en alcance. |
| virtual [HasNamespace](./hasnamespace/)(String) | Devuelve un valor que indica si el prefijo proporcionado tiene un espacio de nombres definido para el alcance actual empujado. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Devuelve el URI del espacio de nombres para el prefijo especificado. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Encuentra el prefijo declarado para el URI de espacio de nombres dado. |
| virtual [PopScope](./popscope/)() | Quita un alcance de espacio de nombres de la pila. |
| virtual [PushScope](./pushscope/)() | Empuja un alcance de espacio de nombres a la pila. |
| virtual [RemoveNamespace](./removenamespace/)(String, String) | Elimina el espacio de nombres dado para el prefijo especificado. |
| [XmlNamespaceManager](./xmlnamespacemanager/)(const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlNamespaceManager](./) con la [XmlNameTable](../xmlnametable/) especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
