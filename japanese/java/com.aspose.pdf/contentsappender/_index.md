---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "コンテンツの変更を APPEND モードでのみ実行します。このモードにより、コンテンツに変更を加える前に不要で重いコンテンツの解析を回避できます。新しいコンテンツのみを追加します。"
type: docs
weight: 800
url: /ja/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

内容の変更は APPEND モードのみで実行します。このモードにより、内容に変更を加える前の不要で重いパース処理を回避できます。新しいオペレーターは内容の末尾または先頭に追加されるだけです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | ページが添付された ContentsAppender の新しいインスタンスを初期化します。 |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Form XObject を使用した ContentsAppender の新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | コンテンツの末尾に演算子を追加します。 |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | コンテンツの末尾に演算子を追加します。 |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | コンテンツの末尾に演算子を追加します。 |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | コンテンツの先頭に演算子を追加します。 |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | コンテンツの先頭に演算子を追加します。 |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | コンテンツの先頭に演算子を追加します。 |
| [getBeginCode](#getBeginCode--) | ページの開始位置に挿入する演算子を含む文字列。 |
| [getBeginOperators](#getBeginOperators--) | <p> 先頭の演算子を返します </p> |
| [getEndCode](#getEndCode--) | ページの末尾に追加する演算子を含む文字列。 |
| [getEndOperators](#getEndOperators--) | <p> 末尾の演算子を返します </p> |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します |
| [setBeginCode](#setBeginCode-java.lang.String-) | ページの開始位置に挿入する演算子を含む文字列。 |
| [setEndCode](#setEndCode-java.lang.String-) | ページの開始位置に挿入する演算子を含む文字列。 |
| [suppressUpdate](#suppressUpdate--) | コンテンツの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツは更新されません。 |
| [updateData](#updateData--) | これは UpdateData の新しいバージョンで、既存の内容のデコードを回避します。 |
| [updateDataOld](#updateDataOld--) | 変更を適用するために呼び出す必要があります。 |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
ページが添付された ContentsAppender の新しいインスタンスを初期化します。

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Form XObject を使用した ContentsAppender の新しいインスタンスを初期化します。

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
コンテンツの末尾に演算子を追加します。

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
コンテンツの末尾に演算子を追加します。

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
コンテンツの末尾に演算子を追加します。

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
コンテンツの先頭に演算子を追加します。

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
コンテンツの先頭に演算子を追加します。

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
コンテンツの先頭に演算子を追加します。

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

ページの開始位置に挿入する演算子を含む文字列。

**Returns:**
String オブジェクト

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> 先頭の演算子を返します </p>

**Returns:**
{@code List<Operator>} オブジェクト

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

ページの末尾に追加する演算子を含む文字列。

**Returns:**
String オブジェクト

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> 末尾の演算子を返します </p>

**Returns:**
{@code List<Operator>} オブジェクト

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

ドキュメントの更新を再開します

### setBeginCode {#setBeginCode-java.lang.String-}
ページの開始位置に挿入する演算子を含む文字列。

### setEndCode {#setEndCode-java.lang.String-}
ページの開始位置に挿入する演算子を含む文字列。

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

コンテンツの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツは更新されません。

### updateData {#updateData--}
```
public void updateData()
```

これは UpdateData の新しいバージョンで、既存の内容のデコードを回避します。

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

変更を適用するために呼び出す必要があります。
