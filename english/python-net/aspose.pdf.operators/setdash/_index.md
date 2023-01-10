---
title: SetDash
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing d operator (set line dash pattern).
type: docs
weight: 580
url: /python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Class representing d operator (set line dash pattern).

The SetDash type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|SetDash(pattern, phase)|Initializes a new instance of the SetDash class|
## Properties
| Name | Description |
| :- | :- |
|index|Operator index in page operators list.|
|pattern|Dash pattern. Array�s elements shall be numbers that specify the lengths of alternating dashes and gaps.<br/>            In case of one element array dash and gap lengths are equal.|
|phase|Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. <br/>            When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, <br/>            and the dash array shall be used cyclically from that point onward.|
## Methods
| Name | Description |
| :- | :- |
|accept(visitor)|Accepts visitor object to process operator.|
|is_text_show_operator(op)|Determines if the operator is operator which responsible for text output (Tj, TJ, etc)|

### See Also

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

