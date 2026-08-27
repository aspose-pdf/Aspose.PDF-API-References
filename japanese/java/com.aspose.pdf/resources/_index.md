---
title: "リソース"
linktitle: "リソース"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページリソースを表すクラスです。"
type: docs
weight: 4220
url: /ja/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

ページリソースを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | キャッシュされたデータをクリアし、メモリを解放しますなど。 |
| [getExtGStates](#getExtGStates--) | リソースからすべての ExGStates を取得します。 |
| [getFonts](#getFonts--) | {@code Fonts} リソースコレクションを取得します |
| [getFonts](#getFonts-boolean-) | フォントコレクションを返します。リソースにフォントエントリが含まれていない場合、CreateIfAbsent フラグに依存して作成されます。 |
| [getForms](#getForms--) | {@code Forms} フォームコレクションを取得します |
| [getImages](#getImages--) | {@code Images} 画像コレクションを取得します |
| [getResourceDictionary](#getResourceDictionary--) | 内部フィールド |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | リソースを取得します |
| [isCommonResource](#isCommonResource--) | このリソースが共通である場合は True です。つまり、複数のページで共有されている（ページ辞書に配置されるか、各ページでオブジェクト参照として配置される）ことを意味します。共通リソースの操作は非常に注意深く行う必要があります。例えば、あるページで共通リソースからオブジェクトを削除すると、削除されたオブジェクトが他のページで使用されていた場合、他のページでエラーが発生する可能性があります。 |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | 内部使用のみ！ |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

キャッシュされたデータをクリアし、メモリを解放しますなど。

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

リソースからすべての ExGStates を取得します。

**Returns:**
ExGStates の名前キーを持つ辞書を返します。

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

{@code Fonts} リソースコレクションを取得します

**Returns:**
FontCollection オブジェクト

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

フォントコレクションを返します。リソースにフォントエントリが含まれていない場合、CreateIfAbsent フラグに依存して作成されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createIfAbsent |  | このフラグが true の場合、このエントリが存在しないときにフォントが作成されます。 |

**Returns:**
フォントコレクション。

### getForms {#getForms--}
```
public XFormCollection getForms()
```

{@code Forms} フォームコレクションを取得します

**Returns:**
XFormCollection オブジェクト

### getImages {#getImages--}
```
public XImageCollection getImages()
```

{@code Images} 画像コレクションを取得します

**Returns:**
XImageCollection オブジェクト

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

内部フィールド

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
リソースを取得します

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

このリソースが共通である場合は True です。つまり、複数のページで共有されている（ページ辞書に配置されるか、各ページでオブジェクト参照として配置される）ことを意味します。共通リソースの操作は非常に注意深く行う必要があります。例えば、あるページで共通リソースからオブジェクトを削除すると、削除されたオブジェクトが他のページで使用されていた場合、他のページでエラーが発生する可能性があります。

**Returns:**
ブール値

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
内部使用のみ！
