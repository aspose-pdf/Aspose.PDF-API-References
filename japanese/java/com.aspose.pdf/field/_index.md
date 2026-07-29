---
title: "フィールド"
linktitle: "フィールド"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Acro フォームフィールドの基底クラス。"
type: docs
weight: 1380
url: /ja/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Acro フォームフィールドの基底クラス。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Generatorで使用するためのフィールドを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | このフィールドのサブフィールドを、指定されたインデックスから配列にコピーします。 |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | このフィールドのサブフィールドを、指定されたインデックスから配列にコピーします。 |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | フィールドに対して指定されたJavaScriptアクションを実行します。 |
| [flatten](#flatten--) | このフィールドを削除し、その値をページ上に直接配置します。 |
| [get_Item](#get_Item-int-) | インデックスでこのフィールドに含まれるサブフィールドを取得します。 |
| [get_Item](#get_Item-java.lang.String-) | サブフィールドの名前でこのフィールドに含まれるサブフィールドを取得します。 |
| [getAlternateName](#getAlternateName--) | フィールドの代替名を取得します（実際のフィールド名の代わりにユーザーインターフェイスでフィールドが識別される場所で使用される代替フィールド名）。代替名はAdobe Acrobatでフィールドのツールチップとして使用されます。 |
| [getAnnotationIndex](#getAnnotationIndex--) | ページ上のこの注釈のインデックスを取得します。 |
| [getMappingName](#getMappingName--) | ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を取得します。 |
| [getMaxFontSize](#getMaxFontSize--) | フィールド内容に使用できる最大フォントサイズです。サイズをチェックしない場合は -1 を指定します。 |
| [getMinFontSize](#getMinFontSize--) | フィールド内容に使用できる最小フォントサイズです。サイズをチェックしない場合は -1 を指定します。 |
| [getPageIndex](#getPageIndex--) | このフィールドを含むページのインデックスを取得します。 |
| [getPartialName](#getPartialName--) | フィールドの部分名を取得します。 |
| [getRect](#getRect--) | フィールドの矩形を取得します。 |
| [getSyncRoot](#getSyncRoot--) | 同期オブジェクトです。 |
| [getTabOrder](#getTabOrder--) | フィールドのタブ順序を取得または設定します。 |
| [getValue](#getValue--) | フィールドの値を取得します。 |
| [isFitIntoRectangle](#isFitIntoRectangle--) | true の場合、テキストが指定された矩形に収まるようにフォントサイズが縮小されます。 |
| [isGroup](#isGroup--) | このフィールドが非終端フィールド（つまりフィールドのグループ）であるかどうかを示すブール値を取得します。 |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Generatorサポート用のプロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。 |
| [isSynchronized](#isSynchronized--) | 辞書が同期されている場合は true を返します。 |
| [iterator](#iterator--) | 含まれるフィールドの列挙子を返します。 |
| [recalculate](#recalculate--) | フォーム上のすべての計算フィールドを再計算します。 |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | フィールドの代替名を設定します（実際のフィールド名の代わりにユーザーインターフェイスでフィールドが識別される場所で使用される代替フィールド名）。代替名はAdobe Acrobatでフィールドのツールチップとして使用されます。 |
| [setAnnotationIndex](#setAnnotationIndex-int-) | ページ上のこの注釈のインデックスを設定します。 |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | true の場合、テキストが指定された矩形に収まるようにフォントサイズが縮小されます。 |
| [setMappingName](#setMappingName-java.lang.String-) | ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を設定します。 |
| [setMaxFontSize](#setMaxFontSize-double-) | フィールド内容に使用できる最大フォントサイズです。サイズをチェックしない場合は -1 を指定します。 |
| [setMinFontSize](#setMinFontSize-double-) | フィールド内容に使用できる最小フォントサイズです。サイズをチェックしない場合は -1 を指定します。 |
| [setPartialName](#setPartialName-java.lang.String-) | フィールドの部分名を設定します。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | フィールドの位置を設定します。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | フィールドの矩形を設定します。 |
| [setSharedField](#setSharedField-boolean-) | Generatorサポート用のプロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。 |
| [setTabOrder](#setTabOrder-int-) | フィールドのタブ順序を取得または設定します。 |
| [setValue](#setValue-java.lang.String-) | 値を設定します。 |
| [size](#size--) | このフィールド内のサブフィールド数を取得します。（例：ラジオボタンフィールドの項目数） |
| [updateAppearances](#updateAppearances--) | 外観の値を更新します。 |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Generatorで使用するためのフィールドを作成します。

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
このフィールドのサブフィールドを、指定されたインデックスから配列にコピーします。

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
このフィールドのサブフィールドを、指定されたインデックスから配列にコピーします。

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
フィールドに対して指定されたJavaScriptアクションを実行します。

### flatten {#flatten--}
```
public void flatten()
```

このフィールドを削除し、その値をページ上に直接配置します。

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

インデックスでこのフィールドに含まれるサブフィールドを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 要求されたサブフィールドのインデックス。 |

**Returns:**
フィールドインスタンス。

### get_Item {#get_Item-java.lang.String-}
サブフィールドの名前でこのフィールドに含まれるサブフィールドを取得します。

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

フィールドの代替名を取得します（実際のフィールド名の代わりにユーザーインターフェイスでフィールドが識別される場所で使用される代替フィールド名）。代替名はAdobe Acrobatでフィールドのツールチップとして使用されます。

**Returns:**
文字列値

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

ページ上のこの注釈のインデックスを取得します。

**Returns:**
int 値です。

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を取得します。

**Returns:**
文字列値

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

フィールド内容に使用できる最大フォントサイズです。サイズをチェックしない場合は -1 を指定します。

**Returns:**
double 値

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

フィールド内容に使用できる最小フォントサイズです。サイズをチェックしない場合は -1 を指定します。

**Returns:**
double 値

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

このフィールドを含むページのインデックスを取得します。

**Returns:**
int 値です。

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

フィールドの部分名を取得します。

**Returns:**
文字列値

### getRect {#getRect--}
```
public Rectangle getRect()
```

フィールドの矩形を取得します。

**Returns:**
フィールドの矩形。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同期オブジェクトです。

**Returns:**
オブジェクトの値

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

フィールドのタブ順序を取得または設定します。

**Returns:**
int 値です。

### getValue {#getValue--}
```
public String getValue()
```

フィールドの値を取得します。

**Returns:**
文字列値

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

true の場合、テキストが指定された矩形に収まるようにフォントサイズが縮小されます。

**Returns:**
ブール値

### isGroup {#isGroup--}
```
public boolean isGroup()
```

このフィールドが非終端フィールド（つまりフィールドのグループ）であるかどうかを示すブール値を取得します。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Generatorサポート用のプロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

辞書が同期されている場合は true を返します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

含まれるフィールドの列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### recalculate {#recalculate--}
```
public boolean recalculate()
```

フォーム上のすべての計算フィールドを再計算します。

**Returns:**
再計算中にフィールドの値が変更された場合は true。

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
フィールドの代替名を設定します（実際のフィールド名の代わりにユーザーインターフェイスでフィールドが識別される場所で使用される代替フィールド名）。代替名はAdobe Acrobatでフィールドのツールチップとして使用されます。

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

ページ上のこの注釈のインデックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

true の場合、テキストが指定された矩形に収まるようにフォントサイズが縮小されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMappingName {#setMappingName-java.lang.String-}
ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を設定します。

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

フィールド内容に使用できる最大フォントサイズです。サイズをチェックしない場合は -1 を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

フィールド内容に使用できる最小フォントサイズです。サイズをチェックしない場合は -1 を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setPartialName {#setPartialName-java.lang.String-}
フィールドの部分名を設定します。

### setPosition {#setPosition-com.aspose.pdf.Point-}
フィールドの位置を設定します。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
フィールドの矩形を設定します。

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Generatorサポート用のプロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

フィールドのタブ順序を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setValue {#setValue-java.lang.String-}
値を設定します。

### size {#size--}
```
public int size()
```

このフィールド内のサブフィールド数を取得します。（例：ラジオボタンフィールドの項目数）

**Returns:**
int 値です。

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

外観の値を更新します。
