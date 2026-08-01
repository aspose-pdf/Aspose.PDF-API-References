---
title: "クラス LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LoadOptionsResourceLoadingResult クラス。リソースのカスタム読み込み結果"
type: docs
weight: 6290
url: /ja/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

リソースのカスタム読み込み結果

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
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | カスタムローダーで読み込まれたバイナリ データ - 読み込み後に設定する必要があります |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | リソースのエンコーディングが読み込み後または読み込み中に判明することがあります。その場合、カスタムコードはこのパラメーターを通じてコンバータにその情報を提供できます。エンコーディングが不明または重要でない場合は、このパラメーターに null を設定したままにできます。 |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 場合によっては、何らかの理由で要求されたリソースを読み込めないことがあります。リソースが利用できないことは、変換処理のクラッシュにつながることは少なく、結果のドキュメントは（画像なしなど、若干品質が低下する可能性はありますが）作成できます。読み込み中に例外が発生した場合は、その例外をキャッチしてこのパラメーターに設定してください。時々、その情報は結果のレンダリングのためにコンバータにとって有用です。 |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 場合によっては、カスタムコードで読み込みを行わない方がよいことがあります。その場合は、このフラグを True に設定してください。フラグが True の場合、コンバータは内部のデフォルトリソースローダーを使用して結果を取得しようとします（カスタム戦略が提供されていない状況と同様に動作します）。 |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 読み込まれたリソースの MIME タイプに関する情報はコンバータにとって有用なことがあります。このパラメーターで MIME タイプ（読み込み後に判明した場合）を指定できます。MIME タイプが不明、または提供する必要がない場合は、パラメーターを null のままにしてください。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


