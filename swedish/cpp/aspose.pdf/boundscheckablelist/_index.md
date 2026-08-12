---
title: "Aspose::Pdf::BoundsCheckableList klass"
linktitle: "BoundsCheckableList"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::BoundsCheckableList klass. Representerar BoundsCheckableList – en wrapper runt System.Collections.Generic.List i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf/boundscheckablelist/
---
## BoundsCheckableList class


Representerar [BoundsCheckableList](./) – wrapper runt [System.Collections.Generic.List](../../system.collections.generic/list/).

```cpp
template<typename T>class BoundsCheckableList : public System::Collections::Generic::IList<T>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Lägger till ett objekt i slutet av [System.Collections.Generic.List](../../system.collections.generic/list/) beroende på parametern \"boundsCheckMode\". |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [BoundsCheckableList](./boundscheckablelist/)() | Initierar en ny instans av klassen [BoundsCheckableList](./). |
| [BoundsCheckableList](./boundscheckablelist/)(BoundsCheckMode, double, double) | Initierar en ny instans av klassen [BoundsCheckableList](./). |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [Clear](./clear/)() override | Tar bort alla element från [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Contains](./contains/)(const T\&) const override | Bestämmer om ett element finns i [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Kopierar hela [System.Collections.Generic.List](../../system.collections.generic/list/) till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [get_Count](./get_count/)() const override | Hämtar antalet element som finns i [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar värdet som indikerar om samlingen är skrivskyddad. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [idx_get](./idx_get/)(int32_t) const override | Hämtar paragraf från eller till samlingen. |
| [idx_set](./idx_set/)(int32_t, T) override | Ställer in paragraf från eller till samlingen. |
| [IndexOf](./indexof/)(const T\&) const override | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten i hela [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Insert](./insert/)(int32_t, const T\&) override | Infogar ett element i [System.Collections.Generic.List](../../system.collections.generic/list/) på det angivna indexet. |
| [Remove](./remove/)(const T\&) override | Tar bort den första förekomsten av ett specifikt objekt från [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [RemoveAt](./removeat/)(int32_t) override | Tar bort elementet på det angivna indexet i [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode, double, double) | Uppdaterar parametern boundsCheckMode för den initierade samlingen. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode) | Uppdaterar parametern boundsCheckMode för den initierade samlingen. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [iterator](./iterator/) | Iterator-typ. |
| [iterator_holder_type](./iterator_holder_type/) | En samlingstyp vars iteratorer används som iteratorer i den aktuella samlingen. |
| [virtualized_iterator](./virtualized_iterator/) | Virtualiserad typ. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Virtualiserad elementtyp. |
## Se även

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
