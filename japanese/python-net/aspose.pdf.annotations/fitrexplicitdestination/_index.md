---
title: "FitRExplicitDestination"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページを表示し、内容を left、bottom、right、top の座標で指定された矩形がウィンドウ内に水平・垂直の両方向で完全に収まるように拡大する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合、両者のうち小さい方を使用し、もう一方の次元では矩形をウィンドウ内で中央に配置します。いずれかのパラメータに null 値を指定すると、予測できない動作になる可能性があります。"
type: docs
weight: 230
url: /ja/python-net/aspose.pdf.annotations/fitrexplicitdestination/
---

## FitRExplicitDestination class

ページを表示し、内容を left、bottom、right、top の座標で指定された矩形がウィンドウ内に水平・垂直の両方向で完全に収まるように拡大する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合、両者のうち小さい方を使用し、もう一方の次元では矩形をウィンドウ内で中央に配置します。いずれかのパラメータに null 値を指定すると、予測できない動作になる可能性があります。

FitRExplicitDestination 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FitRExplicitDestination(page, left, bottom, right, top) | FitRExplicitDestination クラスの新しいインスタンスを初期化します |
| FitRExplicitDestination(document, page_number, left, bottom, right, top) | FitRExplicitDestination クラスの新しいインスタンスを初期化します |
| FitRExplicitDestination(page_number, left, bottom, right, top) | FitRExplicitDestination クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| page | 目的地ページオブジェクトを取得します |
| page_number | 目的地ページ番号を取得します |
| left | 表示矩形の左水平座標を取得します。 |
| bottom | 表示矩形の下垂直座標を取得します。 |
| 右 | 表示矩形の右水平座標を取得します。 |
| 上 | 表示矩形の上垂直座標を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| create_destination(page, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| create_destination(doc, page_number, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| create_destination(page_number, type, values) | ExplicitDestination の派生クラスのインスタンスを作成します。 |
| to_string() | オブジェクトの状態を文字列値に変換します。例: "1 FitR 100 200 300 400"。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

