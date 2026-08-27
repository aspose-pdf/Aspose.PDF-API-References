---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "リソースのカスタムロードの結果"
type: docs
weight: 2820
url: /ja/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

リソースのカスタムロードの結果

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | ロード結果のインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getData](#getData--) | カスタムローダーでロードされたバイナリデータ - ロード後に設定する必要があります。 |
| [getEncodingIfKnown](#getEncodingIfKnown--) | リソースのエンコーディングがロード後またはロード中に判明することがあります。そのような場合、カスタムコードはこのパラメータを介してコンバータにその情報を提供できます。エンコーディングが不明または重要でない場合は、このパラメータに null を設定したままにできます。 |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | 場合によっては、何らかの理由で要求されたリソースの読み込みが不可能になることがあります。リソースが利用できなくても、変換がクラッシュすることはほとんどなく、結果のドキュメントは（ただし品質がやや低下し、画像などが欠ける場合がありますが）作成できます。読み込み中に例外が発生した場合は、単にキャッチしてこのパラメーターに入れてください—この情報が結果のレンダリングのためにコンバータで役立つことがあります。 |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | ロードされたリソースの MIME タイプに関する情報は、コンバータにとって役立つことがあります。このパラメーターで MIME タイプ（ロード後に判明した場合）を指定できます。MIME タイプが不明、または提供する必要がない場合は、パラメーターを null にしてください。 |
| [isLoadingCancelled](#isLoadingCancelled--) | 場合によっては、カスタムコードで読み込みを行わないようにすべきことがあります。その場合はこのフラグを True に設定してください。フラグが設定されると、コンバータは内部のデフォルトリソースローダーを使用して結果を取得しようとします（カスタム戦略が提供されていない状況と同様に動作します）。 |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | リソースのエンコーディングがロード後またはロード中に判明することがあります。そのような場合、カスタムコードはこのパラメータを介してコンバータにその情報を提供できます。エンコーディングが不明または重要でない場合は、このパラメータに null を設定したままにできます。 |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | 場合によっては、何らかの理由で要求されたリソースの読み込みが不可能になることがあります。 |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | 場合によっては、カスタムコードで読み込みを行わないようにすべきことがあります。その場合はこのフラグを True に設定してください。フラグが設定されると、コンバータは内部のデフォルトリソースローダーを使用して結果を取得しようとします（カスタム戦略が提供されていない状況と同様に動作します）。 |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | ロードされたリソースの MIME タイプに関する情報は、コンバータにとって有用です。このパラメーターで MIME タイプ（ロード後に判明した場合）を指定できます。MIME タイプが不明、または提供する必要がない場合は、パラメーターを null にしてください。 |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

ロード結果のインスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ |  | カスタムロードの結果は常に提供する必要があります。結果が取得できない場合は、長さゼロの配列でも構いません。 |

### getData {#getData--}
```
public byte[] getData()
```

カスタムローダーでロードされたバイナリデータ - ロード後に設定する必要があります。

**Returns:**
バイト値の配列

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

リソースのエンコーディングがロード後またはロード中に判明することがあります。そのような場合、カスタムコードはこのパラメータを介してコンバータにその情報を提供できます。エンコーディングが不明または重要でない場合は、このパラメータに null を設定したままにできます。

**Returns:**
Charset インスタンス

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

場合によっては、何らかの理由で要求されたリソースの読み込みが不可能になることがあります。リソースが利用できなくても、変換がクラッシュすることはほとんどなく、結果のドキュメントは（ただし品質がやや低下し、画像などが欠ける場合がありますが）作成できます。読み込み中に例外が発生した場合は、単にキャッチしてこのパラメーターに入れてください—この情報が結果のレンダリングのためにコンバータで役立つことがあります。

**Returns:**
例外

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

ロードされたリソースの MIME タイプに関する情報は、コンバータにとって役立つことがあります。このパラメーターで MIME タイプ（ロード後に判明した場合）を指定できます。MIME タイプが不明、または提供する必要がない場合は、パラメーターを null にしてください。

**Returns:**
文字列値

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

場合によっては、カスタムコードで読み込みを行わないようにすべきことがあります。その場合はこのフラグを True に設定してください。フラグが設定されると、コンバータは内部のデフォルトリソースローダーを使用して結果を取得しようとします（カスタム戦略が提供されていない状況と同様に動作します）。

**Returns:**
ブール値

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
リソースのエンコーディングがロード後またはロード中に判明することがあります。そのような場合、カスタムコードはこのパラメータを介してコンバータにその情報を提供できます。エンコーディングが不明または重要でない場合は、このパラメータに null を設定したままにできます。

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
場合によっては、何らかの理由で要求されたリソースの読み込みが不可能になることがあります。

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

場合によっては、カスタムコードで読み込みを行わないようにすべきことがあります。その場合はこのフラグを True に設定してください。フラグが設定されると、コンバータは内部のデフォルトリソースローダーを使用して結果を取得しようとします（カスタム戦略が提供されていない状況と同様に動作します）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| loadingCancelled |  | ブール値 |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
ロードされたリソースの MIME タイプに関する情報は、コンバータにとって有用です。このパラメーターで MIME タイプ（ロード後に判明した場合）を指定できます。MIME タイプが不明、または提供する必要がない場合は、パラメーターを null にしてください。
