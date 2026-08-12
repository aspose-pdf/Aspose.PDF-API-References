---
title: "System::Collections::Specialized::NameValueCollection klass"
linktitle: "NameValueCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Specialized::NameValueCollection klass. Samling av associerade String-nycklar och String-värden som kan nås antingen med nyckeln eller med indexet i C++."
type: docs
weight: 200
url: /sv/cpp/system.collections.specialized/namevaluecollection/
---
## NameValueCollection class


Samling av associerade [String](../../system/string/) nycklar och [String](../../system/string/) värden som kan nås antingen med nyckeln eller med indexet.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const String\&) override | Åsidosätt [ICollection](../../system.collections/icollection/) metod - inte implementerad. |
| [Add](./add/)(const System::SharedPtr\<NameValueCollection\>\&) | Kopierar posterna i den angivna [NameValueCollection](./) till den aktuella. |
| virtual [Add](./add/)(const String\&, const String\&) | Lägger till en post med det angivna namnet och värdet. |
| [Clear](./clear/)() override | Raderar alla element. |
| [Contains](./contains/)(const String\&) const override | Kontrollerar om objektet finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override | Kopierar samlingselement till befintliga arrayelement. |
| virtual [Get](./get/)(const String\&) | Hämtar värdena som är associerade med den angivna nyckeln. |
| virtual [get_AllKeys](./get_allkeys/)() | Hämtar alla nycklar. |
| [get_Count](./get_count/)() const override | Hämtar antalet nyckel/värde-par. |
| virtual [get_Keys](./get_keys/)() | Hämtar alla nycklar. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom samlingen. |
| virtual [GetValues](./getvalues/)(const String\&) | Hämtar värdena som är associerade med den angivna nyckeln. |
| [HasKeys](./haskeys/)() | Hämtar ett värde som indikerar om [NameValueCollection](./) innehåller nycklar som inte är null. |
| [idx_get](./idx_get/)(const String\&) | Hämtar värdet vid angivet index. |
| [idx_set](./idx_set/)(const String\&, const String\&) | Sätter värdet för en post. |
| [NameValueCollection](./namevaluecollection/)() | Initierar en ny instans av [NameValueCollection](./)-klassen som är tom. |
| [NameValueCollection](./namevaluecollection/)(const System::SharedPtr\<NameValueCollection\>\&) | Kopierar posterna från den angivna [NameValueCollection](./) till en ny [NameValueCollection](./). |
| [Remove](./remove/)(const String\&) override | Tar bort specifikt objekt. |
| virtual [Set](./set/)(const String\&, const String\&) | Sätter värdet för en post. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
