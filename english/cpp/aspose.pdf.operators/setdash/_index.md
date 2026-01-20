---
title: Aspose::Pdf::Operators::SetDash class
linktitle: SetDash
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetDash class. Class representing d operator (set line dash pattern) in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf.operators/setdash/
---
## SetDash class


Class representing d operator (set line dash pattern).

```cpp
class SetDash : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_Pattern](./get_pattern/)() const | Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal. |
| [get_Phase](./get_phase/)() const | Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward. |
| [set_Pattern](./set_pattern/)(System::ArrayPtr\<int32_t\>) | Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal. |
| [set_Phase](./set_phase/)(int32_t) | Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward. |
| [SetDash](./setdash/)(System::ArrayPtr\<int32_t\>, int32_t) | Creates set dash pattern operator. |
| [ToString](./tostring/)() const override | Gets operator string representation. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
