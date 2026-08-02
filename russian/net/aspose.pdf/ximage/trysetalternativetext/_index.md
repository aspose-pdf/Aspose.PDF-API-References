---
title: "XImage.TrySetAlternativeText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод XImage. Устанавливает альтернативный текст для XImage на странице"
type: docs
weight: 180
url: /ru/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Устанавливает альтернативный текст для XImage на странице.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alternativeText | String | Альтернативный текст, который необходимо указать. |
| страница | Страница | Страница, на которой находится XImage. |

### Возвращаемое значение

True, если alternativeText для XImage установлен. False, если alternativeText для XImage не установлен.

## Примечания

Метод возвращает false в следующих случаях: - XImage не найден на указанной странице. - XImage появляется несколько раз на странице с разными структурными элементами, что делает неоднозначным, какому экземпляру следует присвоить альтернативный текст.

### См. также

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


