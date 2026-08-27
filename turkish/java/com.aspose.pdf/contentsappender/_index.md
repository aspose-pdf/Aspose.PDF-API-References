---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yalnızca EKLEME (APPEND) modunda içerik değişiklikleri yapar. Bu mod, içeriklere bir değişiklik yapılmadan önce gereksiz ve ağır içerik ayrıştırmasını önlemeye olanak tanır. Sadece yeni içerik ekler."
type: docs
weight: 800
url: /tr/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Yalnızca APPEND modunda içerik değişiklikleri yapar. Bu mod, içeriklere bir değişiklik yapılmadan önce gereksiz ve ağır içerik ayrıştırmasını önlemeye olanak tanır. Yeni operatörleri yalnızca içeriğin sonuna ya da başına ekler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Sayfa ekli yeni bir içerik ekleyici örneği başlatır |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Form XObject ile yeni bir içerik ekleyici örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Operatörleri içeriğin sonuna ekler |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Operatörü içeriğin sonuna ekler |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Operatörleri içeriğin sonuna ekler |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Operatörleri içeriğin başına ekler |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Operatörü içeriğin başına ekler |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Operatörleri içeriğin başına ekler |
| [getBeginCode](#getBeginCode--) | Sayfanın başlangıcına eklemek için operatörleri içeren dize. |
| [getBeginOperators](#getBeginOperators--) | <p> başlangıç operatörlerini döndürür </p> |
| [getEndCode](#getEndCode--) | Sayfanın sonuna eklemek için operatörleri içeren dize. |
| [getEndOperators](#getEndOperators--) | <p> son operatörleri döndürür </p> |
| [resumeUpdate](#resumeUpdate--) | belge güncellemesini devam ettirir |
| [setBeginCode](#setBeginCode-java.lang.String-) | Sayfanın başlangıcına eklemek için operatörleri içeren dize. |
| [setEndCode](#setEndCode-java.lang.String-) | Sayfanın başlangıcına eklemek için operatörleri içeren dize. |
| [suppressUpdate](#suppressUpdate--) | İçerik güncelleme verisini bastırır. İçerik, ResumeUpdate çağrılana kadar güncellenmez. |
| [updateData](#updateData--) | Bu, mevcut içeriklerin kod çözümlemesini önleyen UpdateData'nın yeni sürümüdür. |
| [updateDataOld](#updateDataOld--) | Değişiklikleri uygulamak için çağrılmalıdır |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Sayfa ekli yeni bir içerik ekleyici örneği başlatır

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Form XObject ile yeni bir içerik ekleyici örneği başlatır.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Operatörleri içeriğin sonuna ekler

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Operatörü içeriğin sonuna ekler

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Operatörleri içeriğin sonuna ekler

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Operatörleri içeriğin başına ekler

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Operatörü içeriğin başına ekler

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Operatörleri içeriğin başına ekler

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Sayfanın başlangıcına eklemek için operatörleri içeren dize.

**Returns:**
Dize nesnesi

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> başlangıç operatörlerini döndürür </p>

**Returns:**
{@code List<Operator>} nesnesi

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Sayfanın sonuna eklemek için operatörleri içeren dize.

**Returns:**
Dize nesnesi

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> son operatörleri döndürür </p>

**Returns:**
{@code List<Operator>} nesnesi

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

belge güncellemesini devam ettirir

### setBeginCode {#setBeginCode-java.lang.String-}
Sayfanın başlangıcına eklemek için operatörleri içeren dize.

### setEndCode {#setEndCode-java.lang.String-}
Sayfanın başlangıcına eklemek için operatörleri içeren dize.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

İçerik güncelleme verisini bastırır. İçerik, ResumeUpdate çağrılana kadar güncellenmez.

### updateData {#updateData--}
```
public void updateData()
```

Bu, mevcut içeriklerin kod çözümlemesini önleyen UpdateData'nın yeni sürümüdür.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Değişiklikleri uygulamak için çağrılmalıdır
