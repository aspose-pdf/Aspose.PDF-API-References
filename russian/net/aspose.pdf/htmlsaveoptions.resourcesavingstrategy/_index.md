---
title: HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF для справочника API .NET
description: Этому свойству можно назначить делегата созданного из пользовательского метода который реализует обработку внешнего ресурса шрифта или изображения  который был извлечен из PDF и должен быть сохранен как внешний ресурс во время преобразования PDF в HTML. В таком случае обработка  например сохранение в потоке или на диске может быть выполнено в этом пользовательском коде и этот пользовательский код должен возвращать путь или любую другую строку без кавычек  которая впоследствии будет включена в сгенерированный HTML вместо исходного предполагаемого пути к этому ресурсу изображения. В этом случае все необходимые действия по сохранению изображения должны быть выполнены в коде предоставленного метода т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка того или иного файла по каким-то причинам должна производиться самим кодом конвертера а не в пользовательском коде установите в пользовательском коде флаг CustomProcessingCancelled переменной resourceSavingInfo параметра Сигнализирует конвертеру что выполнены все необходимые действия для обработка этого ресурса должна выполняться в самом конвертере как если бы не было никакого внешнего пользовательского кода .
type: docs
weight: 3600
url: /ru/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

Этому свойству можно назначить делегата, созданного из пользовательского метода, который реализует обработку внешнего ресурса (шрифта или изображения) , который был извлечен из PDF и должен быть сохранен как внешний ресурс во время преобразования PDF в HTML. В таком случае обработка ( например, сохранение в потоке или на диске) может быть выполнено в этом пользовательском коде, и этот пользовательский код должен возвращать путь (или любую другую строку без кавычек) , которая впоследствии будет включена в сгенерированный HTML вместо исходного предполагаемого пути к этому ресурсу изображения. В этом случае все необходимые действия по сохранению изображения должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка того или иного файла по каким-то причинам должна производиться самим кодом конвертера, а не в пользовательском коде, установите в пользовательском коде флаг CustomProcessingCancelled переменной resourceSavingInfo параметра Сигнализирует конвертеру, что выполнены все необходимые действия для обработка этого ресурса должна выполняться в самом конвертере, как если бы не было никакого внешнего пользовательского кода .

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | представляет собой набор данных для экономии ресурса |

### Возвращаемое значение

должен возвращать URL-адрес сохраненного ресурса, который будет использоваться при создании HTML

### Смотрите также

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
