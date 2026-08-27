---
title: "ComHelper.OpenFile"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ComHelper メソッド。ファイル名を使用して Document を作成し返します。Document と同様です。"
type: docs
weight: 20
url: /ja/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

*filename* を使用して Document を作成し返します。[`Document`](../../document/document/) と同様です。

```csharp
public Document OpenFile(string filename)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントファイルの名前。 |

### 戻り値

Document オブジェクト

### 関連項目

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

暗号化されたドキュメントを操作するために、[`Document`](../../document/) クラスの新しいインスタンスを初期化して返します。

```csharp
public Document OpenFile(string filename, string password)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |

### 戻り値

Document オブジェクト

### 関連項目

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

暗号化されたドキュメントを操作するために、[`Document`](../../document/) クラスの新しいインスタンスを初期化します。

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |
| isManagedStream | Boolean | `true` に設定された場合、内部ストリームは終了前に閉じられます。設定されていない場合は閉じられません。 |

### 戻り値

Document オブジェクト

### 関連項目

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

必要な変換オプションを提供して、ファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントに変換する入力ファイル。 |
| オプション | LoadOptions | *filename* を PDF ドキュメントに変換するためのプロパティを表します。 |

### 戻り値

Document オブジェクト

### 関連項目

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


