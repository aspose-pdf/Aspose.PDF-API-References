---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "演算子のコレクションを表すクラス"
type: docs
weight: 3190
url: /ja/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

演算子のコレクションを表すクラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | 内部使用のみ！ |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | 内部使用のみ！ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | IOperatorSelector ビジターオブジェクトを受け取り、演算子を処理します。 |
| [add](#add-java.lang.Iterable-) | 他のコレクションからすべての演算子をコレクションに追加します。 |
| [add](#add-com.aspose.pdf.Operator-) | <p> コレクションに新しい演算子を追加します。 </p> <hr> <p> 例は page.contents の末尾に演算子を追加する方法を示しています。 <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> contents 演算子の末尾に演算子を追加します。 </p> <hr> <p> 例はページ内容の末尾に演算子を追加する方法を示しています。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。 |
| [clear](#clear--) | <p> リストからすべての演算子を削除します。 </p> <hr> <p> 例はページ内容をクリアする方法を示しています。 </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | アンマネージド リソースの解放、リリース、またはリセットに関連する、アプリケーション定義のタスクを実行します。 |
| [contains](#contains-com.aspose.pdf.Operator-) | コレクションに指定されたオペレーターが含まれている場合、true を返します。 |
| [delete](#delete-int-) | <p> コレクションからオペレーターを削除します。 </p> <hr> <p> 例はインデックスでオペレーターを削除する方法を示しています。 <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | コレクションからオペレーターを削除します。 |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> コレクションからオペレーターを削除します。 </p> <hr> <p> 例はページコンテンツからオペレーターを削除する方法を示しています。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | Delete(index) の内部で制限のないバージョン |
| [dispose](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連する、アプリケーション定義のタスクを実行します。 |
| [get_Item](#get_Item-int-) | <p> インデックスでオペレーターを取得します。 </p> <hr> 例はインデックスでページコンテンツのオペレーターを取得する方法を示しています。 <pre> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | インデクサーの内部で制限のないバージョン |
| [insert](#insert-int-java.lang.Iterable-) | 指定された位置にオペレーターを挿入します。 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> コレクションにオペレーターを挿入します。 </p> <hr> <p> 例はページコンテンツにオペレーターを挿入する方法を示しています。 <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> 指定された位置にオペレーターを挿入します。 </p> <hr> <p> 例はページコンテンツにオペレーターを挿入する方法を示しています。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | オペレーターシーケンスの括弧状態を取得します。つまり、これらのオペレーターが q - Q ブロック内にあるかどうかです。 |
| [isCommandsParsed](#isCommandsParsed--) | 解析されたコマンドを取得します |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | コレクションが高速テキスト抽出に限定されているかどうかを示します |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | ページのコンテンツを記述するオペレーターの数を、初期化せずに取得します。 |
| [remove](#remove-com.aspose.pdf.Operator-) | コレクションからオペレーターを削除します。 |
| [replace](#replace-java.lang.Iterable-) | コレクション内のオペレーターを別のオペレーターに置き換えます。 |
| [replace](#replace-com.aspose.pdf.Operator:A-) | コレクション内のオペレーターを別のオペレーターに置き換えます。 |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。 |
| [resumeUpdate](#resumeUpdate-boolean-) | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。invalidate パラメータが true の場合、すべてのオペレーターを\"changed\"とマークします。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | インデックスでオペレーターを設定します。 |
| [size](#size--) | コレクション内のオペレーター数を取得します。 |
| [suppressUpdate](#suppressUpdate--) | コンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。 |
| [toList](#toList--) | オペレーターリストを返します。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |
| [updateData](#updateData--) | オブジェクトストリームを更新します。 |
| [updateNormalizedData](#updateNormalizedData--) | 欠落している GSave/GRestore 演算子を修正しながらオブジェクトストリームを更新します。 |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
内部使用のみ！

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
内部使用のみ！

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
IOperatorSelector ビジターオブジェクトを受け取り、演算子を処理します。

### add {#add-java.lang.Iterable-}
他のコレクションからすべての演算子をコレクションに追加します。

### add {#add-com.aspose.pdf.Operator-}
<p> コレクションに新しい演算子を追加します。 </p> <hr> <p> 例は page.contents の末尾に演算子を追加する方法を示しています。 <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> contents 演算子の末尾に演算子を追加します。 </p> <hr> <p> 例はページ内容の末尾に演算子を追加する方法を示しています。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。

### clear {#clear--}
```
public void clear()
```

<p> リストからすべての演算子を削除します。 </p> <hr> <p> 例はページ内容をクリアする方法を示しています。 </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

アンマネージド リソースの解放、リリース、またはリセットに関連する、アプリケーション定義のタスクを実行します。

### contains {#contains-com.aspose.pdf.Operator-}
コレクションに指定されたオペレーターが含まれている場合、true を返します。

### delete {#delete-int-}
```
public void delete(int index)
```

<p> コレクションからオペレーターを削除します。 </p> <hr> <p> 例はインデックスでオペレーターを削除する方法を示しています。 <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除すべき演算子のインデックス。演算子の番号は 1 から始まります。 |

### delete {#delete-java.lang.Iterable-}
コレクションからオペレーターを削除します。

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> コレクションからオペレーターを削除します。 </p> <hr> <p> 例はページコンテンツからオペレーターを削除する方法を示しています。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

Delete(index) の内部で制限のないバージョン

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

### dispose {#dispose--}
```
public final void dispose()
```

アンマネージド リソースの解放、リリース、またはリセットに関連する、アプリケーション定義のタスクを実行します。

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> インデックスでオペレーターを取得します。 </p> <hr> 例はインデックスでページコンテンツのオペレーターを取得する方法を示しています。 <pre> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 演算子のインデックス。番号は 1 から始まります。 |

**Returns:**
要求されたインデックスの演算子

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

インデクサーの内部で制限のないバージョン

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

**Returns:**
演算子オブジェクト

### insert {#insert-int-java.lang.Iterable-}
指定された位置にオペレーターを挿入します。

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> コレクションにオペレーターを挿入します。 </p> <hr> <p> 例はページコンテンツにオペレーターを挿入する方法を示しています。 <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> 指定された位置にオペレーターを挿入します。 </p> <hr> <p> 例はページコンテンツにオペレーターを挿入する方法を示しています。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

オペレーターシーケンスの括弧状態を取得します。つまり、これらのオペレーターが q - Q ブロック内にあるかどうかです。

**Returns:**
ブール値

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

解析されたコマンドを取得します

**Returns:**
ブール値

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

コレクションが高速テキスト抽出に限定されているかどうかを示します

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

コレクションの列挙子を返します

**Returns:**
コレクション列挙子

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

ページのコンテンツを記述するオペレーターの数を、初期化せずに取得します。

**Returns:**
int 値です。

### remove {#remove-com.aspose.pdf.Operator-}
コレクションからオペレーターを削除します。

### replace {#replace-java.lang.Iterable-}
コレクション内のオペレーターを別のオペレーターに置き換えます。

### replace {#replace-com.aspose.pdf.Operator:A-}
コレクション内のオペレーターを別のオペレーターに置き換えます。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。invalidate パラメータが true の場合、すべてのオペレーターを\"changed\"とマークします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| updateAll |  | true の場合、コレクション内のすべての演算子が更新済みとしてマークされます。 |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
インデックスでオペレーターを設定します。

### size {#size--}
```
public int size()
```

コレクション内のオペレーター数を取得します。

**Returns:**
int 値です。

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

コンテンツデータの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

オペレーターリストを返します。

**Returns:**
演算子リスト。

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。

### updateData {#updateData--}
```
public void updateData()
```

オブジェクトストリームを更新します。

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

欠落している GSave/GRestore 演算子を修正しながらオブジェクトストリームを更新します。
