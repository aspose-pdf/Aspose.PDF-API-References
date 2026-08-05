---
title: "AttributeName"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "属性名値のクラスを表します。"
type: docs
weight: 50
url: /ja/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

属性名値のクラスを表します。

AttributeName 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| name | 属性の名前値を取得します。 |
| attribute_key | 属性キーを取得します。 |
| PLACEMENT_BLOCK | 属性配置: Block - 包含参照領域または親 BLSE 内でブロック進行方向に積み重ねられます。 |
| PLACEMENT_INLINE | 属性配置: Inline - 包含 BLSE 内でインライン進行方向に詰め込まれます。 |
| PLACEMENT_BEFORE | 属性配置: Before - 要素の割り当て矩形の前端が最も近い包含参照領域の前端と一致するように配置されます。 |
| PLACEMENT_START | 属性 Placement: Start - 要素の割り当て矩形の開始端が、最も近い包含参照領域の開始端と一致するように配置されます。 |
| PLACEMENT_END | 属性 Placement: End - 要素の割り当て矩形の終了端が、最も近い包含参照領域の終了端と一致するように配置されます。 |
| WRITING_MODE_LR_TB | 属性 WritingMode: LrTb - インラインの進行は左から右へ、ブロックの進行は上から下へです。これは西洋の表記システムで一般的な書字方向です。 |
| WRITING_MODE_RL_TB | 属性 WritingMode: RlTb - インラインの進行は右から左へ、ブロックの進行は上から下へです。これはアラビア語とヘブライ語の表記システムで一般的な書字方向です。 |
| WRITING_MODE_TB_RL | 属性 WritingMode: TbRl - インラインの進行は上から下へ、ブロックの進行は右から左へです。これは中国語と日本語の表記システムで一般的な書字方向です。 |
| BORDER_STYLE_NONE | 属性 BorderStyle: None - 境界線がありません。BorderThickness の計算値を 0 に強制します。 |
| BORDER_STYLE_HIDDEN | 属性 BorderStyle: Hidden - None と同様ですが、テーブル要素の境界線競合解決に関しては異なります。 |
| BORDER_STYLE_DOTTED | 属性 BorderStyle: Dotted - 境界線は点の連続です。 |
| BORDER_STYLE_DASHED | 属性 BorderStyle: Dashed - 境界線は短い線分の連続です。 |
| BORDER_STYLE_SOLID | 属性 BorderStyle: Solid - 境界線は単一の線分です。 |
| BORDER_STYLE_DOUBLE | 属性 BorderStyle: Double - 境界線は2本の実線です。2本の線とその間のスペースの合計が BorderThickness の値と等しくなります。 |
| BORDER_STYLE_GROOVE | 属性 BorderStyle: Groove - 境界線はキャンバスに彫り込まれたように見えます。 |
| BORDER_STYLE_RIDGE | 属性 BorderStyle: Ridge - 境界線はキャンバスから浮き上がっているように見えます（Groove の反対）。 |
| BORDER_STYLE_INSET | 属性 BorderStyle: Inset - 境界線は全体のボックスがキャンバスに埋め込まれたように見せます。 |
| BORDER_STYLE_OUTSET | 属性 BorderStyle: Outset - ボーダーは、全体のボックスがキャンバスから突き出ているように見せます（Inset の反対）。 |
| TEXT_ALIGN_START | 属性 TextAlign: Start - 開始エッジに揃えられます。 |
| TEXT_ALIGN_CENTER | 属性 TextAlign: Center - 開始エッジと終了エッジの間で中央に配置されます。 |
| TEXT_ALIGN_END | 属性 TextAlign: End - 終了エッジに揃えられます。 |
| TEXT_ALIGN_JUSTIFY | 属性 TextAlign: Justify - 両方の開始エッジと終了エッジに揃えられ、必要に応じて各行の内部間隔が拡張されてその整列が実現されます。最後（または唯一）の行は開始エッジのみに揃えられます。 |
| WIDTH_AUTO | 属性 Width: Auto - 要素の幅はコンテンツの固有幅によって決定されます。 |
| HEIGHT_AUTO | 属性 Height: Auto - 要素の高さはコンテンツの固有高さによって決定されます。 |
| BLOCK_ALIGN_BEFORE | 属性 BlockAlign: Before - 最初の子要素の割り当て矩形の前端がテーブルセルのコンテンツ矩形の前端と揃えられます。 |
| BLOCK_ALIGN_MIDDLE | 属性 BlockAlign: Middle- 子要素はテーブルセル内で中央に配置されます。最初の子要素の割り当て矩形の前端とテーブルセルのコンテンツ矩形の前端との距離は、最後の子要素の割り当て矩形の後端とテーブルセルのコンテンツ矩形の後端との距離と同じになります。 |
| BLOCK_ALIGN_AFTER | 属性 BlockAlign: After - 最後の子要素の割り当て矩形の後端がテーブルセルのコンテンツ矩形の後端と揃えられます。 |
| BLOCK_ALIGN_JUSTIFY | 属性 BlockAlign: Justify - 子要素はテーブルセルのコンテンツ矩形の前端と後端の両方に揃えられます。最初の子要素は「Before」で説明されたように配置され、最後の子要素は「After」で説明されたように配置され、子要素間は等間隔になります。子要素が1つだけの場合は、Before と同様に前端のみに揃えられます。 |
| INLINE_ALIGN_START | 属性 InlineAlign: Start - 各子要素の割り当て矩形の開始端がテーブルセルのコンテンツ矩形の開始端と揃えられます。 |
| INLINE_ALIGN_CENTER | 属性 InlineAlign: Center - 各子要素はテーブルセル内で中央に配置されます。子要素の割り当て矩形の開始エッジとテーブルセルのコンテンツ矩形の開始エッジとの距離は、終了エッジ間の距離と同じでなければなりません。 |
| INLINE_ALIGN_END | 属性 InlineAlign: End - 各子要素の割り当て矩形の終了エッジがテーブルセルのコンテンツ矩形の終了エッジと揃えられます。 |
| LINE_HEIGHT_NORMAL | 属性 LineHeight: Normal - BaselineShift に指定された非ゼロ値を含めるように行の高さを調整します。 |
| LINE_HEIGHT_AUTO | 属性 LineHeight: Auto - BaselineShift の値に対する調整は行われません。 |
| TEXT_DECORATION_TYPE_NONE | 属性 TextDecorationType: None - テキスト装飾はありません。 |
| TEXT_DECORATION_TYPE_UNDERLINE | 属性 TextDecorationType: Underline - テキストの下に線が引かれます。 |
| TEXT_DECORATION_TYPE_OVERLINE | 属性 TextDecorationType: Overline - テキストの上に線が引かれます。 |
| TEXT_DECORATION_TYPE_LINE_THROUGH | 属性 TextDecorationType: LineThrough - テキストの中央に線が引かれます。 |
| RUBY_ALIGN_START | 属性 RubyAlign: Start - コンテンツはインライン進行方向の開始エッジに揃えられます。 |
| RUBY_ALIGN_CENTER | 属性 RubyAlign: Center - コンテンツはインライン進行方向で中央に配置されます。 |
| RUBY_ALIGN_END | 属性 RubyAlign: End - コンテンツはインライン進行方向の終了エッジに揃えられます。 |
| RUBY_ALIGN_JUSTIFY | 属性 RubyAlign: Justify - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。 |
| RUBY_ALIGN_DISTRIBUTE | 属性 RubyAlign: Distribute - コンテンツはインライン進行方向の利用可能な幅を埋めるように拡張されます。ただし、テキストの開始エッジと終了エッジにもスペースが挿入されます。間隔は 1:2:1（開始:中間:終了）の比率で配分されます。ルビがテキスト行の開始にある場合は 0:1:1 の比率に、終了にある場合は 1:1:0 の比率に変更されます。 |
| RUBY_POSITION_BEFORE | 属性 RubyPosition: Before - RT コンテンツは要素の前端に沿って配置されます。 |
| RUBY_POSITION_AFTER | 属性 RubyPosition: After - RT コンテンツは要素の後端に沿って配置されます。 |
| RUBY_POSITION_WARICHU | 属性 RubyPosition: Warichu - RT と関連する RP 要素は RB 要素に続いて、割注としてフォーマットされます。 |
| RUBY_POSITION_INLINE | 属性 RubyPosition: Inline - RT と関連する RP 要素は RB 要素に続いて、丸括弧コメントとしてフォーマットされます。 |
| GLYPH_ORIENTATION_VERTICAL_AUTO | 属性 GlyphOrientationVertical: Auto - テキストが全角（幅と高さが同じ）かどうかに応じて、デフォルトの向きを指定します。 |
| LIST_NUMBERING_NONE | 属性 ListNumbering: None - 自動番号付けは行われません。Lbl 要素（存在する場合）は任意のテキストを含み、番号付けスキームの対象ではありません。 |
| LIST_NUMBERING_DISC | 属性 ListNumbering: Disc - 塗りつぶしの円形箇条書き記号。 |
| LIST_NUMBERING_CIRCLE | 属性 ListNumbering: Circle - 開いた円形箇条書き記号。 |
| LIST_NUMBERING_SQUARE | 属性 ListNumbering: Square - 塗りつぶしの四角形箇条書き記号。 |
| LIST_NUMBERING_DECIMAL | 属性 ListNumbering: Decimal - 10 進アラビア数字 (1-9、10-99、…)。 |
| LIST_NUMBERING_UPPER_ROMAN | 属性 ListNumbering: UpperRoman - 大文字ローマ数字 (I, II, III, IV, …)。 |
| LIST_NUMBERING_LOWER_ROMAN | 属性 ListNumbering: LowerRoman - 小文字ローマ数字 (i, ii, iii, iv, …)。 |
| LIST_NUMBERING_UPPER_ALPHA | 属性 ListNumbering: UpperAlpha - 大文字 (A, B, C, ...)。 |
| LIST_NUMBERING_LOWER_ALPHA | 属性 ListNumbering: LowerAlpha - 小文字 (a, b, c, ...)。 |
| ROLE_RB | 属性 Role: rb - ラジオボタン。 |
| ROLE_CB | 属性 Role: cb - チェックボックス。 |
| ROLE_PB | 属性 Role: pb - プッシュボタン。 |
| ROLE_TV | 属性 Role: tv - テキスト値フィールド。 |
| CHECKED_ON | 属性 checked: On - ラジオボタンまたはチェックボックスフィールドの状態。 |
| CHECKED_OFF | 属性 checked: Off - ラジオボタンまたはチェックボックスフィールドの状態。 |
| CHECKED_NEUTRAL | 属性 checked: Neutral - ラジオボタンまたはチェックボックスフィールドの状態。 |
| SCOPE_ROW | 属性 Scope: Row. |
| SCOPE_COLUMN | 属性 Scope: Column. |
| SCOPE_BOTH | 属性 Scope: Both. |
## メソッド
| 名前 | 説明 |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | 属性キーに対する属性名を取得します。 |

### 関連項目

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

