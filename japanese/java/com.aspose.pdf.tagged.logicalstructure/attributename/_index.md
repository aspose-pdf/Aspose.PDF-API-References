---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "属性名値用のクラスを表す。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

属性名値用のクラスを表す。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - 最後の子の割り当て矩形の後端がテーブルセルの内容矩形の後端と揃えられます。 |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - 最初の子の割り当て矩形の前端がテーブルセルの内容矩形の前端と揃えられます。 |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - 子要素はテーブルセルの内容矩形の前端と後端の両方に揃えられます。最初の子は Before の説明通りに配置され、最後の子は After の説明通りに配置され、子要素間は等間隔になります。子要素が1つだけの場合は、Before のように前端にのみ揃えられます。 |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle- 子要素はテーブルセル内で中央に配置されます。最初の子の割り当て矩形の前端とテーブルセルの内容矩形の前端との距離は、最後の子の割り当て矩形の後端とテーブルセルの内容矩形の後端との距離と同じになります。 |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - 境界線は短い線分の連続です。 |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - 境界線は点の連続です。 |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - 境界線は2本の実線です。2本の線とその間のスペースの合計が BorderThickness の値と等しくなります。 |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - 境界線はキャンバスに彫り込まれたように見えます。 |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - None と同じですが、テーブル要素の境界線競合解決に関しては例外です。 |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - 境界線により、全体のボックスがキャンバスに埋め込まれたように見えます。 |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - 境界線なし。計算された BorderThickness の値を 0 に強制します。 |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - 境界線により、全体のボックスがキャンバスから突き出ているように見えます（Inset の反対）。 |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - ボーダーはキャンバスから突き出ているように見えます（Groove の反対です）。 |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - ボーダーは単一の線分です。 |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| [Checked_off](#Checked_off) | Attribute checked: Off - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| [Checked_on](#Checked_on) | Attribute checked: On - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribute GlyphOrientationVertical: Auto - テキストのデフォルトの向きを指定します。テキストが全角（幅と高さが同じ）かどうかに応じて決まります。 |
| [Height_Auto](#Height_Auto) | Attribute Height: Auto - 要素の高さは、そのコンテンツの固有の高さによって決定されます。 |
| [InlineAlign_Center](#InlineAlign_Center) | Attribute InlineAlign: Center - 各子要素はテーブルセル内で中央に配置されます。子要素の割り当て矩形の開始辺とテーブルセルのコンテンツ矩形の開始辺との距離は、終了辺同士の距離と同じになります。 |
| [InlineAlign_End](#InlineAlign_End) | Attribute InlineAlign: End - 各子要素の割り当て矩形の終了辺がテーブルセルのコンテンツ矩形の終了辺と揃えられます。 |
| [InlineAlign_Start](#InlineAlign_Start) | Attribute InlineAlign: Start - 各子要素の割り当て矩形の開始辺がテーブルセルのコンテンツ矩形の開始辺と揃えられます。 |
| [LineHeight_Auto](#LineHeight_Auto) | Attribute LineHeight: Auto - BaselineShift の値に対する調整は行われません。 |
| [LineHeight_Normal](#LineHeight_Normal) | Attribute LineHeight: Normal - BaselineShift に指定された非ゼロの値を含めるように行の高さを調整します。 |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribute ListNumbering: Circle - 開いた円形の箇条書き記号です。 |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribute ListNumbering: Decimal - 10 進アラビア数字 (1-9、10-99、…)です。 |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribute ListNumbering: Disc - 実線の円形箇条書き記号です。 |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribute ListNumbering: LowerAlpha - 小文字のアルファベット (a, b, c, …)です。 |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribute ListNumbering: LowerRoman - 小文字のローマ数字 (i, ii, iii, iv, …)です。 |
| [ListNumbering_None](#ListNumbering_None) | Attribute ListNumbering: None - 自動番号付けは行われません。Lbl 要素（存在する場合）は任意のテキストを含み、番号付けスキームの対象ではありません。 |
| [ListNumbering_Square](#ListNumbering_Square) | Attribute ListNumbering: Square - 実線の四角形箇条書き記号です。 |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribute ListNumbering: UpperAlpha - 大文字のアルファベット (A, B, C, …)です。 |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribute ListNumbering: UpperRoman - 大文字のローマ数字 (I, II, III, IV, …)です。 |
| [Placement_Before](#Placement_Before) | Attribute Placement: Before - 要素の割り当て矩形の前端が最も近い包含参照領域の前端と一致するように配置されます。 |
| [Placement_Block](#Placement_Block) | Attribute Placement: Block - 包含参照領域または親 BLSE 内でブロック進行方向に積み重ねられます。 |
| [Placement_End](#Placement_End) | Attribute Placement: End - 要素の割り当て矩形の終了端が最も近い包含参照領域の終了端と一致するように配置されます。 |
| [Placement_Inline](#Placement_Inline) | Attribute Placement: Inline - 包含 BLSE 内でインライン進行方向に詰め込まれます。 |
| [Placement_Start](#Placement_Start) | 属性配置: 開始 - 要素の割り当て矩形の開始端が最も近い包含参照領域の開始端と一致するように配置されます。 |
| [Role_cb](#Role_cb) | 属性ロール: cb - チェックボックス。 |
| [Role_pb](#Role_pb) | 属性ロール: pb - プッシュボタン。 |
| [Role_rb](#Role_rb) | 属性ロール: rb - ラジオボタン。 |
| [Role_tv](#Role_tv) | 属性ロール: tv - テキスト値フィールド。 |
| [RubyAlign_Center](#RubyAlign_Center) | 属性 RubyAlign: Center - コンテンツはインライン進行方向で中央揃えにされます。 |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | 属性 RubyAlign: Distribute - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。ただし、テキストの開始端と終了端にもスペースが挿入されます。間隔は 1:2:1（開始:中間:終了）の比率で配分されます。ルビがテキスト行の開始にある場合は 0:1:1 の比率に、終了にある場合は 1:1:0 の比率に変更されます。 |
| [RubyAlign_End](#RubyAlign_End) | 属性 RubyAlign: End - コンテンツはインライン進行方向の終了端に揃えられます。 |
| [RubyAlign_Justify](#RubyAlign_Justify) | 属性 RubyAlign: Justify - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。 |
| [RubyAlign_Start](#RubyAlign_Start) | 属性 RubyAlign: Start - コンテンツはインライン進行方向の開始端に揃えられます。 |
| [RubyPosition_After](#RubyPosition_After) | 属性 RubyPosition: After - RT コンテンツは要素の後端に沿って揃えられます。 |
| [RubyPosition_Before](#RubyPosition_Before) | 属性 RubyPosition: Before - RT コンテンツは要素の前端に沿って揃えられます。 |
| [RubyPosition_Inline](#RubyPosition_Inline) | 属性 RubyPosition: Inline - RT と関連する RP 要素は RB 要素の後に、括弧コメントとしてフォーマットされます。 |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | 属性 RubyPosition: Warichu - RT と関連する RP 要素は RB 要素の後に、割り注としてフォーマットされます。 |
| [Scope_Both](#Scope_Both) | 属性スコープ: 両方。 |
| [Scope_Column](#Scope_Column) | 属性スコープ: 列。 |
| [Scope_Row](#Scope_Row) | 属性スコープ: 行。 |
| [TextAlign_Center](#TextAlign_Center) | 属性 TextAlign: Center - 開始端と終了端の間で中央揃えです。 |
| [TextAlign_End](#TextAlign_End) | 属性 TextAlign: End - 終了端に揃えられます。 |
| [TextAlign_Justify](#TextAlign_Justify) | 属性 TextAlign: Justify - 開始端と終了端の両方に揃えられ、必要に応じて各行の内部間隔が拡張されます。最後の行（または唯一の行）は開始端のみに揃えられます。 |
| [TextAlign_Start](#TextAlign_Start) | 属性 TextAlign: Start - 開始端に揃えられます。 |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | 属性 TextDecorationType: LineThrough - テキストの中央に横線が引かれます。 |
| [TextDecorationType_None](#TextDecorationType_None) | 属性 TextDecorationType: None - テキスト装飾はありません。 |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | 属性 TextDecorationType: Overline - テキストの上に線が引かれます。 |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | 属性 TextDecorationType: Underline - テキストの下に線が引かれます。 |
| [Width_Auto](#Width_Auto) | 属性 Width: Auto - 要素の幅は、そのコンテンツの固有幅によって決定されます。 |
| [WritingMode_LrTb](#WritingMode_LrTb) | 属性 WritingMode: LrTb - インラインの進行は左から右へ、ブロックの進行は上から下へ。これは西洋の書記体系で典型的な書字方向です。 |
| [WritingMode_RlTb](#WritingMode_RlTb) | 属性 WritingMode: RlTb - インラインの進行は右から左へ、ブロックの進行は上から下へ。これはアラビア語およびヘブライ語の書記体系で典型的な書字方向です。 |
| [WritingMode_TbRl](#WritingMode_TbRl) | 属性 WritingMode: TbRl - インラインの進行は上から下へ、ブロックの進行は右から左へ。これは中国語および日本語の書記体系で典型的な書字方向です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | 属性キーに対する属性名を取得します。 |
| [getAttributeKey](#getAttributeKey--) | 属性キーを取得します。 |
| [getName](#getName--) | 属性の名前値を取得します。 |
| [toString](#toString--) | 現在のオブジェクトを表す文字列を返します。 |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - 最後の子の割り当て矩形の後端がテーブルセルの内容矩形の後端と揃えられます。

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - 最初の子の割り当て矩形の前端がテーブルセルの内容矩形の前端と揃えられます。

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - 子要素はテーブルセルの内容矩形の前端と後端の両方に揃えられます。最初の子は Before の説明通りに配置され、最後の子は After の説明通りに配置され、子要素間は等間隔になります。子要素が1つだけの場合は、Before のように前端にのみ揃えられます。

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle- 子要素はテーブルセル内で中央に配置されます。最初の子の割り当て矩形の前端とテーブルセルの内容矩形の前端との距離は、最後の子の割り当て矩形の後端とテーブルセルの内容矩形の後端との距離と同じになります。

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - 境界線は短い線分の連続です。

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - 境界線は点の連続です。

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - 境界線は2本の実線です。2本の線とその間のスペースの合計が BorderThickness の値と等しくなります。

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - 境界線はキャンバスに彫り込まれたように見えます。

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - None と同じですが、テーブル要素の境界線競合解決に関しては例外です。

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - 境界線により、全体のボックスがキャンバスに埋め込まれたように見えます。

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - 境界線なし。計算された BorderThickness の値を 0 に強制します。

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - 境界線により、全体のボックスがキャンバスから突き出ているように見えます（Inset の反対）。

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - ボーダーはキャンバスから突き出ているように見えます（Groove の反対です）。

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - ボーダーは単一の線分です。

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - ラジオボタンまたはチェックボックスフィールドの状態です。

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribute checked: Off - ラジオボタンまたはチェックボックスフィールドの状態です。

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribute checked: On - ラジオボタンまたはチェックボックスフィールドの状態です。

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribute GlyphOrientationVertical: Auto - テキストのデフォルトの向きを指定します。テキストが全角（幅と高さが同じ）かどうかに応じて決まります。

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribute Height: Auto - 要素の高さは、そのコンテンツの固有の高さによって決定されます。

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribute InlineAlign: Center - 各子要素はテーブルセル内で中央に配置されます。子要素の割り当て矩形の開始辺とテーブルセルのコンテンツ矩形の開始辺との距離は、終了辺同士の距離と同じになります。

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribute InlineAlign: End - 各子要素の割り当て矩形の終了辺がテーブルセルのコンテンツ矩形の終了辺と揃えられます。

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribute InlineAlign: Start - 各子要素の割り当て矩形の開始辺がテーブルセルのコンテンツ矩形の開始辺と揃えられます。

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribute LineHeight: Auto - BaselineShift の値に対する調整は行われません。

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribute LineHeight: Normal - BaselineShift に指定された非ゼロの値を含めるように行の高さを調整します。

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribute ListNumbering: Circle - 開いた円形の箇条書き記号です。

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribute ListNumbering: Decimal - 10 進アラビア数字 (1-9、10-99、…)です。

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribute ListNumbering: Disc - 実線の円形箇条書き記号です。

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribute ListNumbering: LowerAlpha - 小文字のアルファベット (a, b, c, …)です。

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribute ListNumbering: LowerRoman - 小文字のローマ数字 (i, ii, iii, iv, …)です。

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribute ListNumbering: None - 自動番号付けは行われません。Lbl 要素（存在する場合）は任意のテキストを含み、番号付けスキームの対象ではありません。

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribute ListNumbering: Square - 実線の四角形箇条書き記号です。

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribute ListNumbering: UpperAlpha - 大文字のアルファベット (A, B, C, …)です。

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribute ListNumbering: UpperRoman - 大文字のローマ数字 (I, II, III, IV, …)です。

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribute Placement: Before - 要素の割り当て矩形の前端が最も近い包含参照領域の前端と一致するように配置されます。

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribute Placement: Block - 包含参照領域または親 BLSE 内でブロック進行方向に積み重ねられます。

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribute Placement: End - 要素の割り当て矩形の終了端が最も近い包含参照領域の終了端と一致するように配置されます。

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribute Placement: Inline - 包含 BLSE 内でインライン進行方向に詰め込まれます。

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

属性配置: 開始 - 要素の割り当て矩形の開始端が最も近い包含参照領域の開始端と一致するように配置されます。

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

属性ロール: cb - チェックボックス。

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

属性ロール: pb - プッシュボタン。

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

属性ロール: rb - ラジオボタン。

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

属性ロール: tv - テキスト値フィールド。

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

属性 RubyAlign: Center - コンテンツはインライン進行方向で中央揃えにされます。

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

属性 RubyAlign: Distribute - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。ただし、テキストの開始端と終了端にもスペースが挿入されます。間隔は 1:2:1（開始:中間:終了）の比率で配分されます。ルビがテキスト行の開始にある場合は 0:1:1 の比率に、終了にある場合は 1:1:0 の比率に変更されます。

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

属性 RubyAlign: End - コンテンツはインライン進行方向の終了端に揃えられます。

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

属性 RubyAlign: Justify - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

属性 RubyAlign: Start - コンテンツはインライン進行方向の開始端に揃えられます。

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

属性 RubyPosition: After - RT コンテンツは要素の後端に沿って揃えられます。

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

属性 RubyPosition: Before - RT コンテンツは要素の前端に沿って揃えられます。

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

属性 RubyPosition: Inline - RT と関連する RP 要素は RB 要素の後に、括弧コメントとしてフォーマットされます。

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

属性 RubyPosition: Warichu - RT と関連する RP 要素は RB 要素の後に、割り注としてフォーマットされます。

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

属性スコープ: 両方。

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

属性スコープ: 列。

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

属性スコープ: 行。

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

属性 TextAlign: Center - 開始端と終了端の間で中央揃えです。

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

属性 TextAlign: End - 終了端に揃えられます。

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

属性 TextAlign: Justify - 開始端と終了端の両方に揃えられ、必要に応じて各行の内部間隔が拡張されます。最後の行（または唯一の行）は開始端のみに揃えられます。

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

属性 TextAlign: Start - 開始端に揃えられます。

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

属性 TextDecorationType: LineThrough - テキストの中央に横線が引かれます。

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

属性 TextDecorationType: None - テキスト装飾はありません。

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

属性 TextDecorationType: Overline - テキストの上に線が引かれます。

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

属性 TextDecorationType: Underline - テキストの下に線が引かれます。

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

属性 Width: Auto - 要素の幅は、そのコンテンツの固有幅によって決定されます。

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

属性 WritingMode: LrTb - インラインの進行は左から右へ、ブロックの進行は上から下へ。これは西洋の書記体系で典型的な書字方向です。

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

属性 WritingMode: RlTb - インラインの進行は右から左へ、ブロックの進行は上から下へ。これはアラビア語およびヘブライ語の書記体系で典型的な書字方向です。

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

属性 WritingMode: TbRl - インラインの進行は上から下へ、ブロックの進行は右から左へ。これは中国語および日本語の書記体系で典型的な書字方向です。

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
属性キーに対する属性名を取得します。

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

属性キーを取得します。

**Returns:**
AttributeKey インスタンス

### getName {#getName--}
```
public final String getName()
```

属性の名前値を取得します。

**Returns:**
文字列値

### toString {#toString--}
```
public String toString()
```

現在のオブジェクトを表す文字列を返します。

**Returns:**
現在のオブジェクトを表す文字列。
