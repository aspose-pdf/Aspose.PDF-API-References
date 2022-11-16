---
title: IFontOptions
second_title: Aspose.PDF для справки по Java API
description: Полезные свойства для настройки поведения шрифта
type: docs
weight: 434
url: /ru/java/com.aspose.pdf/ifontoptions/
---
```
public interface IFontOptions
```

Полезные свойства для настройки поведения шрифта
## Методы

| Метод | Описание |
| --- | --- |
| [getNotifyAboutFontEmbeddingError()](#getNotifyAboutFontEmbeddingError--) | Иногда невозможно встроить нужный шрифт в документ. |
| [setNotifyAboutFontEmbeddingError(boolean value)](#setNotifyAboutFontEmbeddingError-boolean-) | Иногда невозможно встроить нужный шрифт в документ. |
### getNotifyAboutFontEmbeddingError() {#getNotifyAboutFontEmbeddingError--}
```
public abstract boolean getNotifyAboutFontEmbeddingError()
```


Иногда невозможно встроить нужный шрифт в документ. Причин может быть много, например ограничения лицензии или отсутствие нужного шрифта на целевом компьютере. Когда наступает такая ситуация, ее не просто обнаружить, потому что нужный шрифт встраивается через набор свойств флага Font.IsEmbedded = true; Конечно, это свойство можно прочитать сразу после его установки, но это не очень удобный подход. Флаг NotifyAboutFontEmbeddingError включает механизм исключений для случаев, когда попытка встроить шрифт не удалась. Если этот флаг установлен, будет сгенерировано исключение типа FontEmbeddingException. По умолчанию ложь.

**Возвращает:**
boolean - логическое значение
### setNotifyAboutFontEmbeddingError(boolean value) {#setNotifyAboutFontEmbeddingError-boolean-}
```
public abstract void setNotifyAboutFontEmbeddingError(boolean value)
```


Иногда невозможно встроить нужный шрифт в документ. Причин может быть много, например ограничения лицензии или отсутствие нужного шрифта на целевом компьютере. Когда наступает такая ситуация, ее не просто обнаружить, потому что нужный шрифт встраивается через набор свойств флага Font.IsEmbedded = true; Конечно, это свойство можно прочитать сразу после его установки, но это не очень удобный подход. Флаг NotifyAboutFontEmbeddingError включает механизм исключений для случаев, когда попытка встроить шрифт не удалась. Если этот флаг установлен, будет сгенерировано исключение типа FontEmbeddingException. По умолчанию ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |
