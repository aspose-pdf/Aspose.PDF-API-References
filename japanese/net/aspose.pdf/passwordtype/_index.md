---
title: "列挙型 PasswordType"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PasswordType 列挙型。この列挙型は、パスワードで保護された pdf documents で使用される既知のパスワードタイプを表します。"
type: docs
weight: 8430
url: /ja/net/aspose.pdf/passwordtype/
---
## PasswordType enumeration

この列挙体は、パスワードで保護された PDF ドキュメントで使用される既知のパスワードタイプを表します。

```csharp
public enum PasswordType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | Pdf document はパスワードで保護されていません。 |
| User | `1` | Pdf document は document open password（制限付きアクセス）で開かれました。 |
| Owner | `2` | Pdf document は change permissions password（フルアクセス）で開かれました。 |
| Inaccessible | `3` | Pdf document はパスワードで保護されていますが、ユーザーとオーナーのパスワードがどちらも空ではなく、パスワードが定義されていないか、提供されたパスワードが正しくありません。そのため、パスワードの種類を推測することはできません。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


