---
title: "System::Windows::Forms::Control::ControlCollection klass"
linktitle: "ControlCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Windows::Forms::Control::ControlCollection klass. Samling av kontroller. Inte implementerad i C++."
type: docs
weight: 200
url: /sv/cpp/system.windows.forms/control/controlcollection/
---
## ControlCollection class


Samling av kontroller. Inte implementerad.

```cpp
class ControlCollection : public System::Collections::Generic::IList<System::SharedPtr<Control>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Control\>\&) override | Lägger till kontroll i samlingen. |
| virtual [AddRange](./addrange/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>) | Lägger till flera kontroller i samlingen. |
| [Clear](./clear/)() override | Tar bort alla kontroller från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Control\>\&) const override | Kontrollerar om en specifik kontroll finns i samlingen. |
| virtual [ContainsKey](./containskey/)(System::String) const | Kontrollerar om en kontroll med ett specifikt namn finns i samlingen. |
| [ControlCollection](./controlcollection/)(const System::SharedPtr\<Control\>\&) | Konstruktor. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>, int) override | Kopierar samlingens innehåll till befintliga arrayelement. |
| [Find](./find/)(const System::String\&, bool) const | Söker efter den namngivna kontrollen i samlingen. Kontrollerar eventuellt de innehållna kontrollernas samlingar rekursivt. |
| [get_Count](./get_count/)() const override | Hämtar antalet kontroller i samlingen. |
| [get_Owner](./get_owner/)() const | Hämtar samlingens ägarkontroll. |
| [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&) const | Söker efter specifik kontroll. |
| virtual [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&, bool) const | Söker efter specifik kontroll. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom samlingen. |
| [idx_get](./idx_get/)(int) const override | Åtkomst via index. |
| virtual [idx_get](./idx_get/)(System::String) const | Åtkomst via namn. |
| [idx_set](./idx_set/)(int, System::SharedPtr\<Control\>) override | Åtkomst via index. |
| virtual [idx_set](./idx_set/)(System::String, System::SharedPtr\<Control\>) | Åtkomst via namn. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Control\>\&) const override | Söker efter kontroll i samlingen. |
| virtual [IndexOfKey](./indexofkey/)(System::String) const | Söker efter namngiven kontroll i samlingen. |
| [Insert](./insert/)(int, const System::SharedPtr\<Control\>\&) override | Infogar kontroll i samlingen. |
| [Remove](./remove/)(const System::SharedPtr\<Control\>\&) override | Tar bort kontroll från samlingen. |
| [RemoveAt](./removeat/)(int) override | Tar bort kontroll från samlingen. |
| virtual [RemoveByKey](./removebykey/)(System::String) | Tar bort kontroll från samlingen. |
| virtual [SetChildIndex](./setchildindex/)(const System::SharedPtr\<Control\>\&, int) | Flyttar kontroll till en ny position. |
## Se även

* Class [IList](../../../system.collections.generic/ilist/)
* Class [Control](../)
* Namespace [System::Windows::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
