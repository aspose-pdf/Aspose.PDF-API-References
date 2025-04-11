---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName クラス。属性名値のクラスを表します。
type: docs
weight: 6220
url: /ja/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName クラス

属性名値のクラスを表します。

```csharp
public sealed class AttributeName
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | 属性キーを取得します。 |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | 属性の名前値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | 属性キーに対する属性名を取得します。 |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | 属性 BlockAlign: After - 最後の子の割り当て矩形の後端がテーブルセルのコンテンツ矩形のそれと整列します。 |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | 属性 BlockAlign: Before - 最初の子の割り当て矩形の前端がテーブルセルのコンテンツ矩形のそれと整列します。 |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | 属性 BlockAlign: Justify - 子がテーブルセルのコンテンツ矩形の前端と後端の両方に整列します。最初の子は Before の説明に従って配置され、最後の子は After の説明に従って配置され、子の間には均等な間隔が設けられます。子が1つだけの場合は、Before と同様に前端にのみ整列します。 |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | 属性 BlockAlign: Middle - 子がテーブルセル内で中央に配置されます。最初の子の割り当て矩形の前端とテーブルセルのコンテンツ矩形の前端との距離は、最後の子の割り当て矩形の後端とテーブルセルのコンテンツ矩形の後端との距離と同じでなければなりません。 |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | 属性 BorderStyle: Dashed - ボーダーは短い線分の系列です。 |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | 属性 BorderStyle: Dotted - ボーダーは点の系列です。 |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | 属性 BorderStyle: Double - ボーダーは2本の実線です。2本の線とその間のスペースの合計は BorderThickness の値に等しくなります。 |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | 属性 BorderStyle: Groove - ボーダーはキャンバスに彫り込まれたように見えます。 |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | 属性 BorderStyle: Hidden - None と同じですが、テーブル要素のボーダーの競合解決に関しては異なります。 |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | 属性 BorderStyle: Inset - ボーダーは全体のボックスがキャンバスに埋め込まれているように見えます。 |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | 属性 BorderStyle: None - ボーダーなし。BorderThickness の計算値を0に強制します。 |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | 属性 BorderStyle: Outset - ボーダーは全体のボックスがキャンバスから出ているように見えます（Inset の逆）。 |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | 属性 BorderStyle: Ridge - ボーダーはキャンバスから出ているように見えます（Groove の逆）。 |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | 属性 BorderStyle: Solid - ボーダーは単一の線分です。 |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | 属性 checked: Neutral - ラジオボタンまたはチェックボックスフィールドの状態。 |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | 属性 checked: Off - ラジオボタンまたはチェックボックスフィールドの状態。 |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | 属性 checked: On - ラジオボタンまたはチェックボックスフィールドの状態。 |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | 属性 GlyphOrientationVertical: Auto - テキストのデフォルトの向きを指定します。 |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | 属性 Height: Auto - 要素の高さはその内容の固有の高さによって決定されます。 |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | 属性 InlineAlign: Center - 各子がテーブルセル内で中央に配置されます。子の割り当て矩形の開始端とテーブルセルのコンテンツ矩形の開始端との距離は、終了端との距離と同じでなければなりません。 |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | 属性 InlineAlign: End - 各子の割り当て矩形の終了端がテーブルセルのコンテンツ矩形のそれと整列します。 |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | 属性 InlineAlign: Start - 各子の割り当て矩形の開始端がテーブルセルのコンテンツ矩形のそれと整列します。 |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | 属性 LineHeight: Auto - BaselineShift の値に対する調整は行われません。 |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | 属性 LineHeight: Normal - BaselineShift に指定された非ゼロ値を含むように行の高さを調整します。 |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | 属性 ListNumbering: Circle - 開いた円形の弾丸。 |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | 属性 ListNumbering: Decimal - 十進法のアラビア数字（1-9, 10-99, ...）。 |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | 属性 ListNumbering: Disc - 塗りつぶされた円形の弾丸。 |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | 属性 ListNumbering: LowerAlpha - 小文字のアルファベット（a, b, c, ...）。 |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | 属性 ListNumbering: LowerRoman - 小文字のローマ数字（i, ii, iii, iv, ...）。 |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | 属性 ListNumbering: None - 自動番号付けなし; Lbl 要素（存在する場合）は任意のテキストを含み、番号付けスキームの対象ではありません。 |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | 属性 ListNumbering: Square - 塗りつぶされた四角形の弾丸。 |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | 属性 ListNumbering: UpperAlpha - 大文字のアルファベット（A, B, C, ...）。 |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | 属性 ListNumbering: UpperRoman - 大文字のローマ数字（I, II, III, IV, ...）。 |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | 属性 Placement: Before - 要素の割り当て矩形の前端が最も近い囲い参照領域のそれと一致するように配置されます。 |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | 属性 Placement: Block - 囲い参照領域または親 BLSE 内でブロック進行方向にスタックされます。 |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | 属性 Placement: End - 要素の割り当て矩形の終了端が最も近い囲い参照領域のそれと一致するように配置されます。 |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | 属性 Placement: Inline - 囲い BLSE 内でインライン進行方向に詰め込まれます。 |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | 属性 Placement: Start - 要素の割り当て矩形の開始端が最も近い囲い参照領域のそれと一致するように配置されます。 |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | 属性 Role: cb - チェックボックス。 |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | 属性 Role: pb - プッシュボタン。 |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | 属性 Role: rb - ラジオボタン。 |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | 属性 Role: tv - テキスト値フィールド。 |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | 属性 RubyAlign: Center - コンテンツはインライン進行方向で中央に配置されます。 |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | 属性 RubyAlign: Distribute - コンテンツはインライン進行方向で利用可能な幅を埋めるように拡張されます。ただし、テキストの開始端と終了端にもスペースが挿入されます。間隔は1:2:1（開始:中間:終了）の比率で分配されます。テキスト行の開始にルビがある場合は0:1:1の比率に、テキスト行の終了にルビがある場合は1:1:0の比率に変更されます。 |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | 属性 RubyAlign: End - コンテンツはインライン進行方向で終了端に整列します。 |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | 属性 RubyAlign: Justify - コンテンツはインライン進行方向で利用可能な幅を埋めるように拡張されます。 |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | 属性 RubyAlign: Start - コンテンツはインライン進行方向で開始端に整列します。 |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | 属性 RubyPosition: After - RT コンテンツは要素の後端に沿って整列します。 |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | 属性 RubyPosition: Before - RT コンテンツは要素の前端に沿って整列します。 |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | 属性 RubyPosition: Inline - RT と関連する RP 要素は、RB 要素に続いて括弧コメントとしてフォーマットされます。 |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | 属性 RubyPosition: Warichu - RT と関連する RP 要素は、RB 要素に続いて割注としてフォーマットされます。 |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | 属性 Scope: Both。 |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | 属性 Scope: Column。 |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | 属性 Scope: Row。 |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | 属性 TextAlign: Center - 開始端と終了端の間で中央に配置されます。 |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | 属性 TextAlign: End - 終了端に整列します。 |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | 属性 TextAlign: Justify - 開始端と終了端の両方に整列し、必要に応じて各行内の間隔を拡張してその整列を達成します。最後の（または唯一の）行は開始端にのみ整列します。 |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | 属性 TextAlign: Start - 開始端に整列します。 |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | 属性 TextDecorationType: LineThrough - テキストの中央に線があります。 |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | 属性 TextDecorationType: None - テキスト装飾なし。 |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | 属性 TextDecorationType: Overline - テキストの上に線があります。 |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | 属性 TextDecorationType: Underline - テキストの下に線があります。 |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | 属性 Width: Auto - 要素の幅はその内容の固有の幅によって決定されます。 |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | 属性 WritingMode: LrTb - 左から右へのインライン進行; 上から下へのブロック進行。これは西洋の書き方の典型的なモードです。 |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | 属性 WritingMode: RlTb - 右から左へのインライン進行; 上から下へのブロック進行。これはアラビア語とヘブライ語の書き方の典型的なモードです。 |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | 属性 WritingMode: TbRl - 上から下へのインライン進行; 右から左へのブロック進行。これは中国語と日本語の書き方の典型的なモードです。 |

### 参照

* 名前空間 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* アセンブリ [Aspose.PDF](../../)