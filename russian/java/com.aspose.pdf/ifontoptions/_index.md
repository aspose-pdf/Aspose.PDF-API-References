---
Название: IFontOptions
second_title: Aspose.PDF для справки по Java API
описание: Полезные свойства для настройки поведения шрифта
тип: документы
вес: 434
URL-адрес: /java/com.aspose.pdf/ifontoptions/
---```
общедоступный интерфейс IFontOptions
```

Useful properties to tune Font behavior
## Methods

| Method | Description |
| --- | --- |
| [getNotifyAboutFontEmbeddingError()](#getNotifyAboutFontEmbeddingError--) | Sometimes it's not possible to embed desired font into document. |
| [setNotifyAboutFontEmbeddingError(boolean value)](#setNotifyAboutFontEmbeddingError-boolean-) | Sometimes it's not possible to embed desired font into document. |
### getNotifyAboutFontEmbeddingError() {#getNotifyAboutFontEmbeddingError--}
```
открытый абстрактный логический метод getNotifyAboutFontEmbeddingError()
```


Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type FontEmbeddingException will be thrown. By default false.

**Returns:**
boolean - boolean value
### setNotifyAboutFontEmbeddingError(boolean value) {#setNotifyAboutFontEmbeddingError-boolean-}
```
public abstract void setNotifyAboutFontEmbeddingError (логическое значение)
```


Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type FontEmbeddingException will be thrown. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |
