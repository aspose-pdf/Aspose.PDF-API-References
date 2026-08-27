---
title: "Делегат LoadOptions.ResourceLoadingStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.Pdf в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода."
type: docs
weight: 6300
url: /ru/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например, изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.Pdf в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceURI | String | URI ресурса. |

### Возвращаемое значение

Объект ResourceLoadingResult.

### См. также

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


