---
title: "HtmlLoadOptions.CustomLoaderOfExternalResources"
second_title: "Справочник API Aspose.PDF для .NET"
description: "HtmlLoadOptions поле. Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставить пользовательский метод, который будет получать запрошенные ресурсы откуда‑то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен; в таком случае некоторый пользовательский код, помещённый в специальный метод, должен использоваться, и делегат, ссылающийся на этот метод, должен быть назначен этому атрибуту"
type: docs
weight: 100
url: /ru/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например, изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае следует использовать пользовательский код, помещённый в специальный метод, а делегат, ссылающийся на этот метод, должен быть назначен этому атрибуту.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### См. также

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


