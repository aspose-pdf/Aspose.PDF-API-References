---
title: "Metered Class"
linktitle: "Metered"
articleTitle: "Metered"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Metered class. Provides methods to set metered key."
type: docs
weight: 1870
url: "/net/aspose.pdf/metered/"
keywords: "Metered, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Metered class

Provides methods to set metered key.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](./metered/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Gets consumption credit. |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Gets consumption file size. |
| [GetProductName](./getproductname/)() | Get the Product Name. |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Check whether metered is licensed. |
| [SetMeteredKey](./setmeteredkey/)(string, string) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

