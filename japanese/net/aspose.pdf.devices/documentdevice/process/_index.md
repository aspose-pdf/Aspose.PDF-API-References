---
title: "DocumentDevice.Process"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "DocumentDevice メソッド。各デバイスはドキュメント上の操作を表し、例えば PDF ドキュメントを別の形式に変換できます"
type: docs
weight: 10
url: /ja/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

各デバイスはドキュメント上のある操作を表します。たとえば、pdf ドキュメントを別の形式に変換できます。

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | 処理対象のドキュメントです。 |
| fromPage | Int32 | 処理を開始するページを定義します。 |
| toPage | Int32 | 処理する最後のページを定義します。 |
| output | Stream | 処理結果が保存されるストリームを定義します。 |

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | 処理対象のドキュメントです。 |
| output | Stream | 処理結果が保存されるストリームを定義します。 |

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | 処理対象のドキュメントです。 |
| outputFileName | String | 処理結果が保存されるファイルを定義します。 |

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | 処理対象のドキュメントです。 |
| fromPage | Int32 | 処理を開始する最初のページです。 |
| toPage | Int32 | 処理の最後のページです。 |
| outputFileName | String | 処理結果が保存されるファイルを定義します。 |

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


