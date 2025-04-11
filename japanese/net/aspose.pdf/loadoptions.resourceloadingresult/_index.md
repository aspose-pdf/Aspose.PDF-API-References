---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult クラス。リソースのカスタム読み込みの結果
type: docs
weight: 6150
url: /ja/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult クラス

リソースのカスタム読み込みの結果

```csharp
public class ResourceLoadingResult
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | 読み込み結果のインスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | カスタムローダーで読み込まれたバイナリデータ - 読み込み後に設定する必要があります |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | 時々、リソースのエンコーディングは読み込み後または読み込み中に知られています。その場合、カスタムコードはこのパラメータを介してその知識をコンバータに提供できます。エンコーディングが不明または重要でない場合は、このパラメータを null にしておくことができます。 |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 時々、何らかの理由で要求されたリソースを読み込むことが不可能です。リソースの利用不可は、変換のクラッシュを引き起こさないことが多く、結果のドキュメントは作成される可能性があります（ただし、画像なしなど、少し質が悪くなるかもしれません）。読み込み中に例外が発生した場合は、それをキャッチしてこのパラメータに入れてください - 時々、その情報は結果のレンダリングのためにコンバータにとって有用です。 |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 時々、何らかの理由でカスタムコードによる読み込みが発生しないべきです。その場合、このフラグを True に設定してください。その場合、コンバータは内部のデフォルトリソースローダーを使用してその結果を取得しようとします（カスタム戦略が提供されていない場合の動作です）。 |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 時々、読み込まれたリソースの MIME タイプに関する知識はコンバータにとって有用です。このパラメータに MIME タイプ（読み込み後に知られている場合）を提供できます。MIME タイプが不明または提供する必要がない場合は、このパラメータを null にしておいてください。 |

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)