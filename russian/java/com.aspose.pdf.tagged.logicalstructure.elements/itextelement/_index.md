---
title: ITextElement
second_title: Aspose.PDF для справки по Java API
description: Интерфейс для представления элементов текстовой структуры.
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements/itextelement/
---
```
public interface ITextElement
```

Интерфейс для представления элементов текстовой структуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getStructureTextState()](#getStructureTextState--) | Получает объект StructureTextState для элемента текстовой структуры. |
| [setText(String text)](#setText-java.lang.String-) | Добавляет текстовое содержимое к текущему текстовому элементу. |
### getStructureTextState() {#getStructureTextState--}
```
public abstract StructureTextState getStructureTextState()
```


Получает объект StructureTextState для элемента текстовой структуры.

**Возвращает:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) Значение: объект StructureTextState для элемента текстовой структуры.
### setText(String text) {#setText-java.lang.String-}
```
public abstract void setText(String text)
```


Добавляет текстовое содержимое к текущему текстовому элементу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое |
