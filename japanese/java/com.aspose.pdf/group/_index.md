---
title: "Group"
linktitle: "Group"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "透過イメージングモデルで使用するページのページグループの属性を指定するグループ属性クラスです。"
type: docs
weight: 1850
url: /ja/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

透過イメージングモデルで使用するページのページグループの属性を指定するグループ属性クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | コンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorSpace](#getColorSpace--) | ColorSpace <p> を取得します。 |
| [isKnockout](#isKnockout--) | 内部使用のみです。このフラグが false の場合、グループ内の後続オブジェクトは重なっている先行オブジェクトと合成されます。true の場合、グループの初期バックドロップと合成され、（\"knock out\"）で先行の重複オブジェクトを上書きします。 |
| [isTransparency](#isTransparency--) | 内部使用のみです。グループの透明度フラグを返します。 |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | グループのカラースペースです。 |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | このフラグが false の場合、グループ内の後続オブジェクトは重なっている先行オブジェクトと合成されます。true の場合、グループの初期バックドロップと合成され、（\"knock out\"）で先行の重複オブジェクトを上書きします。 |

### Group {#Group-com.aspose.pdf.Page-}
コンストラクタ。

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

ColorSpace <p> を取得します。

**Returns:**
ColorSpace の値。 @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

内部使用のみです。このフラグが false の場合、グループ内の後続オブジェクトは重なっている先行オブジェクトと合成されます。true の場合、グループの初期バックドロップと合成され、（\"knock out\"）で先行の重複オブジェクトを上書きします。

**Returns:**
ExtendedBoolean 要素 @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

内部使用のみです。グループの透明度フラグを返します。

**Returns:**
ブール値

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
グループのカラースペースです。

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
このフラグが false の場合、グループ内の後続オブジェクトは重なっている先行オブジェクトと合成されます。true の場合、グループの初期バックドロップと合成され、（\"knock out\"）で先行の重複オブジェクトを上書きします。
