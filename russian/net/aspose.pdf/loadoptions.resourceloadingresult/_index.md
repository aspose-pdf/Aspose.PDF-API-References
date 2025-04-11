---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LoadOptionsResourceLoadingResult. Результат пользовательской загрузки ресурса
type: docs
weight: 6150
url: /ru/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Результат пользовательской загрузки ресурса

```csharp
public class ResourceLoadingResult
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Создает экземпляр результата загрузки |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Двоичные данные, загруженные с помощью пользовательского загрузчика - они должны быть установлены после загрузки |

## Fields

| Name | Description |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Иногда кодировка ресурса известна после или во время загрузки. В таком случае пользовательский код может предоставить конвертеру эту информацию через этот параметр. Вы можете оставить null в этом параметре, если кодировка неизвестна или не имеет значения. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Иногда невозможно загрузить запрашиваемый ресурс по какой-то причине. Недоступность ресурса часто не приводит к сбою конверсии, и результирующий документ может быть создан в любом случае (но, возможно, в немного худшем качестве, без изображений и т. д.). Если во время загрузки произошло исключение, просто поймайте его и поместите в этот параметр - иногда эта информация полезна для конвертера при рендеринге результата. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Иногда по каким-то причинам загрузка не должна происходить в пользовательском коде. В таком случае установите этот флаг в True. В таком случае конвертер попытается использовать внутренний загрузчик ресурсов по умолчанию, чтобы получить этот результат (как он ведет себя в ситуации, когда пользовательская стратегия не предоставлена). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Иногда знание о MIME-типе загруженного ресурса полезно для конвертера. Вы можете предоставить MIME-тип (если он известен после загрузки) в этом параметре. Пожалуйста, оставьте параметр равным null, когда MIME-тип неизвестен или его не обязательно предоставлять. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)