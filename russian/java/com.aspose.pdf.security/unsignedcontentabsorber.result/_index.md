---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Справочник API Aspose.PDF для Java"
description: "Инкапсулирует результат операции, пытающейся извлечь неподписанное содержимое из PDF‑документа. Этот класс предоставляет информацию об успешности операции, детали."
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Инкапсулирует результат операции по попытке извлечения неподписанного содержимого из PDF‑документа. Этот класс предоставляет информацию об успешности операции, детали неподписанного содержимого, сообщение, описывающее результат, и статус охвата подписей документа.

## Методы

| Метод | Описание |
| --- | --- |
| [getCoverage](#getCoverage--) | Возвращает значение, указывающее степень, в которой документ покрыт действительными цифровыми подписями. |
| [getMessage](#getMessage--) | Возвращает сообщение, описывающее результат операции. |
| [getSuccess](#getSuccess--) | Возвращает значение, указывающее, была ли успешна операция по получению неподписанного содержимого из документа. |
| [getUnsignedContent](#getUnsignedContent--) | Возвращает неподписанное содержимое. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Возвращает значение, указывающее степень, в которой документ покрыт действительными цифровыми подписями.

**Returns:**
значение, указывающее степень, в которой документ покрыт действительными цифровыми подписями.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Возвращает сообщение, описывающее результат операции.

**Returns:**
сообщение, описывающее результат операции.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Возвращает значение, указывающее, была ли успешна операция по получению неподписанного содержимого из документа.

**Returns:**
значение, указывающее, была ли успешна операция по получению неподписанного содержимого из документа.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Возвращает неподписанное содержимое.

**Returns:**
неподписанное содержимое.
