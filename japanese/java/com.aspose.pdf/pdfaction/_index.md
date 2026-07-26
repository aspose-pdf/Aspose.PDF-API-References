---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント内のアクションを表します"
type: docs
weight: 3670
url: /ja/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

PDF ドキュメント内のアクションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | ECMAScript アクションの文字列を取得します。 |
| [getNext](#getNext--) | シーケンス内の次のアクション。 |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

ECMAScript アクションの文字列を取得します。

**Returns:**
ECMAScript アクションの JS エントリ用の文字列を返します。そうでなければ null を返します。

### getNext {#getNext--}
```
public ActionCollection getNext()
```

シーケンス内の次のアクション。

**Returns:**
ActionCollection オブジェクト
