---
title: MemoryExtender.CallBackPageImage
second_title: Aspose.PDF для справки по Java API
description: Процедура обратного вызова для управления кэшем.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/memoryextender.callbackpageimage/
---
```
public static interface MemoryExtender.CallBackPageImage
```

Процедура обратного вызова для управления кэшем.
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(BufferedImage img)](#invoke-java.awt.image.BufferedImage-) | Этот метод должен дать ответ, добавлять новое изображение в кеш или нет. |
### invoke(BufferedImage img) {#invoke-java.awt.image.BufferedImage-}
```
public abstract boolean invoke(BufferedImage img)
```


Этот метод должен дать ответ, добавлять новое изображение в кеш или нет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| img | java.awt.image.BufferedImage | Объект изображения |

**Возвращает:**
boolean - логическое значение