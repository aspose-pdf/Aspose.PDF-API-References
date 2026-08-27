---
title: "License.SetLicense"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "License メソッド。コンポーネントにライセンスを設定します"
type: docs
weight: 40
url: /ja/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licenseName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| licenseName | String | 完全なファイル名または短いファイル名、または埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。 |

## 備考

次の場所でライセンスを検索します：

1. 明示的なパス。

2. Aspose コンポーネント アセンブリが含まれるフォルダー。

3. クライアントの呼び出しアセンブリが含まれるフォルダー。

4. エントリ（スタートアップ）アセンブリが含まれるフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

[Java]

2. Aspose コンポーネント JAR ファイルが含まれるフォルダー。

3. クライアントの呼び出し JAR ファイルが含まれるフォルダー。

### 関連項目

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream stream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ライセンスを含むストリーム。 |

## 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 関連項目

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


