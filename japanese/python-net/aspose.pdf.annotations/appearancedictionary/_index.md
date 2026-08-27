---
title: "AppearanceDictionary"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です。"
type: docs
weight: 60
url: /ja/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です。

AppearanceDictionary 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_fixed_size | 辞書が固定サイズかどうかを示す値を取得します。 |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state 値、<br/>            ここで N は通常の外観、R はロールオーバー外観、D はダウン外観、state は状態の名前です<br/>            （例：チェックボックスの On、Off）。 |
| values | 辞書の値のリストを取得します。 <br/>            結果コレクションには XForm オブジェクトのリストが含まれます。 |
| is_synchronized | 辞書へのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。 |
| sync_root | 辞書へのアクセスを同期化するために使用できるオブジェクトを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| add(key, value) | 指定されたキーと値で要素を追加します。 |
| add(key, value) | 指定されたキーに対して X フォームを追加します。 |
| copy_to(array, index) | 辞書の要素を配列にコピーし、特定の配列インデックスから開始します。 |
| contains_key(key) | この辞書が指定されたキーを含むかどうかを判断します。 |
| remove(key) | 辞書からキーを削除します。 |
| try_get_value(key, value) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

