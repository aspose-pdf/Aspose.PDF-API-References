---
title: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF для справки по Java API
description: Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы.
type: docs
weight: 13
url: /ru/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то достанет запрошенные ресурсы. Например, при использовании Aspose.PDf в облаке прямой доступ к файлам, на которые ссылаются, невозможен, и необходимо использовать какой-то пользовательский код, помещенный в специальный метод. Этот делегат определяет подпись такого пользовательского метода.
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(String resourceURI)](#invoke-java.lang.String-) |  |
### invoke(String resourceURI) {#invoke-java.lang.String-}
```
public abstract LoadOptions.ResourceLoadingResult invoke(String resourceURI)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceURI | java.lang.String |  |

**Возвращает:**
[ResourceLoadingResult](../../com.aspose.pdf/resourceloadingresult)