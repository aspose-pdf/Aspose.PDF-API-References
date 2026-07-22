---
title: "Aspose::Pdf::Operators::SetDash-klass"
linktitle: "SetDash"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Operators::SetDash-klass. Klass som representerar d-operatorn (sätt linjedash-mönster) i C++."
type: docs
weight: 5800
url: /sv/cpp/aspose.pdf.operators/setdash/
---
## SetDash class


Klass som representerar d-operatorn (ställer in linjestreckmönster).

```cpp
class SetDash : public Aspose::Pdf::Operator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepterar besöksobjekt för att bearbeta operatorn. |
| [get_Pattern](./get_pattern/)() const | Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Om arrayen har ett enda element är streck- och mellanrumslängderna lika. |
| [get_Phase](./get_phase/)() const | Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna av streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska kontureringen av banan börja, och dash-arrayen ska användas cykliskt från den punkten och framåt. |
| [set_Pattern](./set_pattern/)(const System::ArrayPtr\<int32_t\>\&) | Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Om arrayen har ett enda element är streck- och mellanrumslängderna lika. |
| [set_Phase](./set_phase/)(int32_t) | Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna av streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska kontureringen av banan börja, och dash-arrayen ska användas cykliskt från den punkten och framåt. |
| [SetDash](./setdash/)(const System::ArrayPtr\<int32_t\>\&, int32_t) | Skapar dash-mönsteroperator. |
| [ToString](./tostring/)() const override | Hämtar operatorns strängrepresentation. |
## Se även

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
