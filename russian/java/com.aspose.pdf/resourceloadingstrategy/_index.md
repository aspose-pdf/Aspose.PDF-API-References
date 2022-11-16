---
Название: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF для справки по Java API
описание: иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов, таких как изображения или CSS, и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы.
тип: документы
вес: 13
URL-адрес: /java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---```
общедоступный статический интерфейс LoadOptions.ResourceLoadingStrategy
```

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.PDf in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method.
## Methods

| Method | Description |
| --- | --- |
| [invoke(String resourceURI)](#invoke-java.lang.String-) |  |
### invoke(String resourceURI) {#invoke-java.lang.String-}
```
общедоступный абстрактный LoadOptions.ResourceLoadingResult invoke (String resourceURI)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceURI | java.lang.String |  |

**Returns:**
[ResourceLoadingResult](../../com.aspose.pdf/resourceloadingresult)