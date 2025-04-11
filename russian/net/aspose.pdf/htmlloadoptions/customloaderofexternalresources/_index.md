---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: Поле HtmlLoadOptions. Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда-то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае следует использовать некоторый пользовательский код, помещенный в специальный метод, и делегат, который ссылается на этот метод, должен быть назначен этому атрибуту.
type: docs
weight: 100
url: /ru/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## Поле HtmlLoadOptions.CustomLoaderOfExternalResources

Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда-то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае следует использовать некоторый пользовательский код, помещенный в специальный метод, и делегат, который ссылается на этот метод, должен быть назначен этому атрибуту.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### См. также

* делегат [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* класс [HtmlLoadOptions](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)