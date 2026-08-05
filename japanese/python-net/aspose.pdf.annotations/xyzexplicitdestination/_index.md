---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ウィンドウの左上隅に (left, top) の座標が配置され、ページの内容がズーム係数で拡大表示されるページを表示する明示的なデスティネーションを表します。left、top、または zoom のいずれかのパラメータに null 値が指定された場合、そのパラメータの現在の値は変更せずに保持されます。ズーム値が 0 の場合は null 値と同義です。"
type: docs
weight: 880
url: /ja/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

ウィンドウの左上隅に (left, top) の座標が配置され、ページの内容がズーム係数で拡大表示されるページを表示する明示的なデスティネーションを表します。left、top、または zoom のいずれかのパラメータに null 値が指定された場合、そのパラメータの現在の値は変更せずに保持されます。ズーム値が 0 の場合は null 値と同義です。

XYZExplicitDestination 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | XYZExplicitDestination クラスの新しいインスタンスを初期化します |
| XYZExplicitDestination(document, page_number, left, top, zoom) | XYZExplicitDestination クラスの新しいインスタンスを初期化します |
| XYZExplicitDestination(page_number, left, top, zoom) | XYZExplicitDestination クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| page | 目的地ページオブジェクトを取得します |
| page_number | 目的地ページ番号を取得します |
| left | ウィンドウの左上隅の左水平座標を取得します。 |
| 上 | ウィンドウの左上隅の上部垂直座標を取得します。 |
| zoom | ズーム係数を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | 必要に応じてページの回転を考慮し、ページの指定位置へのデスティネーションを作成します。 |
| create_destination(page, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| create_destination(doc, page_number, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| create_destination(page_number, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| create_destination_to_upper_left_corner(page, zoom) | 指定されたページの左上隅へのデスティネーションを作成します。 |
| create_destination_to_upper_left_corner(page) | 指定されたページの左上隅へのデスティネーションを作成します。 |
| to_string() | オブジェクトの状態を文字列値に変換します。例: "1 XYZ 100 200 3"。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

