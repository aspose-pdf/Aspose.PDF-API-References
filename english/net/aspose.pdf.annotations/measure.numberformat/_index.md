---
title: "Measure.NumberFormat Class"
linktitle: "Measure.NumberFormat"
articleTitle: "Measure.NumberFormat"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.Measure.NumberFormat class. Number format for measure."
type: docs
weight: 660
url: "/net/aspose.pdf.annotations/measure.numberformat/"
keywords: "Measure.NumberFormat, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Measure.NumberFormat class

Number format for measure.

```csharp
public class NumberFormat
```

## Constructors

| Name | Description |
| --- | --- |
| [NumberFormat](./numberformat/)(Measure) | Constructor for NumberFormat class. |

## Properties

| Name | Description |
| --- | --- |
| [AfterText](./aftertext/) { get; set; } | Text that shall be concatenated after the label |
| [BeforeText](./beforetext/) { get; set; } | Text that shall be concatenated to the left of the label. |
| [ConvresionFactor](./convresionfactor/) { get; set; } | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [Denominator](./denominator/) { get; set; } | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16. |
| [ForceDenominator](./forcedenominator/) { get; set; } | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced. |
| [FractionDisplayment](./fractiondisplayment/) { get; set; } | In what manner fractional values are displayed. |
| [FractionSeparator](./fractionseparator/) { get; set; } | Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character. |
| [Precision](./precision/) { get; set; } | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100. |
| [ThousandsSeparator](./thousandsseparator/) { get; set; } | Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma. |
| [UnitLabel](./unitlabel/) { get; set; } | A text string specifying a label for displaying the units. |

## Other Members

| Name | Description |
| --- | --- |
| enum [FractionStyle](../../aspose.pdf.annotations/measure.numberformat.fractionstyle) | Value which indicates in which manner fraction values are displayed. |

### See Also

* class [Measure](../measure/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

