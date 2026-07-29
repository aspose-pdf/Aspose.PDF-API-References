---
title: "フォーム"
linktitle: "フォーム"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォームオブジェクトを表すクラスです。"
type: docs
weight: 1740
url: /ja/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

フォームオブジェクトを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | フォームにフィールドを追加します。 |
| [add](#add-com.aspose.pdf.Field-int-) | フォームにフィールドを追加します。 |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | フォームに新しいフィールドを追加します; このフィールドが他のフォームまたはこのフォームに既に配置されている場合、フィールドのコピーが作成されます。 |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | フォームにフィールドを追加します。 |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | 指定された場所に、ドキュメントの指定ページにフィールドの追加外観を追加します。 |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | ドキュメントの指定ページにフィールドの追加外観を追加します。 |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | フォームの XFA を指定された値に設定します。 |
| [clear](#clear--) | フォームからすべてのフィールドを削除します。サポートされていません。 |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | フィールドがフォームに存在するかどうかを判定します。 |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | フォームに配置されたフィールドを配列にコピーします。 |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | フォームのフィールドを配列にコピーします。 |
| [delete](#delete-com.aspose.pdf.Field-) | フォームからフィールドを削除します。 |
| [delete](#delete-java.lang.String-) | 名前でフォームからフィールドを削除します。 |
| [flatten](#flatten--) | すべての静的フォームフィールドを削除し、その値をページに直接配置します。 |
| [get_Item](#get_Item-int-) | フィールドインデックスでフォームのフィールドを取得します。 |
| [get_Item](#get_Item-java.lang.String-) | フィールド名でフォームのフィールドを取得します。フィールドが見つからない場合は例外をスローします。 |
| [get_xfa](#get_xfa--) | 内部使用のみです。 |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | フィールド名でフィールドを検索します。フィールドが見つからない場合は null を返します。 |
| [getAutoRecalculate](#getAutoRecalculate--) | このプロパティを設定すると、任意のフィールドが変更されたときにすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームに入力する際のパフォーマンスを向上させるため、false に設定してください。 |
| [getAutoRestoreForm](#getAutoRestoreForm--) | このプロパティを設定すると、注釈に存在する欠落したフォームフィールドが自動的に作成されます。 |
| [getDefaultAppearance](#getDefaultAppearance--) | フォームのデフォルト外観を取得します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、カラーを記述するオブジェクト）。 |
| [getDefaultResources](#getDefaultResources--) | このフォームに配置されたデフォルトリソースを取得します。 |
| [getDocument](#getDocument--) | 内部使用のみです。 |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないことへの対策として導入されました。デフォルトは false です。 |
| [getFields](#getFields--) | 階層フォームの最下位レベルにあるすべてのフィールドのリストを取得します。 |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | 指定された矩形内のフィールドを返します。 |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値は無視されます。デフォルトは false です。 |
| [getNeedsRendering](#getNeedsRendering--) | ドキュメントが動的 XFA フォームの削除を必要とするかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し {@code NeedsRendering}({@link #getNeedsRendering}) が false の場合に、{@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) を使用して XFA フォームを削除すべきかどうかを判断するために導入されました。 |
| [getRemovePermission](#getRemovePermission--) | このプロパティが true の場合、動的ドキュメントを標準に変換した後、PDF ドキュメントから "Perms" 辞書が削除されます。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。デフォルトは false です。 |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | このプロパティを設定すると、ファイルが増分更新ではなく、以前の内容を変更する形で保存（書き込み）された場合に無効になる可能性のある署名がドキュメントに含まれます。 |
| [getSignaturesExist](#getSignaturesExist--) | このプロパティを設定すると、ドキュメントに少なくとも 1 つの署名フィールドが含まれます。 |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | フォームは署名情報を含むことができ、署名済みまたは未署名のいずれかです。また、フォームの表示は署名の有無に依存することがあります。このプロパティは、フォームのコンバータ（例：XFA フォームを標準フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。 |
| [getSyncRoot](#getSyncRoot--) | 同期オブジェクトを返します。 |
| [getType](#getType--) | フォームのタイプを取得します。可能な値は: Standard、Static、Dynamic です。 |
| [getXFA](#getXFA--) | フォームの XFA データを取得します（存在する場合）。 |
| [hasField](#hasField-com.aspose.pdf.Field-) | フォームに指定されたフィールドが既に存在するか確認します。 |
| [hasField](#hasField-java.lang.String-) | 指定された名前のフィールドが既にフォームに追加されているかどうかを判断します。 |
| [hasField](#hasField-java.lang.String-boolean-) | 指定された名前のフィールドが既にフォームに追加されているかどうかを、子フィールドの階層も検索できるように判断します。 |
| [hasXfa](#hasXfa--) | ドキュメントに XFA フォームが含まれているかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し {@code NeedsRendering}({@link #getNeedsRendering}) が false の場合に、{@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) を使用して XFA フォームを削除すべきかどうかを判断するために導入されました。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを判断します。常に false を返します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトがスレッドセーフである場合に true を返します。 |
| [iterator](#iterator--) | フォーム フィールドの列挙を取得します。 |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * PDF フォーム フィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。 / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | フォームからフィールドを削除します。 |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | 指定されたインデックスのフィールドの外観を削除します。子の外観が1つだけ残っている場合、メソッドはそれをフィールドに埋め込みます。 |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | このプロパティを設定すると、任意のフィールドが変更されたときにすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームに入力する際のパフォーマンスを向上させるため、false に設定してください。 |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | このプロパティを設定すると、注釈に存在する欠落したフォームフィールドが自動的に作成されます。 |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | フィールド計算の順序を設定できるようにします。 |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | フォームのデフォルト外観を設定します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、色を記述するオブジェクト）。 |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないことへの対策として導入されました。デフォルトは false です。 |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値は無視されます。デフォルトは false です。 |
| [setRemovePermission](#setRemovePermission-boolean-) | このプロパティが true の場合、動的ドキュメントを標準に変換した後、PDF ドキュメントから "Perms" 辞書が削除されます。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。デフォルトは false です。 |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | このプロパティを設定すると、ファイルが増分更新ではなく、以前の内容を変更する形で保存（書き込み）された場合に無効になる可能性のある署名がドキュメントに含まれます。 |
| [setSignaturesExist](#setSignaturesExist-boolean-) | このプロパティを設定すると、ドキュメントに少なくとも 1 つの署名フィールドが含まれます。 |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | フォームは署名情報を含むことができ、署名済みまたは未署名のいずれかです。また、フォームの表示は署名の有無に依存することがあります。このプロパティは、フォームのコンバータ（例：XFA フォームを標準フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。 |
| [setType](#setType-com.aspose.pdf.FormType-) | フォームのタイプを取得します。可能な値は: Standard、Static、Dynamic です。 |
| [size](#size--) | このフォームのフィールド数を取得します。 |

### Form {#Form-com.aspose.pdf.IDocument-}
コンストラクタ

### add {#add-com.aspose.pdf.Field-}
フォームにフィールドを追加します。

### add {#add-com.aspose.pdf.Field-int-}
フォームにフィールドを追加します。

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
フォームに新しいフィールドを追加します; このフィールドが他のフォームまたはこのフォームに既に配置されている場合、フィールドのコピーが作成されます。

### add {#add-com.aspose.pdf.WidgetAnnotation-}
フォームにフィールドを追加します。

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
指定された場所に、ドキュメントの指定ページにフィールドの追加外観を追加します。

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
ドキュメントの指定ページにフィールドの追加外観を追加します。

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
フォームの XFA を指定された値に設定します。

### clear {#clear--}
```
public void clear()
```

フォームからすべてのフィールドを削除します。サポートされていません。

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
フィールドがフォームに存在するかどうかを判定します。

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
フォームに配置されたフィールドを配列にコピーします。

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
フォームのフィールドを配列にコピーします。

### delete {#delete-com.aspose.pdf.Field-}
フォームからフィールドを削除します。

### delete {#delete-java.lang.String-}
名前でフォームからフィールドを削除します。

### flatten {#flatten--}
```
public void flatten()
```

すべての静的フォームフィールドを削除し、その値をページに直接配置します。

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

フィールドインデックスでフォームのフィールドを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | フィールドのインデックス。 |

**Returns:**
取得したフィールド。

### get_Item {#get_Item-java.lang.String-}
フィールド名でフォームのフィールドを取得します。フィールドが見つからない場合は例外をスローします。

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

内部使用のみです。

**Returns:**
XFA オブジェクト

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  |  |

### get {#get-java.lang.String-}
フィールド名でフィールドを検索します。フィールドが見つからない場合は null を返します。

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

このプロパティを設定すると、任意のフィールドが変更されたときにすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームに入力する際のパフォーマンスを向上させるため、false に設定してください。

**Returns:**
ブール値

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

このプロパティを設定すると、注釈に存在する欠落したフォームフィールドが自動的に作成されます。

**Returns:**
ブール値

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

フォームのデフォルト外観を取得します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、カラーを記述するオブジェクト）。

**Returns:**
DefaultAppearance オブジェクト

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

このフォームに配置されたデフォルトリソースを取得します。

**Returns:**
Resources 値

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

内部使用のみです。

**Returns:**
IDocument オブジェクト

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないことへの対策として導入されました。デフォルトは false です。

**Returns:**
ブール値

### getFields {#getFields--}
```
public Field [] getFields()
```

階層フォームの最下位レベルにあるすべてのフィールドのリストを取得します。

**Returns:**
見つかったフィールドの配列。

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
指定された矩形内のフィールドを返します。

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値は無視されます。デフォルトは false です。

**Returns:**
ブール値

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

ドキュメントが動的 XFA フォームの削除を必要とするかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し {@code NeedsRendering}({@link #getNeedsRendering}) が false の場合に、{@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) を使用して XFA フォームを削除すべきかどうかを判断するために導入されました。

**Returns:**
ブール値

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

このプロパティが true の場合、動的ドキュメントを標準に変換した後、PDF ドキュメントから "Perms" 辞書が削除されます。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。デフォルトは false です。

**Returns:**
ブール値

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

このプロパティを設定すると、ファイルが増分更新ではなく、以前の内容を変更する形で保存（書き込み）された場合に無効になる可能性のある署名がドキュメントに含まれます。

**Returns:**
ブール値

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

このプロパティを設定すると、ドキュメントに少なくとも 1 つの署名フィールドが含まれます。

**Returns:**
ブール値

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

フォームは署名情報を含むことができ、署名済みまたは未署名のいずれかです。また、フォームの表示は署名の有無に依存することがあります。このプロパティは、フォームのコンバータ（例：XFA フォームを標準フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。

**Returns:**
SignDependentElementsRenderingModes 要素 @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同期オブジェクトを返します。

**Returns:**
同期用オブジェクト

### getType {#getType--}
```
public FormType getType()
```

フォームのタイプを取得します。可能な値は: Standard、Static、Dynamic です。

**Returns:**
FormType 値 @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

フォームの XFA データを取得します（存在する場合）。

**Returns:**
XFA 値

### hasField {#hasField-com.aspose.pdf.Field-}
フォームに指定されたフィールドが既に存在するか確認します。

### hasField {#hasField-java.lang.String-}
指定された名前のフィールドが既にフォームに追加されているかどうかを判断します。

### hasField {#hasField-java.lang.String-boolean-}
指定された名前のフィールドが既にフォームに追加されているかどうかを、子フィールドの階層も検索できるように判断します。

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

ドキュメントに XFA フォームが含まれているかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し {@code NeedsRendering}({@link #getNeedsRendering}) が false の場合に、{@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) を使用して XFA フォームを削除すべきかどうかを判断するために導入されました。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを判断します。常に false を返します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

オブジェクトがスレッドセーフである場合に true を返します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

フォーム フィールドの列挙を取得します。

**Returns:**
フィールド列挙子。

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * PDF フォーム フィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。 / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
フォームからフィールドを削除します。

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
指定されたインデックスのフィールドの外観を削除します。子の外観が1つだけ残っている場合、メソッドはそれをフィールドに埋め込みます。

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

このプロパティを設定すると、任意のフィールドが変更されたときにすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームに入力する際のパフォーマンスを向上させるため、false に設定してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

このプロパティを設定すると、注釈に存在する欠落したフォームフィールドが自動的に作成されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
フィールド計算の順序を設定できるようにします。

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
フォームのデフォルト外観を設定します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、色を記述するオブジェクト）。

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないことへの対策として導入されました。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値は無視されます。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

このプロパティが true の場合、動的ドキュメントを標準に変換した後、PDF ドキュメントから "Perms" 辞書が削除されます。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

このプロパティを設定すると、ファイルが増分更新ではなく、以前の内容を変更する形で保存（書き込み）された場合に無効になる可能性のある署名がドキュメントに含まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

このプロパティを設定すると、ドキュメントに少なくとも 1 つの署名フィールドが含まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

フォームは署名情報を含むことができ、署名済みまたは未署名のいずれかです。また、フォームの表示は署名の有無に依存することがあります。このプロパティは、フォームのコンバータ（例：XFA フォームを標準フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes 要素 @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
フォームのタイプを取得します。可能な値は: Standard、Static、Dynamic です。

### size {#size--}
```
public final int size()
```

このフォームのフィールド数を取得します。

**Returns:**
int 値です。
