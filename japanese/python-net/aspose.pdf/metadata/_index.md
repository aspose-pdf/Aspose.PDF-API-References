---
title: "Metadata"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "XMP メタデータストリームへのアクセスを提供します。"
type: docs
weight: 930
url: /ja/python-net/aspose.pdf/metadata/
---

## Metadata class

XMP メタデータストリームへのアクセスを提供します。

Metadata 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_fixed_size | コレクションが固定サイズかどうかを確認します。 |
| keys | メタデータキーのコレクションを取得します。 |
| values | メタデータ内の値を取得します。 |
| is_synchronized | コレクションが同期化されているかどうかを確認します。 |
| sync_root | コレクションの同期オブジェクトを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | 名前空間 URI を登録します。 |
| register_namespace_uri(prefix, namespace_uri, schema_description) | 名前空間 URI を登録します。 |
| add(key, value) | メタデータに値を追加します。 |
| add(key, value) | メタデータに値を追加します。 |
| add(prefix, value) | メタデータに pdf 拡張子を追加します。 |
| get_namespace_uri_by_prefix(prefix) | プレフィックスから namespace URI を返します。 |
| get_prefix_by_namespace_uri(namespace_uri) | namespace URI からプレフィックスを返します。 |
| contains(key) | キーがメタデータに含まれているかチェックします。 |
| remove(key) | メタデータからエントリを削除します。 |
| contains_key(key) | この辞書が指定されたキーを含むかどうかを判断します。 |
| try_get_value(key, value) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

