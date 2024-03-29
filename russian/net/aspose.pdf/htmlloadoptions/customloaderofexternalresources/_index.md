---
title: CustomLoaderOfExternalResources
second_title: Aspose.PDF для справочника API .NET
description: Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов таких как изображения или CSS и предоставлять собственный метод который откуда-то будет получать запрошенные ресурсы. Например при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен в таком случае необходимо использовать некий пользовательский код помещенный в специальный метод и этому атрибуту должен быть присвоен делегат ссылающийся на этот метод.
type: docs
weight: 90
url: /ru/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае необходимо использовать некий пользовательский код, помещенный в специальный метод, и этому атрибуту должен быть присвоен делегат, ссылающийся на этот метод.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Смотрите также

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy)
* class [HtmlLoadOptions](../../htmlloadoptions)
* пространство имен [Aspose.Pdf](../../htmlloadoptions)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
