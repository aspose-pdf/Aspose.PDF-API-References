---
title: "Aspose::Pdf::Operator-klass"
linktitle: "Operator"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Operator-klass. Abstrakt klass som representerar en operator i C++."
type: docs
weight: 12000
url: /sv/cpp/aspose.pdf/operator/
---
## Operator class


Abstrakt klass som representerar operatör.

```cpp
class Operator : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Accepterar besökare [IOperatorSelector](../ioperatorselector/) som tillhandahåller bearbetning av operatorer. |
| [get_Index](./get_index/)() | [Operator](./) index i listan över sidoperatorer. |
| static [IsTextShowOperator](./istextshowoperator/)(const System::SharedPtr\<Operator\>\&) | Bestämmer om operatorn är en operator som ansvarar för textutmatning (Tj, TJ, etc). |
| [set_Index](./set_index/)(int32_t) | [Operator](./) index i listan över sidoperatorer. |
| [ToString](./tostring/)() const override | Returnerar texten för operatorn och dess parametrar. |
| [ValueEquals](./valueequals/)(const System::SharedPtr\<Operator\>\&) | Jämför den här instansen med det angivna objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
