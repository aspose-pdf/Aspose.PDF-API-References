---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "LoadOptions 型は個々のロードオプションに対する抽象化レベルを保持します。"
type: docs
weight: 2790
url: /ja/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

LoadOptions 型は個々のロードオプションに対する抽象化レベルを保持します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | {@code LoadOptions} が記述するファイル形式を表します。 |
| [getWarningHandler](#getWarningHandler--) | 生成された警告を処理するコールバック。WarningHandler は Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | ファイルを読み込む際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。{@code } が指定されている場合、このフォントのライセンスで禁止されている操作を実行できるようになり、たとえばライセンス規則で埋め込みが禁止されているフォントでも PDF ドキュメントに埋め込むことが可能になります。デフォルトは {@code } です。このフラグを使用する際は注意が必要です。設定すると、そのフラグを設定した人物が可能なライセンス/法的違反に対する全責任を自ら負うことになります。したがって自己責任で使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | ファイルを読み込む際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。{@code } が指定されている場合、このフォントのライセンスで禁止されている操作を実行できるようになり、たとえばライセンス規則で埋め込みが禁止されているフォントでも PDF ドキュメントに埋め込むことが可能になります。デフォルトは {@code } です。このフラグを使用する際は注意が必要です。設定すると、そのフラグを設定した人物が可能なライセンス/法的違反に対する全責任を自ら負うことになります。したがって自己責任で使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。 |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 生成された警告を処理するコールバック。WarningHandler は Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

{@code LoadOptions} が記述するファイル形式を表します。

**Returns:**
LoadFormat 要素 @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

生成された警告を処理するコールバック。WarningHandler は Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。

**Returns:**
IWarningCallback の値

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

ファイルを読み込む際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。{@code } が指定されている場合、このフォントのライセンスで禁止されている操作を実行できるようになり、たとえばライセンス規則で埋め込みが禁止されているフォントでも PDF ドキュメントに埋め込むことが可能になります。デフォルトは {@code } です。このフラグを使用する際は注意が必要です。設定すると、そのフラグを設定した人物が可能なライセンス/法的違反に対する全責任を自ら負うことになります。したがって自己責任で使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。

**Returns:**
ブール値

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

ファイルを読み込む際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。{@code } が指定されている場合、このフォントのライセンスで禁止されている操作を実行できるようになり、たとえばライセンス規則で埋め込みが禁止されているフォントでも PDF ドキュメントに埋め込むことが可能になります。デフォルトは {@code } です。このフラグを使用する際は注意が必要です。設定すると、そのフラグを設定した人物が可能なライセンス/法的違反に対する全責任を自ら負うことになります。したがって自己責任で使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
生成された警告を処理するコールバック。WarningHandler は Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。
