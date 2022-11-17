---
title: Document.IDocumentFontUtilities
second_title: Aspose.PDF для справки по Java API
description: Содержит функциональность для настройки шрифтов
type: docs
weight: 12
url: /ru/java/com.aspose.pdf/document.idocumentfontutilities/
---
```
public static interface Document.IDocumentFontUtilities
```

Содержит функциональность для настройки шрифтов
## Методы

| Метод | Описание |
| --- | --- |
| [getAllFonts()](#getAllFonts--) | Возвращает все шрифты из документа |
| [subsetFonts(byte subsetStrategy)](#subsetFonts-byte-) | Подмножество всех шрифтов в документе |
### getAllFonts() {#getAllFonts--}
```
public abstract Font[] getAllFonts()
```


Возвращает все шрифты из документа

**Возвращает:**
com.aspose.pdf.Шрифт[- шрифты
### subsetFonts(byte subsetStrategy) {#subsetFonts-byte-}
```
public abstract void subsetFonts(byte subsetStrategy)
```


Подмножество всех шрифтов в документе

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| subsetStrategy | byte | Элемент FontSubsetStrategy |
