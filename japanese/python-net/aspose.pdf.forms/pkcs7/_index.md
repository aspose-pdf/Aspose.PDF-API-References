---
title: "PKCS7"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "インターネット RFC 2315 の PKCS#7 仕様に準拠した PKCS#7 オブジェクトを表します。<br/>            PKCS #7: 暗号メッセージ構文、バージョン 1.5。<br/>            文書のバイト範囲の SHA1 ダイジェストが PKCS#7 SignedData フィールドにカプセル化されます。"
type: docs
weight: 190
url: /ja/python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

インターネット RFC 2315 の PKCS#7 仕様に準拠した PKCS#7 オブジェクトを表します。<br/>            PKCS #7: 暗号メッセージ構文、バージョン 1.5。<br/>            文書のバイト範囲の SHA1 ダイジェストが PKCS#7 SignedData フィールドにカプセル化されます。

PKCS7 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PKCS7() | [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) クラスの新しいインスタンスを初期化します。 |
| PKCS7(pfx, password) | PKCS7 クラスの新しいインスタンスを初期化します |
| PKCS7(pfx, password) | PKCS7 クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| custom_appearance | カスタム外観を取得/設定します。 |
| authority | 文書に署名する人物または権限者の名前。 |
| date | 署名時刻。 |
| location | 署名の CPU ホスト名または物理的な場所。 |
| reason | 署名の理由、例として (I agreeРІР‚В¦) など。 |
| contact_info | 署名者が受取人が署名者に連絡できるように提供する情報 <br/>            署名の検証のため、例：電話番号。 |
| byte_range | 整数のペア（開始バイトオフセット、バイト単位の長さ）の配列 <br/>             で、ダイジェスト計算の正確なバイト範囲を記述します。 |
| timestamp_settings | タイムスタンプ設定を取得/設定します。 |
| ocsp_settings | OCSP 設定を取得/設定します。 |
| use_ltv | ltv 検証フラグを取得/設定します。 |
| show_properties | 署名プロパティの表示/非表示を強制します。<br/>            ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（表す文字列）を持ちます：<br/>            -------------------------------------------<br/>            デジタル署名者: {certificate subject}<br/>            日付: {signature.Date}<br/>            理由: {signature.Reason}<br/>            場所: {signature.Location}<br/>            -------------------------------------------<br/>            {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像の上に配置されます。<br/>            ShowProperties のデフォルトは true です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| verify() | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true を返します。<br/>            それ以外の場合は false を返します。 |

### 関連項目

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

