---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, ReplaceText işlemi gerçekleştirildiğinde PdfContentEditor davranışını tanımlayan parametreleri içerir."
type: docs
weight: 650
url: /tr/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Bu sınıf, ReplaceText işlemi gerçekleştirildiğinde PdfContentEditor davranışını tanımlayan parametreleri içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Değiştirilen metin için uygun bir yazı tipi bulunamadığında gerçekleştirilen eylem (Throw exception / Substitute other font / Replace anyway). |
| [getReplaceScope](#getReplaceScope--) | Değiştirme işleminin kapsamı (replace first occurence or replace all occurences). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Yanlış ise, bulunacak dize basit bir metindir. Doğru ise, bulunacak dize düzenli ifadedir. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Değiştirilen metin için uygun bir yazı tipi bulunamadığında gerçekleştirilen eylem (Throw exception / Substitute other font / Replace anyway). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Yanlış ise, bulunacak dize basit bir metindir. Doğru ise, bulunacak dize düzenli ifadedir. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Değiştirme işleminin kapsamı (replace first occurence or replace all occurences). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Değiştirilen metin için uygun bir yazı tipi bulunamadığında gerçekleştirilen eylem (Throw exception / Substitute other font / Replace anyway).

**Returns:**
NoCharacterAction değeri. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Değiştirme işleminin kapsamı (replace first occurence or replace all occurences).

**Returns:**
Kapsam öğesi @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Yanlış ise, bulunacak dize basit bir metindir. Doğru ise, bulunacak dize düzenli ifadedir.

**Returns:**
boolean değer

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Değiştirilen metin için uygun bir yazı tipi bulunamadığında gerçekleştirilen eylem (Throw exception / Substitute other font / Replace anyway).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Yanlış ise, bulunacak dize basit bir metindir. Doğru ise, bulunacak dize düzenli ifadedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Değiştirme işleminin kapsamı (replace first occurence or replace all occurences).
