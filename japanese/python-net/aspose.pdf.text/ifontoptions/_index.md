---
title: "IFontOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フォントの動作を調整するための便利なプロパティ"
type: docs
weight: 180
url: /ja/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

フォントの動作を調整するための便利なプロパティ

IFontOptions 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| notify_about_font_embedding_error | 時々、目的のフォントをドキュメントに埋め込むことができません。さまざまな理由があり、例えば<br/>            ライセンス制限や、目的のフォントが宛先コンピュータに見つからない場合があります。<br/>            このような状況になると、目的のフォントはプロパティ フラグ Font.IsEmbedded = true; を設定して埋め込まれるため、検出が簡単ではありません。もちろん、設定直後にこのプロパティを読み取ることは可能ですが、<br/>            便利なアプローチとは言えません。フラグ NotifyAboutFontEmbeddingError は、フォント埋め込みが失敗した場合の例外メカニズムを強制します。<br/>            このフラグが設定されていると、タイプが [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) の例外がスローされます。デフォルトは false です。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

