---
title: "クラス AttributeName"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LogicalStructure.AttributeName クラス。属性名の値のクラスを表します。"
type: docs
weight: 6360
url: /ja/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

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
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribute BlockAlign: After - 最後の子要素の割り当て矩形の後端が、テーブルセルのコンテンツ矩形と揃えられます。 |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribute BlockAlign: Before - 最初の子要素の割り当て矩形の前端が、テーブルセルのコンテンツ矩形と揃えられます。 |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | 属性 BlockAlign: Justify - 子要素はテーブルセルのコンテンツ矩形の前端と後端の両方に揃えられます。最初の子要素は Before の説明どおりに配置され、最後の子要素は After の説明どおりに配置され、子要素間は等間隔です。子要素が1つだけの場合は、Before の端にのみ揃えられます。 |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | 属性 BlockAlign: Middle - 子要素はテーブルセル内で中央に配置されます。最初の子要素の割り当て矩形の前端とテーブルセルのコンテンツ矩形の前端との距離は、最後の子要素の割り当て矩形の後端とテーブルセルのコンテンツ矩形の後端との距離と同じになります。 |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | 属性 BorderStyle: Dashed - 境界線は短い線分の連続です。 |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | 属性 BorderStyle: Dotted - 境界線は点の連続です。 |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | 属性 BorderStyle: Double - 境界線は2本の実線です。2本の線とその間のスペースの合計が BorderThickness の値と等しくなります。 |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | 属性 BorderStyle: Groove - 境界線はキャンバスに彫り込まれたように見えます。 |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | 属性 BorderStyle: Hidden - None と同じですが、テーブル要素の境界線競合解決に関しては異なります。 |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | 属性 BorderStyle: Inset - 境界線により、全体のボックスがキャンバスに埋め込まれたように見えます。 |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | 属性 BorderStyle: None - 境界線なし。計算された BorderThicknessto の値を 0 に強制します。 |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | 属性 BorderStyle: Outset - 境界線により、全体のボックスがキャンバスから突き出ているように見えます（Inset の反対）。 |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | 属性 BorderStyle: Ridge - 境界線はキャンバスから突き出ているように見えます（Groove の反対）。 |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | 属性 BorderStyle: Solid - 境界線は単一の線分です。 |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | 属性 checked: Neutral - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | 属性 checked: Off - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | 属性 checked: On - ラジオボタンまたはチェックボックスフィールドの状態です。 |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | 属性 GlyphOrientationVertical: Auto - テキストが全角（幅と高さが同じ）かどうかに応じて、デフォルトの向きを指定します。 |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | 属性 Height: Auto - 要素の高さはコンテンツの固有高さに基づいて決定されます。 |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | 属性 InlineAlign: Center - 各子要素はテーブルセル内で中央に配置されます。子要素の割り当て矩形の開始端とテーブルセルのコンテンツ矩形の開始端との距離は、終了端同士の距離と同じになります。 |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | 属性 InlineAlign: End - 各子要素の割り当て矩形の終了端がテーブルセルのコンテンツ矩形の終了端と揃えられます。 |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | 属性 InlineAlign: Start - 各子要素の割り当て矩形の開始端がテーブルセルのコンテンツ矩形の開始端と揃えられます。 |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | 属性 LineHeight: Auto - BaselineShift の値に対する調整は行われません。 |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | 属性 LineHeight: Normal - BaselineShift に指定された非ゼロの値を含むように行の高さを調整します。 |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | 属性 ListNumbering: Circle - 開いた円形の箇条書き記号です。 |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | 属性 ListNumbering: Decimal - アラビア数字の十進数 (1-9、10-99、…)。 |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | 属性 ListNumbering: Disc - 実線の円形箇条書き記号です。 |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | 属性 ListNumbering: LowerAlpha - 小文字のアルファベット (a, b, c, ...)。 |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | 属性 ListNumbering: LowerRoman - 小文字のローマ数字 (i, ii, iii, iv, ...)。 |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | 属性 ListNumbering: None - 自動番号付けなし; Lbl 要素（存在する場合）は任意のテキストを含み、番号付けスキームの対象ではありません。 |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | 属性 ListNumbering: Square - 塗りつぶしの四角形の箇条書き記号。 |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | 属性 ListNumbering: UpperAlpha - 大文字のアルファベット (A, B, C, ...)。 |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | 属性 ListNumbering: UpperRoman - 大文字のローマ数字 (I, II, III, IV, ...)。 |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | 属性 Placement: Before - 要素の割り当て矩形の前端が最も近い包含参照領域の前端と一致するように配置されます。 |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | 属性 Placement: Block - 包含参照領域または親 BLSE 内でブロック進行方向に積み重ねられます。 |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | 属性 Placement: End - 要素の割り当て矩形の終端が最も近い包含参照領域の終端と一致するように配置されます。 |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | 属性 Placement: Inline - 包含 BLSE 内でインライン進行方向に詰め込まれます。 |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | 属性 Placement: Start - 要素の割り当て矩形の開始端が最も近い包含参照領域の開始端と一致するように配置されます。 |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | 属性 Role: cb - チェックボックス。 |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | 属性 Role: pb - プッシュボタン。 |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | 属性 Role: rb - ラジオボタン。 |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | 属性 Role: tv - テキスト値フィールド。 |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | 属性 RubyAlign: Center - コンテンツはインライン進行方向で中央に配置されます。 |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | 属性 RubyAlign: Distribute - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。ただし、テキストの開始端と終了端にもスペースが挿入されます。間隔は 1:2:1（開始:中間:終了）の比率で配分されます。ルビがテキスト行の先頭にある場合は 0:1:1 の比率に、行末にある場合は 1:1:0 の比率に変更されます。 |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | 属性 RubyAlign: End - コンテンツはインライン進行方向の終端に揃えられます。 |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | 属性 RubyAlign: Justify - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。 |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | 属性 RubyAlign: Start - コンテンツはインライン進行方向の開始端に揃えられます。 |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | 属性 RubyPosition: After - RT コンテンツは要素の後端に沿って配置されます。 |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | 属性 RubyPosition: Before - RT コンテンツは要素の前端に沿って配置されます。 |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | 属性 RubyPosition: Inline - RT と関連する RP 要素は RB 要素の後に、括弧コメントとしてフォーマットされます。 |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | 属性 RubyPosition: Warichu - RT と関連する RP 要素は RB 要素の後に、割注としてフォーマットされます。 |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | 属性 Scope: Both。 |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | 属性スコープ: 列。 |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | 属性スコープ: 行。 |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | 属性 TextAlign: Center - 開始端と終了端の間で中央揃え。 |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | 属性 TextAlign: End - 終端に揃えられます。 |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | 属性 TextAlign: Justify - 開始端と終了端の両方に揃えられ、必要に応じて各行の内部間隔が拡張されてこの揃えが実現されます。最後の行（または唯一の行）は開始端のみに揃えられます。 |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | 属性 TextAlign: Start - 開始端に揃えられます。 |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | 属性 TextDecorationType: LineThrough - テキストの中央に横線が引かれます。 |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | 属性 TextDecorationType: None - テキスト装飾はありません。 |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | 属性 TextDecorationType: Overline - テキストの上に線が引かれます。 |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | 属性 TextDecorationType: Underline - テキストの下に線が引かれます。 |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | 属性 Width: Auto - 要素の幅はコンテンツの固有幅によって決定されます。 |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | 属性 WritingMode: LrTb - インラインの進行は左から右へ、ブロックの進行は上から下へです。これは西洋の表記体系で一般的な書字方向です。 |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | 属性 WritingMode: RlTb - インラインの進行は右から左へ、ブロックの進行は上から下へです。これはアラビア語とヘブライ語の表記体系で一般的な書字方向です。 |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | 属性 WritingMode: TbRl - インラインの進行は上から下へ、ブロックの進行は右から左へです。これは中国語と日本語の表記体系で一般的な書字方向です。 |

### 関連項目

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


