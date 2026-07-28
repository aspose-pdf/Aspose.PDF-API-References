---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Для этого свойства вы можете назначить делегат, созданный из пользовательского метода, который реализует обработку внешнего ресурса (Font или Image), извлечённого из PDF и подлежащего сохранению."
type: docs
weight: 2150
url: /ru/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Для этого свойства вы можете назначить делегат, созданный из пользовательского метода, который реализует обработку внешнего ресурса (Font или Image), извлечённого из PDF и подлежащего сохранению как внешнего ресурса при конвертации PDF в HTML. В таком случае обработка (например, сохранение в поток или на диск) может быть выполнена в этом пользовательском коде, и этот пользовательский код должен вернуть путь (или любую другую строку без кавычек), который затем будет включён в сгенерированный HTML вместо исходного предполагаемого пути к этому изображению. При этом все необходимые действия по сохранению изображения должны быть выполнены в коде предоставленного метода, поскольку сохранение результата в коде конвертера использоваться не будет. Если обработка этого или того файла по какой‑то причине должна быть выполнена кодом конвертера, а не пользовательским кодом, пожалуйста, установите в пользовательском коде флаг 'CustomProcessingCancelled' переменной параметра 'resourceSavingInfo'. Это сигнализирует конвертеру, что все необходимые шаги по обработке этого ресурса должны быть выполнены самим конвертером, как если бы внешнего пользовательского кода не было.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Вызванный метод |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Вызванный метод
