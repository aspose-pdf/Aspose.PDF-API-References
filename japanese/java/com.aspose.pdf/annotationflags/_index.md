---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フラグ アノテーションのさまざまな特性を指定するバイナリフラグのセットです。"
type: docs
weight: 90
url: /ja/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

フラグ アノテーションのさまざまな特性を指定するバイナリフラグのセットです。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Default](#Default) | 既定値。 |
| [Hidden](#Hidden) | 設定されている場合、注釈の表示や印刷、ユーザーとの相互作用を行わないようにします。注釈の種類や注釈ハンドラの有無に関係なく動作します。画面領域が限られている場合、注釈を選択的に非表示・表示できる機能を外観ストリームと組み合わせて使用することで、オンラインヘルプシステムと同様の機能を持つ補助的なポップアップ情報を表示できます。 |
| [Invisible](#Invisible) | 設定されている場合、標準の注釈タイプのいずれにも属さず、注釈ハンドラが利用できない注釈は表示しません。クリアされている場合、存在すれば外観辞書で指定された外観ストリームを使用して、そのような不明な注釈を表示します。 |
| [Locked](#Locked) | 設定されている場合、ユーザーによる注釈の削除やプロパティ（位置やサイズを含む）の変更を許可しません。ただし、このフラグはフォームフィールドの値など、注釈の内容の変更は制限しません。 |
| [LockedContents](#LockedContents) | 設定されている場合、ユーザーによる注釈の内容の変更を許可しません。このフラグは注釈の削除や位置・サイズなど他のプロパティの変更は制限しません。 |
| [NoRotate](#NoRotate) | 設定されている場合、ページの回転に合わせて注釈の外観を回転させません。注釈矩形の左上隅はページ回転に関係なく固定された位置に留まります。 |
| [NoView](#NoView) | 設定されている場合、画面上に注釈を表示せず、ユーザーとの相互作用も許可しません。注釈は（Print フラグの設定に応じて）印刷されることがありますが、画面表示やユーザー操作の目的では非表示とみなすべきです。 |
| [NoZoom](#NoZoom) | 設定されている場合、ページの拡大率に合わせて注釈の外観を拡大縮小しません。注釈のページ上の位置（注釈矩形の左上隅で定義される）は、ページの拡大率に関係なく固定されたままです。 |
| [Print](#Print) | 設定されている場合、ページが印刷されるときに注釈を印刷します。クリアされている場合、画面に表示されているかどうかに関係なく注釈は印刷されません。たとえば、インタラクティブなプッシュボタンを表す注釈など、印刷ページで意味を持たないものに有用です。 |
| [ReadOnly](#ReadOnly) | 設定されている場合、ユーザーとの相互作用を注釈が行わないようにします。注釈は（NoView および Print フラグの設定に応じて）表示または印刷されることがありますが、マウスクリックに応答したり、マウスの動きに応じて外観を変えたりしません。このフラグはウィジェット注釈には無視され、関連するフォームフィールドの ReadOnly フラグの機能に置き換えられます。 |
| [ToggleNoView](#ToggleNoView) | 設定されている場合、特定のイベントに対して NoView フラグの解釈を反転させます。典型的な使用例は、マウスカーソルが上に乗っているときだけ表示される注釈です。 |

### Default {#Default}
```
public static final int Default
```

既定値。

### Hidden {#Hidden}
```
public static final int Hidden
```

設定されている場合、注釈の表示や印刷、ユーザーとの相互作用を行わないようにします。注釈の種類や注釈ハンドラの有無に関係なく動作します。画面領域が限られている場合、注釈を選択的に非表示・表示できる機能を外観ストリームと組み合わせて使用することで、オンラインヘルプシステムと同様の機能を持つ補助的なポップアップ情報を表示できます。

### Invisible {#Invisible}
```
public static final int Invisible
```

設定されている場合、標準の注釈タイプのいずれにも属さず、注釈ハンドラが利用できない注釈は表示しません。クリアされている場合、存在すれば外観辞書で指定された外観ストリームを使用して、そのような不明な注釈を表示します。

### Locked {#Locked}
```
public static final int Locked
```

設定されている場合、ユーザーによる注釈の削除やプロパティ（位置やサイズを含む）の変更を許可しません。ただし、このフラグはフォームフィールドの値など、注釈の内容の変更は制限しません。

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

設定されている場合、ユーザーによる注釈の内容の変更を許可しません。このフラグは注釈の削除や位置・サイズなど他のプロパティの変更は制限しません。

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

設定されている場合、ページの回転に合わせて注釈の外観を回転させません。注釈矩形の左上隅はページ回転に関係なく固定された位置に留まります。

### NoView {#NoView}
```
public static final int NoView
```

設定されている場合、画面上に注釈を表示せず、ユーザーとの相互作用も許可しません。注釈は（Print フラグの設定に応じて）印刷されることがありますが、画面表示やユーザー操作の目的では非表示とみなすべきです。

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

設定されている場合、ページの拡大率に合わせて注釈の外観を拡大縮小しません。注釈のページ上の位置（注釈矩形の左上隅で定義される）は、ページの拡大率に関係なく固定されたままです。

### Print {#Print}
```
public static final int Print
```

設定されている場合、ページが印刷されるときに注釈を印刷します。クリアされている場合、画面に表示されているかどうかに関係なく注釈は印刷されません。たとえば、インタラクティブなプッシュボタンを表す注釈など、印刷ページで意味を持たないものに有用です。

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

設定されている場合、ユーザーとの相互作用を注釈が行わないようにします。注釈は（NoView および Print フラグの設定に応じて）表示または印刷されることがありますが、マウスクリックに応答したり、マウスの動きに応じて外観を変えたりしません。このフラグはウィジェット注釈には無視され、関連するフォームフィールドの ReadOnly フラグの機能に置き換えられます。

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

設定されている場合、特定のイベントに対して NoView フラグの解釈を反転させます。典型的な使用例は、マウスカーソルが上に乗っているときだけ表示される注釈です。
