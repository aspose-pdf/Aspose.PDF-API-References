---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет перечисление уровня охвата, предоставляемого цифровыми подписями в документе."
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Представляет перечисление уровня охвата, предоставляемого цифровыми подписями в документе.

## Поля

| Поле | Описание |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Указывает, что документ полностью охвачен цифровыми подписями. Это значение означает, что все необходимые части документа подписаны и ни одна подпись не скомпрометирована. |
| [PartiallySigned](#PartiallySigned) | Указывает, что документ частично подписан, то есть некоторые, но не все, его части охвачены цифровыми подписями. Это значение используется, когда определённые части документа остаются неподписанными или исключены из охвата подписью. |
| [Undefined](#Undefined) | Указывает, что состояние охвата цифровыми подписями в документе неопределено. Это значение обычно используется, когда одна или несколько подписей в документе скомпрометированы или не могут быть проверены, что не позволяет дать окончательную оценку охвата подписью. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Указывает, что документ полностью охвачен цифровыми подписями. Это значение означает, что все необходимые части документа подписаны и ни одна подпись не скомпрометирована.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Указывает, что документ частично подписан, то есть некоторые, но не все, его части охвачены цифровыми подписями. Это значение используется, когда определённые части документа остаются неподписанными или исключены из охвата подписью.

### Undefined {#Undefined}
```
public static final int Undefined
```

Указывает, что состояние охвата цифровыми подписями в документе неопределено. Это значение обычно используется, когда одна или несколько подписей в документе скомпрометированы или не могут быть проверены, что не позволяет дать окончательную оценку охвата подписью.
