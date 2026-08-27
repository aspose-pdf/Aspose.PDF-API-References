---
title: "ImageDeleteAction"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合。"
type: docs
weight: 6450
url: /ja/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合。

## Members
| メンバー名 | 説明 |
| :- | :- |
| KEEP_CONTENTS | 画像はコレクションから削除されます。ページの内容に画像への参照が含まれている場合、それらは削除されません。ドキュメントが無効になる可能性があります。 |
| NONE | 画像はコレクションとページ内容から削除されますが、画像オブジェクトは削除されません。ファイルサイズは減少しません。 |
| FORCE_DELETE | 画像はコレクションから削除され、画像オブジェクトはドキュメントから削除されます。同じオブジェクトへの他の参照が存在する場合、ドキュメントが破損する可能性があります。 |
| CHECK | 画像はコレクションから削除され、他のページからの画像への参照がない場合にのみ画像オブジェクトが削除されます。ForceDelete オプションと比較して、これにはより多くの時間がかかる場合があります。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

