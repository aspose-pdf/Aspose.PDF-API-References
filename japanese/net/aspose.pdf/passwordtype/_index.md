---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PasswordType 列挙型。この列挙型は、パスワード保護された PDF ドキュメントに使用される既知のパスワードタイプを表します。
type: docs
weight: 8290
url: /ja/net/aspose.pdf/passwordtype/
---
## PasswordType 列挙型

この列挙型は、パスワード保護された PDF ドキュメントに使用される既知のパスワードタイプを表します。

```csharp
public enum PasswordType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | PDF ドキュメントはパスワード保護されていません。 |
| User | `1` | PDF ドキュメントはドキュメントオープンパスワード（アクセス制限）を使用して開かれました。 |
| Owner | `2` | PDF ドキュメントは変更権限パスワード（フルアクセス）を使用して開かれました。 |
| Inaccessible | `3` | PDF ドキュメントはパスワード保護されていますが、ユーザーパスワードとオーナーパスワードの両方が空でなく、いずれのパスワードも定義されていないか、提供されたパスワードが不正確です。そのため、パスワードのタイプを推測することは不可能です。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)