---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то."
type: docs
weight: 2830
url: /ru/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.PDf в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода.

## Методы

| Метод | Описание |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
