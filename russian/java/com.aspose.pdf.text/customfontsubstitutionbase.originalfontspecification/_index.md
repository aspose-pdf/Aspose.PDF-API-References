---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Справочник API Aspose.PDF для Java"
description: "<p> Представляет спецификацию оригинального шрифта. </p> <hr> <p> Предоставляет информацию, связанную с оригинальным шрифтом, такую как , flag. Также предоставляет флаг, который помогает проверить, будет ли substitution. </p>"
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Представляет спецификацию оригинального шрифта. </p> <hr> <p> Предоставляет информацию, связанную с оригинальным шрифтом, такую как , flag. Также предоставляет флаг, который помогает проверить, произойдёт ли substitution всё равно с шрифтом, и пользователь может переопределить логику замены по умолчанию. </p>

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Инициализирует новый объект OriginalFontSpecification. |

## Методы

| Метод | Описание |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Получает имя оригинального шрифта. |
| [isEmbedded](#isEmbedded--) | Получает значение, указывающее, встроен ли шрифт. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Получает значение, указывающее, что замена неизбежна. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Инициализирует новый объект OriginalFontSpecification.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Получает имя оригинального шрифта.

**Returns:**
строковое значение

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Получает значение, указывающее, встроен ли шрифт.

**Returns:**
логическое значение

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Получает значение, указывающее, что замена неизбежна. </p>

**Returns:**
boolean value <hr> <p> Возвращает true, если замена была запрошена из‑за отсутствия оригинального шрифта или если оригинальный шрифт нельзя использовать в контексте некоторой задачи. Если пользователь игнорирует флаг и не заменяет шрифт — выполняется процедура замены шрифта по умолчанию. Однако это предоставляет возможность пользователю изменить стандартную процедуру замены и установить более подходящий шрифт в системе. Возвращает false, если оригинальный шрифт присутствует, валиден, но пользователю разрешено его заменить. </p>
