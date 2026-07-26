---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDFドキュメントページからベクターグラフィックを抽出するためのオプションクラスを表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

PDFドキュメントページからベクターグラフィックを抽出するためのオプションクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | SvgExtractionOptions クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | サブパスを自動的に画像にグループ化するオプションを取得および設定します。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) オプションを除外します。 |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | PDF ドキュメントからすべてのサブパスを抽出し、個別の SVG 画像にするオプションを取得および設定します。 |
| [getExtractionAreaBound](#getExtractionAreaBound--) | SVG 抽出の領域を定義するバウンディング矩形を取得および設定します。 |
| [getGroupStrength](#getGroupStrength--) | サブパスを画像にグループ化する強度のオプションを取得および設定します。サブパスのグループ化度合いを構成できます。値の範囲は 0 から 1 です。0 の値は {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) オプションが有効になることに対応します。1 の値はページ上のすべてのベクターパスを単一の画像にします。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) が false のときに効果があります。デフォルト値は {@code 0.8} です。 |
| [getMinStrokeWidth](#getMinStrokeWidth--) | 生成される SVG で使用される最小ストローク幅を取得または設定します。PDF がそれより細いストローク幅を使用している場合、この幅に置き換えられます。デフォルト値は 0.5 です。この値は変換された PDF ページのユーザースペース単位で表されます。デフォルトでは 1 ユーザースペース単位は 1/72 インチ（0.35 mm）ですが、PDF ドキュメントで上書き可能です。変換により生成された SVG の実際の最小幅に影響を与えることがあります。 |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | サブパスが {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) で指定された矩形内にあるかどうかを厳密にチェックするオプションを取得および設定します。false に設定すると、{@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) に完全に含まれないサブパスも抽出されます。デフォルト値は {@code True} です。 |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | ページ上で見つかった XFrom を展開するかどうかを決定するフラグを取得および設定します。XFrom 要素は異なる SVG ファイルに分割される可能性があります。ページコンテンツの Do 文でレンダリングされた XForm のみが展開されます。入れ子になった XForm は展開されません。 |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | 指定された述語に対応する XForm のみを展開するオプションを取得および設定します。 |
| [setAutoGrouping](#setAutoGrouping-boolean-) | サブパスを自動的に画像にグループ化するオプションを取得および設定します。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) オプションを除外します。 |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | PDF ドキュメントからすべてのサブパスを抽出し、個別の SVG 画像にするオプションを取得および設定します。 |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | SVG 抽出の領域を定義するバウンディング矩形を取得および設定します。 |
| [setGroupStrength](#setGroupStrength-double-) | サブパスを画像にグループ化する強度のオプションを取得および設定します。サブパスのグループ化度合いを構成できます。値の範囲は 0 から 1 です。0 の値は {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) オプションが有効になることに対応します。1 の値はページ上のすべてのベクターパスを単一の画像にします。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) が false のときに効果があります。デフォルト値は {@code 0.8} です。 |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | 生成される SVG で使用される最小ストローク幅を取得または設定します。PDF がそれより細いストローク幅を使用している場合、この幅に置き換えられます。デフォルト値は 0.5 です。この値は変換された PDF ページのユーザースペース単位で表されます。デフォルトでは 1 ユーザースペース単位は 1/72 インチ（0.35 mm）ですが、PDF ドキュメントで上書き可能です。変換により生成された SVG の実際の最小幅に影響を与えることがあります。 |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | サブパスが {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) で指定された矩形内にあるかどうかを厳密にチェックするオプションを取得および設定します。false に設定すると、{@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) に完全に含まれないサブパスも抽出されます。デフォルト値は {@code True} です。 |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | ページ上で見つかった XFrom を展開するかどうかを決定するフラグを取得および設定します。XFrom 要素は異なる SVG ファイルに分割される可能性があります。ページコンテンツの Do 文でレンダリングされた XForm のみが展開されます。入れ子になった XForm は展開されません。 |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | 指定された述語に対応する XForm のみを展開するオプションを取得および設定します。 |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

SvgExtractionOptions クラスのインスタンスを作成します。

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

サブパスを自動的に画像にグループ化するオプションを取得および設定します。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) オプションを除外します。

**Returns:**
ブール値

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

PDF ドキュメントからすべてのサブパスを抽出し、個別の SVG 画像にするオプションを取得および設定します。

**Returns:**
ブール値

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

SVG 抽出の領域を定義するバウンディング矩形を取得および設定します。

**Returns:**
矩形インスタンス

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

サブパスを画像にグループ化する強度のオプションを取得および設定します。サブパスのグループ化度合いを構成できます。値の範囲は 0 から 1 です。0 の値は {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) オプションが有効になることに対応します。1 の値はページ上のすべてのベクターパスを単一の画像にします。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) が false のときに効果があります。デフォルト値は {@code 0.8} です。

**Returns:**
double 値

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

生成される SVG で使用される最小ストローク幅を取得または設定します。PDF がそれより細いストローク幅を使用している場合、この幅に置き換えられます。デフォルト値は 0.5 です。この値は変換された PDF ページのユーザースペース単位で表されます。デフォルトでは 1 ユーザースペース単位は 1/72 インチ（0.35 mm）ですが、PDF ドキュメントで上書き可能です。変換により生成された SVG の実際の最小幅に影響を与えることがあります。

**Returns:**
double 値

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

サブパスが {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) で指定された矩形内にあるかどうかを厳密にチェックするオプションを取得および設定します。false に設定すると、{@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) に完全に含まれないサブパスも抽出されます。デフォルト値は {@code True} です。

**Returns:**
ブール値

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

ページ上で見つかった XFrom を展開するかどうかを決定するフラグを取得および設定します。XFrom 要素は異なる SVG ファイルに分割される可能性があります。ページコンテンツの Do 文でレンダリングされた XForm のみが展開されます。入れ子になった XForm は展開されません。

**Returns:**
ブール値

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

指定された述語に対応する XForm のみを展開するオプションを取得および設定します。

**Returns:**
XFormPlacement インスタンスの内部 Predicate インスタンス

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

サブパスを自動的に画像にグループ化するオプションを取得および設定します。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) オプションを除外します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

PDF ドキュメントからすべてのサブパスを抽出し、個別の SVG 画像にするオプションを取得および設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
SVG 抽出の領域を定義するバウンディング矩形を取得および設定します。

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

サブパスを画像にグループ化する強度のオプションを取得および設定します。サブパスのグループ化度合いを構成できます。値の範囲は 0 から 1 です。0 の値は {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) オプションが有効になることに対応します。1 の値はページ上のすべてのベクターパスを単一の画像にします。このオプションは {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) が false のときに効果があります。デフォルト値は {@code 0.8} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

生成される SVG で使用される最小ストローク幅を取得または設定します。PDF がそれより細いストローク幅を使用している場合、この幅に置き換えられます。デフォルト値は 0.5 です。この値は変換された PDF ページのユーザースペース単位で表されます。デフォルトでは 1 ユーザースペース単位は 1/72 インチ（0.35 mm）ですが、PDF ドキュメントで上書き可能です。変換により生成された SVG の実際の最小幅に影響を与えることがあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

サブパスが {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) で指定された矩形内にあるかどうかを厳密にチェックするオプションを取得および設定します。false に設定すると、{@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) に完全に含まれないサブパスも抽出されます。デフォルト値は {@code True} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

ページ上で見つかった XFrom を展開するかどうかを決定するフラグを取得および設定します。XFrom 要素は異なる SVG ファイルに分割される可能性があります。ページコンテンツの Do 文でレンダリングされた XForm のみが展開されます。入れ子になった XForm は展開されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
指定された述語に対応する XForm のみを展開するオプションを取得および設定します。
