---
title: "Page"
linktitle: "Page"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを表すクラス。"
type: docs
weight: 3310
url: /ja/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

PDF ドキュメントのページを表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーションの操作機能を提供する {@code AnnotationSelector} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 画像配置オブジェクトの操作機能を提供する {@code ImagePlacementAbsorber} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | テキストオブジェクトの操作機能を提供する {@code TextAbsorber} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | テキストオブジェクトの操作機能を提供する {@code TextFragmentAbsorber} ビジターオブジェクトを受け入れます。 |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | ページにグラフィックを追加します。GraphicElement#addOnPage(Page) メソッドで要素を1つずつ追加するよりも高速に動作します。 |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | ページにグラフィックを追加します。GraphicElement#addOnPage(Page) メソッドで要素を1つずつ追加するよりも高速に動作します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | ページにスタンプを配置します。スタンプはページ番号、画像、または単純なテキスト（例: ロゴ）にできます。 |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | 現在のページを BMP ビットマップに変換し、バイト配列を返します。 |
| [asXml](#asXml--) | 現在のページを UTF-8 エンコードの XML に変換します。 |
| [calculateContentBBox](#calculateContentBBox--) | bbox 値を計算します - 可視マージンなしでコンテンツを含む矩形です。 |
| [clearContents](#clearContents--) | 内部使用のみです。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | DSR、OMR、OCR 画像ストリーム用にページを PNG に変換します。 |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | ページからグラフィックを削除します。{@link GraphicElement#remove} メソッドで要素を一つずつ削除するよりも高速です。 |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | メモリを解放します。このメソッドは廃止されました。代わりに close() を使用してください。 |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | 指定された名前のリソースを使用するオペレーターのリストを返します。 |
| [findReferences](#findReferences-java.lang.String-) | <p> 参照を検索 </p> |
| [flatten](#flatten--) | ページ上にあるすべての静的フィールドを削除し、その代わりに値を配置します。 |
| [freeMemory](#freeMemory--) | キャッシュされたデータをクリアします |
| [getActions](#getActions--) | ページプロパティのコレクションを取得します。 |
| [getAnnotations](#getAnnotations--) | ページ注釈のコレクションを取得します。 {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> ページのアートボックスを取得します。 </p> |
| [getArtifacts](#getArtifacts--) | ページ上のアーティファクトのコレクションを取得します。 |
| [getBackground](#getBackground--) | ページの背景色を取得します。 |
| [getBackgroundImage](#getBackgroundImage--) | ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。 |
| [getBleedBox](#getBleedBox--) | <p> ページのブリードボックスを取得します。 </p> |
| [getColorType](#getColorType--) | SetColor オペレーター、画像、フォームから取得した情報に基づいてページのカラ―タイプを取得します。 |
| [getContents](#getContents--) | <p> ページのコンテンツストリーム内のオペレーターのコレクションを取得します。 {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | 現在のコンテンツアペンダーを取得します。 {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> ページのクロップボックスを取得します。 </p> |
| [getDocument](#getDocument--) | ドキュメントを取得します。 |
| [getDuration](#getDuration--) | <p> ページの表示時間を取得します。これはプレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。 </p> <hr> 例はページの表示時間の取得方法を示しています <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | 内部使用のみ |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | このページのタブ順にある Field オブジェクトのリストを取得します。 |
| [getFooter](#getFooter--) | ページのフッターを取得します。 |
| [getGroup](#getGroup--) | 透過イメージングモデルで使用するために、ページのページグループの属性を指定するグループ属性クラスを取得します。 |
| [getHeader](#getHeader--) | ページヘッダーを取得します。 |
| [getLayers](#getLayers--) | レイヤーコレクションを取得します。 |
| [getMediaBox](#getMediaBox--) | <p> ページのメディアボックスを取得します。 </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | ノートの線スタイルを取得します。（生成時のみ使用され、ドキュメントを読み込む際には設定されません） |
| [getNotifications](#getNotifications--) | ページコンテンツに対する内部操作に関する通知を返します。（現在、テキスト追加シナリオにおける段落イベントに関する通知のみがサポートされています） |
| [getNumber](#getNumber--) | ページ番号を取得します。 |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | ヘッダーとフッターをカスタマイズするためのイベントです。 |
| [getPageInfo](#getPageInfo--) | ページ情報を取得します。（生成時のみ使用され、ドキュメントを読み込む際には設定されません） |
| [getPageRect](#getPageRect-boolean-) | CropBox（またはCropBoxがnullの場合はMediaBox）に基づくページの矩形を返します。 |
| [getParagraphs](#getParagraphs--) | 段落を取得します。 |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> CropBoxとMediaBoxに基づくページの矩形を返します； </p> Internal |
| [getRect](#getRect--) | <p> CropBoxとMediaBoxに基づくページの矩形を返します；取得時: 指定されていればページのCropBoxが返され、そうでなければページのMediaBoxが返されます。設定時: 常にページのMediaBoxが設定されます。 </p> |
| [getResources](#getResources--) | ページに関連付けられたリソースを取得します。 |
| [getResourcesField](#getResourcesField--) | <p> ページリソースを取得します。Resourcesオブジェクトは画像、フォーム、フォントのコレクションを含みます。{@code Resources} </p> |
| [getRotate](#getRotate--) | <p> ページの回転を取得します。 </p> |
| [getRotationMatrix](#getRotationMatrix--) | ページの変換行列を取得します。 |
| [getTabOrder](#getTabOrder--) | ページのタブ順序を取得します。可能な値: Row、Column。デフォルト、Manual |
| [getTocInfo](#getTocInfo--) | 目次情報を取得します。 |
| [getTrimBox](#getTrimBox--) | <p> ページのトリムボックスを取得します。 </p> |
| [getUserUnit](#getUserUnit--) | UserUnit値を取得または設定します。デフォルトのユーザースペース単位のサイズを示す正の数で、1/72インチの倍数です。デフォルト値は1です。このエントリをページからクリアするには、0または負の値を設定してください。 |
| [getWatermark](#getWatermark--) | ページの透かしを取得します。 |
| [hasVectorGraphics](#hasVectorGraphics--) | ページにベクターグラフィックが存在するかどうかを検出します。 |
| [intToRotation](#intToRotation-int-) | 整数値を対応する回転列挙体メンバーに変換します。 |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | ページの最後の段落の後に段落を追加するかどうかを取得または設定します。Value: この値はページの最後の段落の後に段落が追加されるかどうかを示します。value が true の場合、ページの最後の段落の後に段落が追加されます。 |
| [isBlank](#isBlank-double-) | ページが空白かどうかのフラグを取得します。 |
| [isBlank](#isBlank-double-boolean-) | ページが空白かどうかのフラグを取得します。 |
| [makeGrayscale](#makeGrayscale--) | ページをグレースケールに変換します。 |
| [mergeLayers](#mergeLayers-java.lang.String-) | ページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します。 |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | ページ上のすべてのレイヤーを、指定された新しいレイヤー名とオプションのコンテンツグループIDで単一のレイヤーに結合します。 |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | オブジェクト参照を削除します |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | ページコンテンツから XObject への参照を削除します（例：オブジェクト名を使用するすべての Do 演算子）。 |
| [resize](#resize-com.aspose.pdf.PageSize-) | ページのサイズを変更します。 |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | 回転列挙体のメンバーを整数値に変換します。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | 指定されたページデバイスでページを処理に送ります。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | 指定されたページデバイスでページを処理に送ります。 |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | ページの最後の段落の後に段落を追加するかどうかを取得または設定します。Value: この値はページの最後の段落の後に段落が追加されるかどうかを示します。value が true の場合、ページの最後の段落の後に段落が追加されます。 |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | ページのアートボックスを設定します。 |
| [setBackground](#setBackground-java.awt.Color-) | ページの背景色を設定します。 |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | ページの背景色を設定します。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。 |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | ページのブリードボックスを設定します。 |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> ページのクロップボックスを設定します。 </p> <hr> <pre> 例として、ページのクロップボックスを取得する方法を示します: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | ページの表示時間を設定します。これは、プレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。 |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | 内部使用のみ |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | ページのフッターを設定します。 |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | 透明イメージングモデルで使用するために、ページのページグループの属性を指定するグループ属性クラスを設定します。 |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | ページのヘッダーを設定します。 |
| [setLayers](#setLayers-java.util.ArrayList-) | レイヤーコレクションを設定します。 |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | レイヤーコレクションを設定します。 |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | ページのメディアボックスを設定します。 |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | ノートの線スタイルを設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません） |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | ページ情報を設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません） |
| [setPageSize](#setPageSize-double-double-) | ページのサイズを設定します。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | 段落を設定します。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | ページの矩形を取得または設定します。取得時: 指定されている場合はページのクロップボックスが返され、指定されていない場合はページのメディアボックスが返されます。設定時: 常にページのメディアボックスが設定されます。なお、このプロパティはページの回転を考慮しません。回転を考慮したページ矩形を取得するには ActualRect を使用してください。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | ページの回転を設定します。 |
| [setTabOrder](#setTabOrder-int-) | ページのタブ順序を設定します。可能な値: Row、Column。デフォルトは Manual です。 |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | 目次情報を設定します。 |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | 遷移を設定します。 |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | ページのトリムボックスを設定します。 |
| [setUserUnit](#setUserUnit-double-) | UserUnit値を取得または設定します。デフォルトのユーザースペース単位のサイズを示す正の数で、1/72インチの倍数です。デフォルト値は1です。このエントリをページからクリアするには、0または負の値を設定してください。 |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | ページの透かしを設定します。 |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | ページにベクターグラフィックが存在する場合、保存を試みます。保存形式は SVG です。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーションの操作機能を提供する {@code AnnotationSelector} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
画像配置オブジェクトの操作機能を提供する {@code ImagePlacementAbsorber} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.TextAbsorber-}
テキストオブジェクトの操作機能を提供する {@code TextAbsorber} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
テキストオブジェクトの操作機能を提供する {@code TextFragmentAbsorber} ビジターオブジェクトを受け入れます。

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
ページにグラフィックを追加します。GraphicElement#addOnPage(Page) メソッドで要素を1つずつ追加するよりも高速に動作します。

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
ページにグラフィックを追加します。GraphicElement#addOnPage(Page) メソッドで要素を1つずつ追加するよりも高速に動作します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
ページに検索可能な画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保持します。

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
ページにスタンプを配置します。スタンプはページ番号、画像、または単純なテキスト（例: ロゴ）にできます。

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
現在のページを BMP ビットマップに変換し、バイト配列を返します。

### asXml {#asXml--}
```
public String asXml()
```

現在のページを UTF-8 エンコードの XML に変換します。

**Returns:**
変換された XML 文字列。

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

bbox 値を計算します - 可視マージンなしでコンテンツを含む矩形です。

**Returns:**
Bbbox 値 - 可視マージンなしでコンテンツを含む矩形

### clearContents {#clearContents--}
```
public void clearContents()
```

内部使用のみです。

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

DSR、OMR、OCR 画像ストリーム用にページを PNG に変換します。

**Returns:**
byte[] 配列内の画像ストリーム。

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
ページからグラフィックを削除します。{@link GraphicElement#remove} メソッドで要素を一つずつ削除するよりも高速です。

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

メモリを解放します。このメソッドは廃止されました。代わりに close() を使用してください。

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
指定された名前のリソースを使用するオペレーターのリストを返します。

### findReferences {#findReferences-java.lang.String-}
<p> 参照を検索 </p>

### flatten {#flatten--}
```
public void flatten()
```

ページ上にあるすべての静的フィールドを削除し、その代わりに値を配置します。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

キャッシュされたデータをクリアします

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

ページプロパティのコレクションを取得します。

**Returns:**
PageActionCollection の値

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

ページ注釈のコレクションを取得します。 {@code Annotations}

**Returns:**
AnnotationCollection の値

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> ページのアートボックスを取得します。 </p>

**Returns:**
矩形の値 <hr> <pre> 例として、ページのアートボックスを取得する方法を示します: Document document = new Document(\"sample.pdf\"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

ページ上のアーティファクトのコレクションを取得します。

**Returns:**
ArtifactCollection の値

### getBackground {#getBackground--}
```
public Color getBackground()
```

ページの背景色を取得します。

**Returns:**
カラー値

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。

**Returns:**
Image インスタンス

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> ページのブリードボックスを取得します。 </p>

**Returns:**
矩形の値 <hr> <pre> 例として、ページのブリードボックスを取得する方法を示します: Document document = new Document(\"sample.pdf\"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

SetColor オペレーター、画像、フォームから取得した情報に基づいてページのカラ―タイプを取得します。

**Returns:**
ColorType 要素 @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> ページのコンテンツストリーム内のオペレーターのコレクションを取得します。 {@code OperatorCollection} </p>

**Returns:**
OperatorCollection オブジェクト <hr> <pre> 例として、ページのオペレーターストリームを走査する方法を示します。 Document document = new Document(\"sample.pdf\"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

現在のコンテンツアペンダーを取得します。 {@code ContentsAppender}

**Returns:**
ContentsAppender の値

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> ページのクロップボックスを取得します。 </p>

**Returns:**
矩形の値 <hr> <pre> 例として、ページのクロップボックスを取得する方法を示します: Document document = new Document(\"sample.pdf\"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

ドキュメントを取得します。

**Returns:**
IDocument オブジェクト

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> ページの表示時間を取得します。これはプレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。 </p> <hr> 例はページの表示時間の取得方法を示しています <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double 値

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

内部使用のみ

**Returns:**
内部インスタンス

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

このページのタブ順にある Field オブジェクトのリストを取得します。

**Returns:**
フィールドオブジェクトのリスト

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

ページのフッターを取得します。

**Returns:**
ページのフッターです。

### getGroup {#getGroup--}
```
public Group getGroup()
```

透過イメージングモデルで使用するために、ページのページグループの属性を指定するグループ属性クラスを取得します。

**Returns:**
グループの値

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

ページヘッダーを取得します。

**Returns:**
ページのヘッダーです。

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

レイヤーコレクションを取得します。

**Returns:**
値: レイヤーのコレクション。

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> ページのメディアボックスを取得します。 </p>

**Returns:**
矩形の値 <hr> <pre> 例として、ページのメディアボックスを取得する方法を示します: Document document = new Document(\"sample.pdf\"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

ノートの線スタイルを取得します。（生成時のみ使用され、ドキュメントを読み込む際には設定されません）

**Returns:**
GraphInfo の値

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

ページコンテンツに対する内部操作に関する通知を返します。（現在、テキスト追加シナリオにおける段落イベントに関する通知のみがサポートされています）

**Returns:**
ページコンテンツに関する内部操作の通知を表す文字列。

### getNumber {#getNumber--}
```
public final int getNumber()
```

ページ番号を取得します。

**Returns:**
int 値です。

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

ヘッダーとフッターをカスタマイズするためのイベントです。

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

ページ情報を取得します。（生成時のみ使用され、ドキュメントを読み込む際には設定されません）

**Returns:**
ページ情報です。

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

CropBox（またはCropBoxがnullの場合はMediaBox）に基づくページの矩形を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| considerRotation |  | true の場合、ページの回転が矩形計算に考慮されます。 |

**Returns:**
ページの矩形。

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

段落を取得します。

**Returns:**
段落。

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> CropBoxとMediaBoxに基づくページの矩形を返します； </p> Internal

**Returns:**
矩形の値 <hr> <pre> 例ではページの矩形を取得する方法を示しています: Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> CropBoxとMediaBoxに基づくページの矩形を返します；取得時: 指定されていればページのCropBoxが返され、そうでなければページのMediaBoxが返されます。設定時: 常にページのMediaBoxが設定されます。 </p>

**Returns:**
矩形の値 <hr> <pre> 例ではページの矩形を取得する方法を示しています: Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

ページに関連付けられたリソースを取得します。

**Returns:**
ページのリソースを表す {@code Resources}({@link #getResources()}) オブジェクト。

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> ページリソースを取得します。Resourcesオブジェクトは画像、フォーム、フォントのコレクションを含みます。{@code Resources} </p>

**Returns:**
リソースの値 <hr> <pre> 例ではページ画像を走査する方法を示しています: Document document = new Document(\"sample.pdf\"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + \":\" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> ページの回転を取得します。 </p>

**Returns:**
回転要素 <hr> <pre> 例ではページの回転を判定する方法を示しています。 Document document = new Document(\"sample.pdf\"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

ページの変換行列を取得します。

**Returns:**
行列の値

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

ページのタブ順序を取得します。可能な値: Row、Column。デフォルト、Manual

**Returns:**
TabOrder の値 @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

目次情報を取得します。

**Returns:**
目次情報 - デフォルトは null。設定するとこのページに目次が含まれます。

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> ページのトリムボックスを取得します。 </p>

**Returns:**
矩形の値 <hr> <pre> 例ではページのトリムボックスを取得する方法を示しています: Document document = new Document(\"sample.pdf\"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

UserUnit値を取得または設定します。デフォルトのユーザースペース単位のサイズを示す正の数で、1/72インチの倍数です。デフォルト値は1です。このエントリをページからクリアするには、0または負の値を設定してください。

**Returns:**
double 値

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

ページの透かしを取得します。

**Returns:**
透かしの値

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

ページにベクターグラフィックが存在するかどうかを検出します。

**Returns:**
ページがパス構築演算子を含む場合は true、そうでない場合は false。

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

整数値を対応する回転列挙体メンバーに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 回転 |  | 変換する整数値 |

**Returns:**
Rotation 列挙メンバー @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

ページの最後の段落の後に段落を追加するかどうかを取得または設定します。Value: この値はページの最後の段落の後に段落が追加されるかどうかを示します。value が true の場合、ページの最後の段落の後に段落が追加されます。

**Returns:**
ブール値

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

ページが空白かどうかのフラグを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillThresholdFactor |  | 検出感度を管理する塗りつぶし閾値。範囲は [0..1) である必要があります。ページが空かどうかを判断するために、ページ全体に対する塗りつぶされた領域の比率を計算します。この比率を fillThresholdFactor パラメータと比較し、より小さい場合はページは空とみなされます。 |

**Returns:**
ブール値 true - ページが空白の場合；それ以外は false。

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

ページが空白かどうかのフラグを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillThresholdFactor |  | 検出感度を管理する塗りつぶし閾値。0.01 以上である必要があります。 |
| parseWhiteContent |  | 白色コンテンツ解析を伴う完全なページ走査の場合は true、デフォルトの false は高速アルゴリズムで、白色のグラフィックは空白ページではないとみなされます。 |

**Returns:**
ブール値 true - ページが空白の場合；それ以外は false。

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

ページをグレースケールに変換します。

### mergeLayers {#mergeLayers-java.lang.String-}
ページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します。

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
ページ上のすべてのレイヤーを、指定された新しいレイヤー名とオプションのコンテンツグループIDで単一のレイヤーに結合します。

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
オブジェクト参照を削除します

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
ページコンテンツから XObject への参照を削除します（例：オブジェクト名を使用するすべての Do 演算子）。

### resize {#resize-com.aspose.pdf.PageSize-}
ページのサイズを変更します。

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
回転列挙体のメンバーを整数値に変換します。

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
指定されたページデバイスでページを処理に送ります。

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
指定されたページデバイスでページを処理に送ります。

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

ページの最後の段落の後に段落を追加するかどうかを取得または設定します。Value: この値はページの最後の段落の後に段落が追加されるかどうかを示します。value が true の場合、ページの最後の段落の後に段落が追加されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
ページのアートボックスを設定します。

### setBackground {#setBackground-java.awt.Color-}
ページの背景色を設定します。

### setBackground {#setBackground-com.aspose.pdf.Color-}
ページの背景色を設定します。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
ページの背景画像を取得または設定します（ジェネレータ用のみで、ドキュメントを読み取る際には設定されません）。

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
ページのブリードボックスを設定します。

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> ページのクロップボックスを設定します。 </p> <hr> <pre> 例として、ページのクロップボックスを取得する方法を示します: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

ページの表示時間を設定します。これは、プレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ページ表示時間。 |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
内部使用のみ

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
ページのフッターを設定します。

### setGroup {#setGroup-com.aspose.pdf.Group-}
透明イメージングモデルで使用するために、ページのページグループの属性を指定するグループ属性クラスを設定します。

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
ページのヘッダーを設定します。

### setLayers {#setLayers-java.util.ArrayList-}
レイヤーコレクションを設定します。

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
レイヤーコレクションを設定します。

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
ページのメディアボックスを設定します。

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
ノートの線スタイルを設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません）

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
ページ情報を設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません）

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

ページのサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | ページ幅。 |
| 高さ |  | ページサイズ。 |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
段落を設定します。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
ページの矩形を取得または設定します。取得時: 指定されている場合はページのクロップボックスが返され、指定されていない場合はページのメディアボックスが返されます。設定時: 常にページのメディアボックスが設定されます。なお、このプロパティはページの回転を考慮しません。回転を考慮したページ矩形を取得するには ActualRect を使用してください。

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
ページの回転を設定します。

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

ページのタブ順序を設定します。可能な値: Row、Column。デフォルトは Manual です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TabOrder オブジェクト @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
目次情報を設定します。

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
遷移を設定します。

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
ページのトリムボックスを設定します。

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

UserUnit値を取得または設定します。デフォルトのユーザースペース単位のサイズを示す正の数で、1/72インチの倍数です。デフォルト値は1です。このエントリをページからクリアするには、0または負の値を設定してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
ページの透かしを設定します。

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
ページにベクターグラフィックが存在する場合、保存を試みます。保存形式は SVG です。
