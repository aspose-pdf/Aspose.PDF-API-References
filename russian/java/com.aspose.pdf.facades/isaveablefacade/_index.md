---
title: ISaveableFacade
second_title: Aspose.PDF для справки по Java API
description: Интерфейс фасада, определяющий методы, общие для всех сохраняемых фасадов.
type: docs
weight: 72
url: /ru/java/com.aspose.pdf.facades/isaveablefacade/
---
**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public interface ISaveableFacade extends IFacade
```

Интерфейс фасада, определяющий методы, общие для всех сохраняемых фасадов.
## Методы

| Метод | Описание |
| --- | --- |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет полученный PDF-документ в потоковом режиме. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет полученный PDF-документ в файл. |
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream destStream)
```


Сохраняет полученный PDF-документ в потоковом режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Объект OutputStream |

### save(String destFile) {#save-java.lang.String-}
```
public abstract void save(String destFile)
```


Сохраняет полученный PDF-документ в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Строковый объект |
