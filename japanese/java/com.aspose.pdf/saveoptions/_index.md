---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "SaveOptions 型は個々の保存オプションに対する抽象化レベルを保持します。"
type: docs
weight: 4370
url: /ja/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

SaveOptions 型は個々の保存オプションに対する抽象化レベルを保持します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | データ保存の形式です。 |
| [getWarningHandler](#getWarningHandler--) | 警告が生成された際に処理するコールバックです。WarningHandler は ReturnAction 列挙体の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合、保存操作は中止されます。 |
| [isCacheGlyphs](#isCacheGlyphs--) | フォントグリフを APS ページの準備中にキャッシュするかどうかを示すブール値を取得または設定します。これにより PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [isCloseResponse](#isCloseResponse--) | ドキュメントがレスポンスに保存された後に Response オブジェクトが閉じられるかどうかを示すブール値を取得します。 |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | フォントグリフを APS ページの準備中にキャッシュするかどうかを示すブール値を取得または設定します。これにより PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [setCloseResponse](#setCloseResponse-boolean-) | ドキュメントがレスポンスに保存された後に Response オブジェクトが閉じられるかどうかを示すブール値を設定します。 |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 警告が生成された際に処理するコールバックです。WarningHandler は ReturnAction 列挙体の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合、保存操作は中止されます。 |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

データ保存の形式です。

**Returns:**
SaveFormat の値 @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

警告が生成された際に処理するコールバックです。WarningHandler は ReturnAction 列挙体の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合、保存操作は中止されます。

**Returns:**
IWarningCallback の値

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

フォントグリフを APS ページの準備中にキャッシュするかどうかを示すブール値を取得または設定します。これにより PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。

**Returns:**
ブール値

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

ドキュメントがレスポンスに保存された後に Response オブジェクトが閉じられるかどうかを示すブール値を取得します。

**Returns:**
ブール値

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

フォントグリフを APS ページの準備中にキャッシュするかどうかを示すブール値を取得または設定します。これにより PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

ドキュメントがレスポンスに保存された後に Response オブジェクトが閉じられるかどうかを示すブール値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
警告が生成された際に処理するコールバックです。WarningHandler は ReturnAction 列挙体の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合、保存操作は中止されます。
