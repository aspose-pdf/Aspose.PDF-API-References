---
title: "XmpValue Class"
linktitle: "XmpValue"
articleTitle: "XmpValue"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XmpValue class. Represents XMP value"
type: docs
weight: 3310
url: "/net/aspose.pdf/xmpvalue/"
keywords: "XmpValue, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XmpValue class

Represents XMP value

```csharp
public class XmpValue
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpValue](./xmpvalue/#constructor)(DateTime) | Constructor for date time value. |
| [XmpValue](./xmpvalue/#constructor_1)(double) | Constructor for floating point Value. |
| [XmpValue](./xmpvalue/#constructor_2)(int) | Consructor for integer value. |
| [XmpValue](./xmpvalue/#constructor_3)(string) | Constructor for string value. |
| [XmpValue](./xmpvalue/#constructor_4)(XmpValue[]) | Constructor for array value. |

## Properties

| Name | Description |
| --- | --- |
| [IsArray](./isarray/) { get; } | Returns true is XmpValue is array. |
| [IsDateTime](./isdatetime/) { get; } | Returns true if value is DateTime. |
| [IsDouble](./isdouble/) { get; } | Returns true if value is floating point value. |
| [IsField](./isfield/) { get; } | Returns true if XmpValue is field. |
| [IsInteger](./isinteger/) { get; } | Returns true if value is integer. |
| [IsNamedValue](./isnamedvalue/) { get; } | Returns true if XmpValue is named value. |
| [IsNamedValues](./isnamedvalues/) { get; } | Returns true is XmpValue represents named values. |
| [IsRaw](./israw/) { get; } | Value is unsupported/unknown and raw XML code is provided. |
| [IsString](./isstring/) { get; } | Returns true if value is string. |
| [IsStructure](./isstructure/) { get; } | Returns true is XmpValue represents structure. |

## Methods

| Name | Description |
| --- | --- |
| [ToArray](./toarray/)() | Returns array. |
| [ToDateTime](./todatetime/)() | Converts to date time. |
| [ToDictionary](./todictionary/)() | Returns dictionary which contains named values. |
| [ToDouble](./todouble/)() | Converts to double. |
| [ToField](./tofield/)() | Returns XMP value as XMP field. |
| [ToInteger](./tointeger/)() | Converts to integer. |
| [ToNamedValue](./tonamedvalue/)() | Returns XMP value as named value. |
| [ToNamedValues](./tonamedvalues/)() | Returns XMP value as named value collection. |
| [ToRaw](./toraw/)() | Raw XML code for unknown/unsupported values. |
| override [ToString](./tostring/)() | Returns string representation of XmpValue. |
| [ToString](./tostring/)(IFormatProvider) | Returns string representation. |
| [ToStringValue](./tostringvalue/)() | Converts to string. |
| [ToStructure](./tostructure/)() | Returns XMP value as structure (set of fields). |
| [implicit operator](./op_implicit/#op_implicit) | Converts string to XmpValue. (5 operators) |
| [explicit operator](./op_explicit/#op_explicit) | Converts XmpValue to array. (5 operators) |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

