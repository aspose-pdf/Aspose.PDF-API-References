---
title: Aspose::Pdf::IOperatorSelector::Visit method
linktitle: Visit
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::IOperatorSelector::Visit method. Visit/select f operator in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/ioperatorselector/visit/
---
## IOperatorSelector::Visit(System::SharedPtr\<Operators::Fill\>) method


Visit/select f operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::Fill> f)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| f | System::SharedPtr\<Operators::Fill\> | Fill path operator (nonzero winding number rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>f</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Fill path operator (nonzero winding number rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Fill](../../../aspose.pdf.operators/fill/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ObsoleteFill\>) method


Visit/select F operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ObsoleteFill> F)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| F | System::SharedPtr\<Operators::ObsoleteFill\> | Fill path operator (nonzero winding number rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>F</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Fill path operator (nonzero winding number rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ObsoleteFill](../../../aspose.pdf.operators/obsoletefill/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EOFill\>) method


Visit/select operator f*.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EOFill> f_)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| f_ | System::SharedPtr\<Operators::EOFill\> | Fill path operator (even-odd rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>f_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Fill path operator (even-odd rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EOFill](../../../aspose.pdf.operators/eofill/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetGrayStroke\>) method


Visit/select G operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetGrayStroke> G)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| G | System::SharedPtr\<Operators::SetGrayStroke\> | Set gray level operator (for stroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>G</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set gray level operator (for stroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetGrayStroke](../../../aspose.pdf.operators/setgraystroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetGray\>) method


Visit/select g operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetGray> g)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| g | System::SharedPtr\<Operators::SetGray\> | Set gray level operator (for nonstroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>g</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set gray level operator (for nonstroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetGray](../../../aspose.pdf.operators/setgray/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::GS\>) method


Visit/select gs operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::GS> gs)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| gs | System::SharedPtr\<Operators::GS\> | Set graphics state operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>gs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set graphics state operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GS](../../../aspose.pdf.operators/gs/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ClosePath\>) method


Visit/select h operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ClosePath> h)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| h | System::SharedPtr\<Operators::ClosePath\> | Close subpath operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>h</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Close subpath operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ClosePath](../../../aspose.pdf.operators/closepath/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetFlat\>) method


Visit/select i operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetFlat> i)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | System::SharedPtr\<Operators::SetFlat\> | Set flatness tolerance operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>i</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set flatness tolerance operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetFlat](../../../aspose.pdf.operators/setflat/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ID\>) method


Visit/select ID operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ID> ID)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| ID | System::SharedPtr\<Operators::ID\> | Begin inline image data operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>ID</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin inline image data operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ID](../../../aspose.pdf.operators/id/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetColorRenderingIntent\>) method


Visit/select ri operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetColorRenderingIntent> ri)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| ri | System::SharedPtr\<Operators::SetColorRenderingIntent\> | Set color rendering intent operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>ri</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color rendering intent operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetColorRenderingIntent](../../../aspose.pdf.operators/setcolorrenderingintent/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetLineCap\>) method


Visit/select J operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetLineCap> J)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| J | System::SharedPtr\<Operators::SetLineCap\> | Set line cap style operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>J</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set line cap style operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetLineCap](../../../aspose.pdf.operators/setlinecap/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetMiterLimit\>) method


Visit/select M operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetMiterLimit> M)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| M | System::SharedPtr\<Operators::SetMiterLimit\> | Set miter limit operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>M</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set miter limit operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetMiterLimit](../../../aspose.pdf.operators/setmiterlimit/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MP\>) method


Visit/select MP operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MP> MP)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| MP | System::SharedPtr\<Operators::MP\> | Define marked-content point operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>MP</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Define marked-content point operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MP](../../../aspose.pdf.operators/mp/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EndPath\>) method


Visit/select n operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EndPath> n)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| n | System::SharedPtr\<Operators::EndPath\> | End path operator (without filling or stroking). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>n</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End path operator (without filling or stroking). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EndPath](../../../aspose.pdf.operators/endpath/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::GSave\>) method


Visit/select q operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::GSave> q)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| q | System::SharedPtr\<Operators::GSave\> | Save graphics state operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>q</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Save graphics state operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GSave](../../../aspose.pdf.operators/gsave/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::GRestore\>) method


Visit/select Q operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::GRestore> Q)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Q | System::SharedPtr\<Operators::GRestore\> | Restore graphics state operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Q</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Restore graphics state operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GRestore](../../../aspose.pdf.operators/grestore/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::Re\>) method


Visit/select re operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::Re> re)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| re | System::SharedPtr\<Operators::Re\> | Append rectangle to path operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>re</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Append rectangle to path operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Re](../../../aspose.pdf.operators/re/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetRGBColorStroke\>) method


Visit/select RG operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetRGBColorStroke> RG)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| RG | System::SharedPtr\<Operators::SetRGBColorStroke\> | Set RGB color operator (for stroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>RG</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set RGB color operator (for stroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetRGBColorStroke](../../../aspose.pdf.operators/setrgbcolorstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetRGBColor\>) method


Visit/select rg operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetRGBColor> rg)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| rg | System::SharedPtr\<Operators::SetRGBColor\> | Set RGB color operator (for nonstroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>rg</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set RGB color operator (for nonstroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetRGBColor](../../../aspose.pdf.operators/setrgbcolor/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetCMYKColorStroke\>) method


Visit/select K operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetCMYKColorStroke> K)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| K | System::SharedPtr\<Operators::SetCMYKColorStroke\> | Set CMYK color operator (for stroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>K</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set CMYK color operator (for stroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetCMYKColorStroke](../../../aspose.pdf.operators/setcmykcolorstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetCMYKColor\>) method


Visit/select k operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetCMYKColor> k)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| k | System::SharedPtr\<Operators::SetCMYKColor\> | Set CMYK color operator (for nonstroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>k</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set CMYK color operator (for nonstroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetCMYKColor](../../../aspose.pdf.operators/setcmykcolor/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::LineTo\>) method


Visit/select l operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::LineTo> l)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| l | System::SharedPtr\<Operators::LineTo\> | Append straight line segment to path operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>l</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Append straight line segment to path operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LineTo](../../../aspose.pdf.operators/lineto/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MoveTo\>) method


Visit/select m operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MoveTo> m)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| m | System::SharedPtr\<Operators::MoveTo\> | Begin new subpath operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>m</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin new subpath operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MoveTo](../../../aspose.pdf.operators/moveto/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetWordSpacing\>) method


Visit/select Tw operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetWordSpacing> Tw)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tw | System::SharedPtr\<Operators::SetWordSpacing\> | Set word spacing operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tw</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set word spacing operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetWordSpacing](../../../aspose.pdf.operators/setwordspacing/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ClosePathStroke\>) method


Visit/select s operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ClosePathStroke> s)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | System::SharedPtr\<Operators::ClosePathStroke\> | Close and stroke path operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>s</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Close and stroke path operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ClosePathStroke](../../../aspose.pdf.operators/closepathstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MoveTextPositionSetLeading\>) method


Visit/select TD operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MoveTextPositionSetLeading> TD)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| TD | System::SharedPtr\<Operators::MoveTextPositionSetLeading\> | Move text position and set leading operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>TD</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Move text position and set leading operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MoveTextPositionSetLeading](../../../aspose.pdf.operators/movetextpositionsetleading/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SelectFont\>) method


Visit/select Tf operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SelectFont> Tf)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tf | System::SharedPtr\<Operators::SelectFont\> | Set text font and size operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tf</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set text font and size operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SelectFont](../../../aspose.pdf.operators/selectfont/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ShowText\>) method


Visit/select Tj operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ShowText> Tj)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tj | System::SharedPtr\<Operators::ShowText\> | Show text operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tj</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Show text operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ShowText](../../../aspose.pdf.operators/showtext/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetGlyphsPositionShowText\>) method


Visit/select TJ operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetGlyphsPositionShowText> TJ)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| TJ | System::SharedPtr\<Operators::SetGlyphsPositionShowText\> | Show text operator (allowing individual glyph positioning). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>TJ</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Show text operator (allowing individual glyph positioning). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetGlyphsPositionShowText](../../../aspose.pdf.operators/setglyphspositionshowtext/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetTextLeading\>) method


Visit/select TL operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetTextLeading> TL)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| TL | System::SharedPtr\<Operators::SetTextLeading\> | Set text leading operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>TL</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set text leading operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetTextLeading](../../../aspose.pdf.operators/settextleading/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetTextMatrix\>) method


Visit/select Tm operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetTextMatrix> Tm)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tm | System::SharedPtr\<Operators::SetTextMatrix\> | Set text matrix and text line matrix operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set text matrix and text line matrix operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetTextMatrix](../../../aspose.pdf.operators/settextmatrix/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetTextRenderingMode\>) method


Visit/select Tr operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetTextRenderingMode> Tr)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tr | System::SharedPtr\<Operators::SetTextRenderingMode\> | Set text rendering mode operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tr</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set text rendering mode operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetTextRenderingMode](../../../aspose.pdf.operators/settextrenderingmode/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetTextRise\>) method


Visit/select Ts operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetTextRise> Ts)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Ts | System::SharedPtr\<Operators::SetTextRise\> | Set text rise operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Ts</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set text rise operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetTextRise](../../../aspose.pdf.operators/settextrise/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::Stroke\>) method


Visit/select S operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::Stroke> S)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| S | System::SharedPtr\<Operators::Stroke\> | Stroke path operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>S</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stroke path operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Stroke](../../../aspose.pdf.operators/stroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetColorStroke\>) method


Visit/select SC operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetColorStroke> SC)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| SC | System::SharedPtr\<Operators::SetColorStroke\> | Set color operator (for stroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>SC</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color operator (for stroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetColorStroke](../../../aspose.pdf.operators/setcolorstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetColor\>) method


Visit/select sc operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetColor> sc)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| sc | System::SharedPtr\<Operators::SetColor\> | Set color operator (for nonstroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>sc</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color operator (for nonstroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetColor](../../../aspose.pdf.operators/setcolor/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetAdvancedColorStroke\>) method


Visit/select SCN operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetAdvancedColorStroke> SCN)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| SCN | System::SharedPtr\<Operators::SetAdvancedColorStroke\> | Set color operator (for stroking operations, ICCBasedand special colour spaces). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>SCN</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color operator (for stroking operations, ICCBasedand special colour spaces). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetAdvancedColorStroke](../../../aspose.pdf.operators/setadvancedcolorstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetAdvancedColor\>) method


Visit/select scn operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetAdvancedColor> scn)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| scn | System::SharedPtr\<Operators::SetAdvancedColor\> | Set color operator (for nonstroking operations, ICCBased and special colour spaces). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>scn</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color operator (for nonstroking operations, ICCBased and special colour spaces). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetAdvancedColor](../../../aspose.pdf.operators/setadvancedcolor/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ShFill\>) method


Visit/select sh operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ShFill> sh)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| sh | System::SharedPtr\<Operators::ShFill\> | Paint area defined by shading pattern operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>sh</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Paint area defined by shading pattern operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ShFill](../../../aspose.pdf.operators/shfill/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MoveToNextLine\>) method


Visit/select T* operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MoveToNextLine> T_)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| T_ | System::SharedPtr\<Operators::MoveToNextLine\> | Move to start of next text line operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>T_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Move to start of next text line operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MoveToNextLine](../../../aspose.pdf.operators/movetonextline/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetCharacterSpacing\>) method


Visit/select Tc operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetCharacterSpacing> Tc)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tc | System::SharedPtr\<Operators::SetCharacterSpacing\> | Set character spacing operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tc</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set character spacing operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetCharacterSpacing](../../../aspose.pdf.operators/setcharacterspacing/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MoveTextPosition\>) method


Visit/select Td operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MoveTextPosition> Td)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Td | System::SharedPtr\<Operators::MoveTextPosition\> | Move text position operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Td</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Move text position operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MoveTextPosition](../../../aspose.pdf.operators/movetextposition/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::CurveTo2\>) method


Visit/select y operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::CurveTo2> y)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| y | System::SharedPtr\<Operators::CurveTo2\> | Append curved segment to path operator (final point replicated). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Append curved segment to path operator (final point replicated). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [CurveTo2](../../../aspose.pdf.operators/curveto2/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EOClip\>) method


Visit/select W* operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EOClip> W_)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| W_ | System::SharedPtr\<Operators::EOClip\> | Set clipping path operator (even-odd rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>W_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set clipping path operator (even-odd rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EOClip](../../../aspose.pdf.operators/eoclip/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetHorizontalTextScaling\>) method


Visit/select Tz operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetHorizontalTextScaling> Tz)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Tz | System::SharedPtr\<Operators::SetHorizontalTextScaling\> | Set horizontal text scaling operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Tz</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set horizontal text scaling operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetHorizontalTextScaling](../../../aspose.pdf.operators/sethorizontaltextscaling/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::CurveTo1\>) method


Visit/select v operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::CurveTo1> v)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| v | System::SharedPtr\<Operators::CurveTo1\> | Append curved segment to path operator (initial point replicated). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>v</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Append curved segment to path operator (initial point replicated). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [CurveTo1](../../../aspose.pdf.operators/curveto1/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::Clip\>) method


Visit/select W operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::Clip> W)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| W | System::SharedPtr\<Operators::Clip\> | Set clipping path operator (nonzero winding number rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>W</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set clipping path operator (nonzero winding number rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Clip](../../../aspose.pdf.operators/clip/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetLineWidth\>) method


Visit/select w operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetLineWidth> w)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| w | System::SharedPtr\<Operators::SetLineWidth\> | Set line width operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>w</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set line width operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetLineWidth](../../../aspose.pdf.operators/setlinewidth/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetLineJoin\>) method


Visit/select j operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetLineJoin> j)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| j | System::SharedPtr\<Operators::SetLineJoin\> | Set line join style operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>j</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set line join style operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetLineJoin](../../../aspose.pdf.operators/setlinejoin/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EX\>) method


Visit/select EX operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EX> EX)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| EX | System::SharedPtr\<Operators::EX\> | End compatibility section operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>EX</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End compatibility section operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EX](../../../aspose.pdf.operators/ex/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ET\>) method


Visit/select ET operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ET> ET)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| ET | System::SharedPtr\<Operators::ET\> | End text object operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>ET</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End text object operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ET](../../../aspose.pdf.operators/et/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EMC\>) method


Visit/select EMC operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EMC> EMC)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| EMC | System::SharedPtr\<Operators::EMC\> | End marked-content sequence operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>EMC</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End marked-content sequence operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EMC](../../../aspose.pdf.operators/emc/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EI\>) method


Visit/select EI operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EI> EI)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| EI | System::SharedPtr\<Operators::EI\> | End inline image object operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>EI</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End inline image object operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EI](../../../aspose.pdf.operators/ei/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::DP\>) method


Visit/select DP operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::DP> DP)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| DP | System::SharedPtr\<Operators::DP\> | Define marked-content point operator (with property list). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>DP</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Define marked-content point operator (with property list). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DP](../../../aspose.pdf.operators/dp/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::Do\>) method


Visit/select Do operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::Do> Do)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| Do | System::SharedPtr\<Operators::Do\> | Invoke named XObject operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>Do</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Invoke named XObject operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Do](../../../aspose.pdf.operators/do/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetDash\>) method


Visit/select d operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetDash> d)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| d | System::SharedPtr\<Operators::SetDash\> | Set line dash pattern operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>d</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set line dash pattern operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetDash](../../../aspose.pdf.operators/setdash/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetCharWidth\>) method


Visit/select d0 operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetCharWidth> d0)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| d0 | System::SharedPtr\<Operators::SetCharWidth\> | Set glyph width in Type 3 font operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>d0</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set glyph width in Type 3 font operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetCharWidth](../../../aspose.pdf.operators/setcharwidth/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetCharWidthBoundingBox\>) method


Visit/select d1 operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetCharWidthBoundingBox> d1)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| d1 | System::SharedPtr\<Operators::SetCharWidthBoundingBox\> | Set glyph width and bounding box in Type 3 font operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>d1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set glyph width and bounding box in Type 3 font operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetCharWidthBoundingBox](../../../aspose.pdf.operators/setcharwidthboundingbox/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetColorSpaceStroke\>) method


Visit/select CS operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetColorSpaceStroke> CS)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| CS | System::SharedPtr\<Operators::SetColorSpaceStroke\> | Set color space operator (for stroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>CS</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color space operator (for stroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetColorSpaceStroke](../../../aspose.pdf.operators/setcolorspacestroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetColorSpace\>) method


Visit/select cs operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetColorSpace> cs)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| cs | System::SharedPtr\<Operators::SetColorSpace\> | Set color space operator (for nonstroking operations). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>cs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set color space operator (for nonstroking operations). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetColorSpace](../../../aspose.pdf.operators/setcolorspace/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ConcatenateMatrix\>) method


Visit/select cm operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ConcatenateMatrix> cm)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| cm | System::SharedPtr\<Operators::ConcatenateMatrix\> | Concatenate matrix to current transformation matrix operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>cm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Concatenate matrix to current transformation matrix operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ConcatenateMatrix](../../../aspose.pdf.operators/concatenatematrix/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::CurveTo\>) method


Visit/select c operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::CurveTo> c)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | System::SharedPtr\<Operators::CurveTo\> | Append curved segment to path operator (three control points). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>c</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Append curved segment to path operator (three control points). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [CurveTo](../../../aspose.pdf.operators/curveto/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::BX\>) method


Visit/select BX operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::BX> BX)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| BX | System::SharedPtr\<Operators::BX\> | Begin compatibility section operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>BX</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin compatibility section operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [BX](../../../aspose.pdf.operators/bx/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::BT\>) method


Visit/select BT operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::BT> BT)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| BT | System::SharedPtr\<Operators::BT\> | Begin text object operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>BT</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin text object operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [BT](../../../aspose.pdf.operators/bt/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::BMC\>) method


Visit/select BMC operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::BMC> BMC)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| BMC | System::SharedPtr\<Operators::BMC\> | Begin marked-content sequence operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>BMC</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin marked-content sequence operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [BMC](../../../aspose.pdf.operators/bmc/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::BI\>) method


Visit/select BI operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::BI> BI)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| BI | System::SharedPtr\<Operators::BI\> | Begin inline image object operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>BI</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin inline image object operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [BI](../../../aspose.pdf.operators/bi/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::BDC\>) method


Visit/select BDC operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::BDC> BDC)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| BDC | System::SharedPtr\<Operators::BDC\> | Begin marked-content sequence operator (with property list). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>BDC</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Begin marked-content sequence operator (with property list). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [BDC](../../../aspose.pdf.operators/bdc/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::FillStroke\>) method


Visit/select B operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::FillStroke> B)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| B | System::SharedPtr\<Operators::FillStroke\> | Fill and stroke path operator (nonzero winding number rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>B</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Fill and stroke path operator (nonzero winding number rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FillStroke](../../../aspose.pdf.operators/fillstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ClosePathFillStroke\>) method


Visit/select b operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ClosePathFillStroke> b)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| b | System::SharedPtr\<Operators::ClosePathFillStroke\> | Close, fill, and stroke path operator (nonzero winding number rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>b</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Close, fill, and stroke path operator (nonzero winding number rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ClosePathFillStroke](../../../aspose.pdf.operators/closepathfillstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::EOFillStroke\>) method


Visit/select B* operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::EOFillStroke> B_)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| B_ | System::SharedPtr\<Operators::EOFillStroke\> | Fill and stroke path operator (even-odd rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>B_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Fill and stroke path operator (even-odd rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [EOFillStroke](../../../aspose.pdf.operators/eofillstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::ClosePathEOFillStroke\>) method


Visit/select b* operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::ClosePathEOFillStroke> b_)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| b_ | System::SharedPtr\<Operators::ClosePathEOFillStroke\> | Close, fill, and stroke path operator (even-odd rule). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>b_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Close, fill, and stroke path operator (even-odd rule). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ClosePathEOFillStroke](../../../aspose.pdf.operators/closepatheofillstroke/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::MoveToNextLineShowText\>) method


Visit/select ' operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::MoveToNextLineShowText> _)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| _ | System::SharedPtr\<Operators::MoveToNextLineShowText\> | Move to next line and show text operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>_</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Move to next line and show text operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [MoveToNextLineShowText](../../../aspose.pdf.operators/movetonextlineshowtext/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>) method


Visit/select '' operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::SetSpacingMoveToNextLineShowText> __)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| __ | System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\> | Set word and character spacing, move to next line, and show text operator. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>__</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set word and character spacing, move to next line, and show text operator. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SetSpacingMoveToNextLineShowText](../../../aspose.pdf.operators/setspacingmovetonextlineshowtext/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## IOperatorSelector::Visit(System::SharedPtr\<Operators::TextOperator\>) method


Visit/select any text operator operator.

```cpp
virtual void Aspose::Pdf::IOperatorSelector::Visit(System::SharedPtr<Operators::TextOperator> textOperator)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| textOperator | System::SharedPtr\<Operators::TextOperator\> | General text operator which is used to select the set of corresponding pdf operators. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>textOperator</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>General text operator which is used to select the set of corresponding pdf operators. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextOperator](../../../aspose.pdf.operators/textoperator/)
* Class [IOperatorSelector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
