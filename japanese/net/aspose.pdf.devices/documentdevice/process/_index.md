---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice メソッド。各デバイスはドキュメントに対する操作を表します。例えば、PDF ドキュメントを別の形式に変換できます。
type: docs
weight: 10
url: /ja/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

各デバイスはドキュメントに対する操作を表します。例えば、PDF ドキュメントを別の形式に変換できます。

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | 処理するドキュメント。 |
| fromPage | Int32 | 処理を開始するページを定義します。 |
| toPage | Int32 | 処理する最後のページを定義します。 |
| output | Stream | 処理の結果が保存されるストリームを定義します。 |

### 参照

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

ドキュメント全体を処理し、結果をストリームに保存します。

```csharp
public void Process(Document document, Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | 処理するドキュメント。 |
| output | Stream | 処理の結果が保存されるストリームを定義します。 |

### 参照

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

ドキュメント全体を処理し、結果をファイルに保存します。

```csharp
public void Process(Document document, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | 処理するドキュメント。 |
| outputFileName | String | 処理の結果が保存されるファイルを定義します。 |

### 参照

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

ドキュメントの特定のページを処理し、結果をファイルに保存します。

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | 処理するドキュメント。 |
| fromPage | Int32 | 処理を開始する最初のページ。 |
| toPage | Int32 | 処理の最後のページ。 |
| outputFileName | String | 処理の結果が保存されるファイルを定義します。 |

### 参照

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)