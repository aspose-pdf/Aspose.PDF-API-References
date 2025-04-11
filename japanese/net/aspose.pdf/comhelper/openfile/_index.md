---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper メソッド。ファイル名を使用してドキュメントを作成して返します。Document と同じです。
type: docs
weight: 20
url: /ja/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

*filename* を使用してドキュメントを作成して返します。[`Document`](../../document/document/) と同じです。

```csharp
public Document OpenFile(string filename)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントファイルの名前。 |

### 戻り値

ドキュメントオブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

暗号化されたドキュメントで作業するための [`Document`](../../document/) クラスの新しいインスタンスを初期化して返します。

```csharp
public Document OpenFile(string filename, string password)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | String | ドキュメントファイル名。 |
| password | String | ユーザーまたはオーナーパスワード。 |

### 戻り値

ドキュメントオブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

暗号化されたドキュメントで作業するための [`Document`](../../document/) クラスの新しいインスタンスを初期化します。

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | String | ドキュメントファイル名。 |
| password | String | ユーザーまたはオーナーパスワード。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。それ以外の場合は閉じられません。 |

### 戻り値

ドキュメントオブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

必要な変換オプションを提供してファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントに変換する入力ファイル。 |
| options | LoadOptions | *filename* を PDF ドキュメントに変換するためのプロパティを表します。 |

### 戻り値

ドキュメントオブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [LoadOptions](../../loadoptions/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)