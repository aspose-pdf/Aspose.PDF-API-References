---
title: "権限"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "この列挙型はPDFのユーザー権限を表します。"
type: docs
weight: 6560
url: /ja/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

この列挙型はPDFのユーザー権限を表します。

## Members
| メンバー名 | 説明 |
| :- | :- |
| PRINT_DOCUMENT | (リビジョン 2 のセキュリティハンドラ) 文書を印刷します。<br/>            (リビジョン 3 以上のセキュリティハンドラ) 文書を印刷します <br/>            (最高品質レベルでない可能性があります、<br/>            [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) が設定されているかどうかに依存します)。 |
| MODIFY_CONTENT | 文書の内容を、<br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) によって制御される操作以外の操作で変更し、<br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/) と 11。 |
| EXTRACT_CONTENT | (リビジョン 2 のセキュリティハンドラ) 文書からテキストとグラフィックをコピーまたはその他の方法で抽出し、テキストとグラフィックの抽出を含みます（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。<br/>            (リビジョン 3 以上のセキュリティハンドラ) 文書からテキストとグラフィックを、[EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/) によって制御される操作以外の操作でコピーまたは抽出します。 |
| MODIFY_TEXT_ANNOTATIONS | テキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、<br/>            さらに、[MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) が設定されている場合は、インタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| FILL_FORM | (リビジョン 3 以上のセキュリティハンドラ) 既存の<br/>            インタラクティブなフォームフィールド（署名フィールドを含む）に入力します、たとえ<br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) が無効でも。 |
| EXTRACT_CONTENT_WITH_DISABILITIES | (リビジョン 3 以上のセキュリティハンドラ) テキストと<br/>            グラフィックを抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。 |
| ASSEMBLE_DOCUMENT | (リビジョン 3 以上のセキュリティハンドラ) 文書を組み立てます<br/>            （ページの挿入、回転、削除やブックマークやサムネイル画像の作成）、たとえ<br/>            [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) が無効でも。 |
| PRINTING_QUALITY | (リビジョン 3 以上のセキュリティハンドラ) 文書を<br/>            PDF コンテンツの忠実なデジタルコピーを生成できる表現に印刷します。 このビットがオフ（かつビット 3 がオン）の場合、<br/>            印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

