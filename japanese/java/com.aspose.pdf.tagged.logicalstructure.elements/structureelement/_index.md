---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造における構造要素の基底クラスを表します。"
type: docs
weight: 110
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

論理構造における構造要素の基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 現在の構造要素の親要素を変更する |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | 現在の構造要素の親要素を変更する |
| [clearId](#clearId--) | 構造要素の ID をクリアする。 |
| [generateId](#generateId--) | 構造要素の ID を生成する。 |
| [getActualText](#getActualText--) | 構造要素の実際のテキストを取得または設定します。 |
| [getAlternativeText](#getAlternativeText--) | 構造要素の代替テキストを取得または設定します。 |
| [getAttributes](#getAttributes--) | {@code StructureAttributeCollection} オブジェクトを取得します。 |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} オブジェクトを取得します。値: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} オブジェクト。 |
| [getExpansionText](#getExpansionText--) | 構造要素の拡張テキストを取得または設定します。 |
| [getID](#getID--) | 構造要素の ID を取得します。値: 構造要素の ID。 |
| [getLanguage](#getLanguage--) | 構造要素の言語を取得または設定します。 |
| [getPage](#getPage--) | 一部またはすべての子要素がレンダリングされるページを取得します。 |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | 構造要素のタイプを取得します。 |
| [getTitle](#getTitle--) | 構造要素のタイトルを取得または設定します。 |
| [remove](#remove--) | 削除します: 構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、ドキュメントからの対応するオブジェクト。 |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | 構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。 |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | 構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。 |
| [setActualText](#setActualText-java.lang.String-) | 構造要素の実際のテキストを取得または設定します。 |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | 構造要素の代替テキストを取得または設定します。 |
| [setExpansionText](#setExpansionText-java.lang.String-) | 構造要素の拡張テキストを取得または設定します。 |
| [setId](#setId-java.lang.String-) | 構造要素の ID を設定します。 |
| [setLanguage](#setLanguage-java.lang.String-) | 構造要素の言語を取得または設定します。 |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 親要素を設定 |
| [setTag](#setTag-java.lang.String-) | 構造要素のカスタムタグを設定します。 |
| [setTitle](#setTitle-java.lang.String-) | 構造要素のタイトルを取得または設定します。 |
| [tag](#tag-com.aspose.pdf.Annotation-) | 構造要素をアノテーションにバインドします。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 構造要素をアーティファクトにバインドします。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 構造要素をコンテンツストリームの BDC 演算子にバインドします。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 構造要素をコンテンツストリームの XForm にバインドします。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 構造要素を XImage にバインドします。 |
| [toString](#toString--) | 現在のオブジェクトを表す文字列を返します。 |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
現在の構造要素の親要素を変更する

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
現在の構造要素の親要素を変更する

### clearId {#clearId--}
```
public final void clearId()
```

構造要素の ID をクリアする。

### generateId {#generateId--}
```
public final void generateId()
```

構造要素の ID を生成する。

### getActualText {#getActualText--}
```
public final String getActualText()
```

構造要素の実際のテキストを取得または設定します。

**Returns:**
値: 構造要素の実際のテキスト。

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

構造要素の代替テキストを取得または設定します。

**Returns:**
値: 構造要素の代替テキスト。

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

{@code StructureAttributeCollection} オブジェクトを取得します。

**Returns:**
{@code StructureAttributeCollection} オブジェクト。

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

{@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} オブジェクトを取得します。値: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} オブジェクト。

**Returns:**
AttributeOwnerStandard インスタンス

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

構造要素の拡張テキストを取得または設定します。

**Returns:**
値: 構造要素の拡張テキスト。

### getID {#getID--}
```
public final String getID()
```

構造要素の ID を取得します。値: 構造要素の ID。

**Returns:**
文字列値

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

構造要素の言語を取得または設定します。

**Returns:**
値: 構造要素の言語。

### getPage {#getPage--}
```
public final Page getPage()
```

一部またはすべての子要素がレンダリングされるページを取得します。

**Returns:**
ページインスタンス

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

構造要素のタイプを取得します。

**Returns:**
値: 構造要素の {@code StructureTypeStandard} オブジェクト。

### getTitle {#getTitle--}
```
public final String getTitle()
```

構造要素のタイトルを取得または設定します。

**Returns:**
値: 構造要素のタイトル。

### remove {#remove--}
```
public final void remove()
```

削除します: 構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、ドキュメントからの対応するオブジェクト。

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

構造から要素、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | 削除されたオブジェクトの子オブジェクトを、その親の子オブジェクトコレクションに挿入できるかどうかを確認します。 |

### setActualText {#setActualText-java.lang.String-}
構造要素の実際のテキストを取得または設定します。

### setAlternativeText {#setAlternativeText-java.lang.String-}
構造要素の代替テキストを取得または設定します。

### setExpansionText {#setExpansionText-java.lang.String-}
構造要素の拡張テキストを取得または設定します。

### setId {#setId-java.lang.String-}
構造要素の ID を設定します。

### setLanguage {#setLanguage-java.lang.String-}
構造要素の言語を取得または設定します。

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
親要素を設定

### setTag {#setTag-java.lang.String-}
構造要素のカスタムタグを設定します。

### setTitle {#setTitle-java.lang.String-}
構造要素のタイトルを取得または設定します。

### tag {#tag-com.aspose.pdf.Annotation-}
構造要素をアノテーションにバインドします。

### tag {#tag-com.aspose.pdf.Artifact-}
構造要素をアーティファクトにバインドします。

### tag {#tag-com.aspose.pdf.operators.BDC-}
構造要素をコンテンツストリームの BDC 演算子にバインドします。

### tag {#tag-com.aspose.pdf.XForm-}
構造要素をコンテンツストリームの XForm にバインドします。

### tag {#tag-com.aspose.pdf.XImage-}
構造要素を XImage にバインドします。

### toString {#toString--}
```
public String toString()
```

現在のオブジェクトを表す文字列を返します。

**Returns:**
現在のオブジェクトを表す文字列。
