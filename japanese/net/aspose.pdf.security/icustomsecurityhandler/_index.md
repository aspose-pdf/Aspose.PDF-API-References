---
title: "インターフェイス ICustomSecurityHandler"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Security.ICustomSecurityHandler インターフェイス。カスタムセキュリティハンドラのインターフェイスです。"
type: docs
weight: 10150
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

カスタム セキュリティ ハンドラ インターフェイスです。

```csharp
public interface ICustomSecurityHandler
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | フィルタ名を取得します。 |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | 鍵長を取得します。 |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | ハンドラまたは暗号化アルゴリズムのリビジョンを取得します。 |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | サブフィルタ名を取得します。 |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | ハンドラまたは暗号化アルゴリズムのバージョンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | EncryptionKey を計算します。通常、キーは UserKey に基づいて計算されます。呼び出し時の現在のパラメータを含む EncryptionParams の値を使用できます。この値は [`Encrypt`](./encrypt/) および [`Decrypt`](./decrypt/) の key 引数として渡されます。 |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | データ配列を復号化します。 |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | データ配列を暗号化します。 |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | ドキュメントの権限フィールドを暗号化します。結果は Perms 暗号化辞書フィールドに書き込まれます。ドキュメントを開く際、[`EncryptionParameters`](../encryptionparameters/) の Perms フィールドを介してこの値を取得できます。これにより、ドキュメントの権限が変更されたかどうかを確認できます。 |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | 暗号化辞書の O フィールドに書き込まれるパスワードに基づいてエンコードされた配列を作成します。渡された引数のみを使用すべきです。ユーザーパスワードは所有者パスワードを使用してこのフィールドから計算できます。暗号化中に呼び出され、暗号化辞書を準備および設定します。この値は [`CalculateEncryptionKey`](./calculateencryptionkey/) で利用可能で、UserKey からキーを取得します。ドキュメント暗号化を呼び出す際にユーザーが指定したパスワードが渡されます。パスワードは指定しないか、または1つだけ指定することがあります。 |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | ユーザーのパスワードに基づいてエンコードされた配列を作成します。この値は通常、パスワードがユーザーまたは所有者に属するかを確認し、暗号化キーを取得するために使用されます。暗号化中に呼び出され、暗号化辞書を準備および設定します。ドキュメント暗号化を呼び出す際に、ユーザー指定のパスワードが引数として渡されます。 |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | 暗号化のために現在のインスタンスを初期化するために呼び出されます。暗号化時には、転送されたプロパティ `ICustomSecurityHandler` のデータで埋められ、暗号化辞書からドキュメントを開く際にも同様です。新しい暗号化中にこのメソッドが呼び出された場合、[`UserKey`](../encryptionparameters/userkey/) および [`OwnerKey`](../encryptionparameters/ownerkey/) は null になります。 |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | パスワードがドキュメント所有者のパスワードかどうかを確認します。このメソッドは Initialize の後に呼び出されます。このメソッド呼び出しは PDF API で使用されます。 |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | パスワードがユーザーに属するか（ドキュメントを開くためのパスワード）を確認します。このメソッドは Initialize の後に呼び出されます。このメソッド呼び出しは PDF API で使用されます。 |

### 関連項目

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


