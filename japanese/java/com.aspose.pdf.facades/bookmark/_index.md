---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ブックマークを表します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

ブックマークを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Bookmark](#Bookmark--) | {@code Bookmark} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAction](#getAction--) | ブックマークにバインドされたアクションを取得します。PageNumber が指定されている場合、アクションは指定できません。アクションタイプには「GoTo」「GoToR」「Launch」「Named」が含まれます。 |
| [getBoldFlag](#getBoldFlag--) | ブックマークのタイトルの太字フラグを取得します。 |
| [getChildItem](#getChildItem--) | ブックマークの子要素を取得します。Obsolete("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | ブックマークの子要素を取得します。 |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | まだサポートされていません。Acrobat ビューアでメニュー項目を実行する対応するアクション名です。 |
| [getDestination](#getDestination--) | ブックマークのリンク先ページを取得します。アクションが "" に設定されている場合に必要です。 |
| [getItalicFlag](#getItalicFlag--) | ブックマークのタイトルのイタリックフラグを取得します。 |
| [getLevel](#getLevel--) | ブックマークの階層レベルを取得します。 |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | ページ表示の下端座標を取得します。 |
| [getPageDisplay_Left](#getPageDisplay_Left--) | ページ表示の左端座標を取得します。 |
| [getPageDisplay_Right](#getPageDisplay_Right--) | ページ表示の右端座標を取得します。 |
| [getPageDisplay_Top](#getPageDisplay_Top--) | ページ表示の上端座標を取得します。 |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | ページ表示のズーム倍率を取得します。 |
| [getPageDisplay](#getPageDisplay--) | ブックマークのリンク先ページの表示タイプを取得します。 |
| [getPageNumber](#getPageNumber--) | ブックマークのリンク先ページ番号を取得します。 |
| [getRemoteFile](#getRemoteFile--) | ブックマークの "GoToR" アクションに必要なファイル（パス）を取得します。 |
| [getTitle](#getTitle--) | ブックマークのタイトルを取得します。 |
| [getTitleColor](#getTitleColor--) | ブックマークのタイトルの色を取得します。 |
| [isOpen](#isOpen--) | ブックマークの状態（開く、閉じる）を取得します。 |
| [setAction](#setAction-java.lang.String-) | ブックマークにバインドされたアクションを設定します。PageNumber が指定されている場合、アクションは指定できません。アクションタイプには "GoTo"、"GoToR"、"Launch"、"Named" が含まれます。 |
| [setBoldFlag](#setBoldFlag-boolean-) | ブックマークのタイトルの太字フラグを設定します。 |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | ブックマークの子要素を設定します。Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | ブックマークの子要素を設定します。 |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | まだサポートされていません。Acrobat ビューアでメニュー項目を実行する対応するアクション名を設定します。 |
| [setDestination](#setDestination-java.lang.String-) | ブックマークのリンク先ページを設定します。アクションが "" に設定されている場合に必要です。 |
| [setItalicFlag](#setItalicFlag-boolean-) | ブックマークのタイトルのイタリックフラグを設定します。 |
| [setLevel](#setLevel-int-) | ブックマークの階層レベルを設定します。 |
| [setOpen](#setOpen-boolean-) | ブックマークの状態（開く、閉じる）を設定します。 |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | ページ表示の下端座標を設定します。 |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | ページ表示の左端座標を設定します。 |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | ページ表示の右端座標を設定します。 |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | ページ表示の上端座標を設定します。 |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | ページ表示のズーム倍率を設定します。 |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | 表示ブックマークの対象ページのタイプを設定します。 |
| [setPageNumber](#setPageNumber-int-) | ブックマークの対象ページ番号を設定します。 |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | ブックマークの "GoToR" アクションに必要なファイル（パス）を設定します。 |
| [setTitle](#setTitle-java.lang.String-) | ブックマークのタイトルを設定します。 |
| [setTitleColor](#setTitleColor-java.awt.Color-) | ブックマークのタイトルの色を設定します。 |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | OutlineItemCollection に変換します |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

{@code Bookmark} クラスの新しいインスタンスを初期化します。

### getAction {#getAction--}
```
public String getAction()
```

ブックマークにバインドされたアクションを取得します。PageNumber が指定されている場合、アクションは指定できません。アクションタイプには「GoTo」「GoToR」「Launch」「Named」が含まれます。

**Returns:**
文字列値

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

ブックマークのタイトルの太字フラグを取得します。

**Returns:**
ブール値

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

ブックマークの子要素を取得します。Obsolete("Use getChildItems() property instead of this one.")

**Returns:**
ブックマーク要素

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

ブックマークの子要素を取得します。

**Returns:**
ブックマークの子アイテムです。

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

まだサポートされていません。Acrobat ビューアでメニュー項目を実行する対応するアクション名です。

**Returns:**
int 値の配列

### getDestination {#getDestination--}
```
public String getDestination()
```

ブックマークのリンク先ページを取得します。アクションが "" に設定されている場合に必要です。

**Returns:**
文字列値

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

ブックマークのタイトルのイタリックフラグを取得します。

**Returns:**
ブール値

### getLevel {#getLevel--}
```
public int getLevel()
```

ブックマークの階層レベルを取得します。

**Returns:**
int 値です。

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

ページ表示の下端座標を取得します。

**Returns:**
int 値です。

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

ページ表示の左端座標を取得します。

**Returns:**
int 値です。

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

ページ表示の右端座標を取得します。

**Returns:**
int 値です。

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

ページ表示の上端座標を取得します。

**Returns:**
int 値です。

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

ページ表示のズーム倍率を取得します。

**Returns:**
int 値です。

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

ブックマークのリンク先ページの表示タイプを取得します。

**Returns:**
文字列値

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

ブックマークのリンク先ページ番号を取得します。

**Returns:**
int 値です。

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

ブックマークの "GoToR" アクションに必要なファイル（パス）を取得します。

**Returns:**
文字列値

### getTitle {#getTitle--}
```
public String getTitle()
```

ブックマークのタイトルを取得します。

**Returns:**
文字列値

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

ブックマークのタイトルの色を取得します。

**Returns:**
色要素

### isOpen {#isOpen--}
```
public boolean isOpen()
```

ブックマークの状態（開く、閉じる）を取得します。

**Returns:**
ブール値

### setAction {#setAction-java.lang.String-}
ブックマークにバインドされたアクションを設定します。PageNumber が指定されている場合、アクションは指定できません。アクションタイプには "GoTo"、"GoToR"、"Launch"、"Named" が含まれます。

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

ブックマークのタイトルの太字フラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
ブックマークの子要素を設定します。Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
ブックマークの子要素を設定します。

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

まだサポートされていません。Acrobat ビューアでメニュー項目を実行する対応するアクション名を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値の配列 |

### setDestination {#setDestination-java.lang.String-}
ブックマークのリンク先ページを設定します。アクションが "" に設定されている場合に必要です。

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

ブックマークのタイトルのイタリックフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

ブックマークの階層レベルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

ブックマークの状態（開く、閉じる）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

ページ表示の下端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

ページ表示の左端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

ページ表示の右端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

ページ表示の上端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

ページ表示のズーム倍率を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPageDisplay {#setPageDisplay-java.lang.String-}
表示ブックマークの対象ページのタイプを設定します。

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

ブックマークの対象ページ番号を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRemoteFile {#setRemoteFile-java.lang.String-}
ブックマークの "GoToR" アクションに必要なファイル（パス）を設定します。

### setTitle {#setTitle-java.lang.String-}
ブックマークのタイトルを設定します。

### setTitleColor {#setTitleColor-java.awt.Color-}
ブックマークのタイトルの色を設定します。

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
OutlineItemCollection に変換します
