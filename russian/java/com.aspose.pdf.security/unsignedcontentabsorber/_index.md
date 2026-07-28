---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для извлечения неподписанного содержимого из PDF‑файла, управляемого цифровыми подписями."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Представляет класс для извлечения неподписанного содержимого из PDF‑файла, управляемого цифровыми подписями.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Представляет класс, используемый для обработки неподписанного содержимого. |

## Методы

| Метод | Описание |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Попытка получить неподписанное содержимое из связанного документа. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Представляет класс, используемый для обработки неподписанного содержимого.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Попытка получить неподписанное содержимое из связанного документа.

**Returns:**
Объект {@link UnsignedContentAbsorber.Result}, содержащий детали о неподписанном содержимом, охвате цифровых подписей, статусе успешности операции и информационном сообщении.
