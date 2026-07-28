---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для проверки цифровых подписей документа на компрометацию."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Представляет класс для проверки цифровых подписей документа на компрометацию.

## Поля

| Поле | Описание |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Получает коллекцию цифровых подписей, которые были определены как скомпрометированные. Это свойство содержит список всех скомпрометированных подписей, обнаруженных в документе. |

## Методы

| Метод | Описание |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Получает состояние охвата цифровыми подписями в документе. Если оно равно {@code SignaturesCoverage#Undefined}, то одна из подписей скомпрометирована. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Указывает, есть ли в документе скомпрометированные цифровые подписи. Возвращает true, если хотя бы одна подпись скомпрометирована; в противном случае — false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Получает коллекцию цифровых подписей, которые были определены как скомпрометированные. Это свойство содержит список всех скомпрометированных подписей, обнаруженных в документе.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Получает состояние охвата цифровыми подписями в документе. Если оно равно {@code SignaturesCoverage#Undefined}, то одна из подписей скомпрометирована.

**Returns:**
Элемент SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Указывает, есть ли в документе скомпрометированные цифровые подписи. Возвращает true, если хотя бы одна подпись скомпрометирована; в противном случае — false.

**Returns:**
логическое значение
