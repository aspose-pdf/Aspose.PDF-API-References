---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставить собственный метод, который будет получать запрашиваемые ресурсы откуда-то. Например, при использовании Aspose.Pdf в облаке прямой доступ к ссылочным файлам невозможен, и должен использоваться некоторый пользовательский код, помещенный в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода.
type: docs
weight: 6160
url: /ru/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## Делегат LoadOptions.ResourceLoadingStrategy

Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставить собственный метод, который будет получать запрашиваемые ресурсы откуда-то. Например, при использовании Aspose.Pdf в облаке прямой доступ к ссылочным файлам невозможен, и должен использоваться некоторый пользовательский код, помещенный в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceURI | String | URI ресурса. |

### Возвращаемое значение

Объект ResourceLoadingResult.

### См. также

* класс [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)