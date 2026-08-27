---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: ".mht ファイルを PDF ドキュメントにロード/インポートするオプションを表します。"
type: docs
weight: 4060
url: /ja/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

.mht ファイルを PDF ドキュメントにロード/インポートするオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | 空のベースパスでPostScriptをpdfドキュメントに変換するためのロードオプションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | フォントフォルダーのパスを取得します。変換用の追加フォントが含まれるフォルダーです。 |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | TrueTypeでないフォントをTTFに保存するかどうかを指定します。これにより、PSからPDFへの変換時に生成されるドキュメントの容量が大幅に減少し、TrueTypeでないフォントが大量に含まれるPSファイルを任意の出力形式に変換する速度が向上します。ただし、PostSctiptファイルを画像に変換する際にテキストがわずかに垂直方向にずれることがあります。 |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | TrueTypeでないフォントをTTFに保存するかどうかを指定します。これにより、PSからPDFへの変換時に生成されるドキュメントの容量が大幅に減少し、TrueTypeでないフォントが大量に含まれるPSファイルを任意の出力形式に変換する速度が向上します。ただし、PostSctiptファイルを画像に変換する際にテキストがわずかに垂直方向にずれることがあります。 |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | フォントフォルダーのパスを設定します。変換用の追加フォントが含まれるフォルダーです。 |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

空のベースパスでPostScriptをpdfドキュメントに変換するためのロードオプションを作成します。

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

フォントフォルダーのパスを取得します。変換用の追加フォントが含まれるフォルダーです。

**Returns:**
String 値の配列

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

TrueTypeでないフォントをTTFに保存するかどうかを指定します。これにより、PSからPDFへの変換時に生成されるドキュメントの容量が大幅に減少し、TrueTypeでないフォントが大量に含まれるPSファイルを任意の出力形式に変換する速度が向上します。ただし、PostSctiptファイルを画像に変換する際にテキストがわずかに垂直方向にずれることがあります。

**Returns:**
ブール値

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

TrueTypeでないフォントをTTFに保存するかどうかを指定します。これにより、PSからPDFへの変換時に生成されるドキュメントの容量が大幅に減少し、TrueTypeでないフォントが大量に含まれるPSファイルを任意の出力形式に変換する速度が向上します。ただし、PostSctiptファイルを画像に変換する際にテキストがわずかに垂直方向にずれることがあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
フォントフォルダーのパスを設定します。変換用の追加フォントが含まれるフォルダーです。
