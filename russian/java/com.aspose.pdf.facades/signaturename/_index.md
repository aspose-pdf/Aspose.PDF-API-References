---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для имени подписи. Представляет более точное имя подписи. Используется вместо строковых имен. Позволяет представлять подписи с одинаковыми строковыми именами."
type: docs
weight: 690
url: /ru/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Представляет класс для имени подписи. Представляет более точное имя подписи. Используется вместо строковых имен. Позволяет представлять подписи с одинаковыми строковыми именами.

## Поля

| Поле | Описание |
| --- | --- |
| [FullName](#FullName) | Получает полное имя подписи, предоставляя уникальный и точный идентификатор для поля подписи. |
| [Name](#Name) | Получает имя подписи. |

## Методы

| Метод | Описание |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Определяет, равны ли данный экземпляр и указанный объект. |
| [getSignatureDictionary](#getSignatureDictionary--) | Получает словарь подписи. |
| [hashCode](#hashCode--) | Возвращает хеш-код для этого экземпляра на основе свойства FullName. |
| [hasSignature](#hasSignature--) | Указывает, присутствует ли подпись. |
| [toString](#toString--) | Возвращает строковое представление экземпляра {@link SignatureName}, в основном используя его имя. |

### FullName {#FullName}
```
public final String FullName
```

Получает полное имя подписи, предоставляя уникальный и точный идентификатор для поля подписи.

### Name {#Name}
```
public final String Name
```

Получает имя подписи.

### equals {#equals-java.lang.Object-}
Определяет, равны ли данный экземпляр и указанный объект.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Получает словарь подписи.

**Returns:**
Словарь подписи или null, если он не найден.

### hashCode {#hashCode--}
```
public int hashCode()
```

Возвращает хеш-код для этого экземпляра на основе свойства FullName.

**Returns:**
Целое число, представляющее хеш-код свойства FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Указывает, присутствует ли подпись.

**Returns:**
логическое значение

### toString {#toString--}
```
public String toString()
```

Возвращает строковое представление экземпляра {@link SignatureName}, в основном используя его имя.

**Returns:**
Строка, представляющая имя подписи.
