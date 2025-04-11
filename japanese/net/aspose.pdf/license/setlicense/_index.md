---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: ライセンスメソッド。コンポーネントにライセンスを付与します
type: docs
weight: 20
url: /ja/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licenseName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | String | フルファイル名または短いファイル名、または埋め込まれたリソースの名前である可能性があります。空の文字列を使用すると評価モードに切り替わります。 |

## 備考

次の場所でライセンスを探します:

1. 明示的なパス。

2. Asposeコンポーネントアセンブリを含むフォルダー。

3. クライアントの呼び出しアセンブリを含むフォルダー。

4. エントリ（スタートアップ）アセンブリを含むフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**注意:** .NET Compact Frameworkでは、次の場所でのみライセンスを探します:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

[Java]

2. AsposeコンポーネントJARファイルを含むフォルダー。

3. クライアントの呼び出しJARファイルを含むフォルダー。

### 関連項目

* クラス [License](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream stream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | ライセンスを含むストリーム。 |

## 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 関連項目

* クラス [License](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)