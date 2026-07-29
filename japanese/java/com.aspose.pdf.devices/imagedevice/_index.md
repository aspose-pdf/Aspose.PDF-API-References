---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "画像デバイス用の抽象クラスです。"
type: docs
weight: 110
url: /ja/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

画像デバイス用の抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageDevice](#ImageDevice--) | {@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。 |
| [ImageDevice](#ImageDevice-int-int-) | 提供された画像サイズとデフォルト解像度 (=150) で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | {@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | {@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | {@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | {@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | ページを {@link java.awt.image.BufferedImage} に変換します。 |
| [getCoordinateType](#getCoordinateType--) | ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。 |
| [getCropRectangle](#getCropRectangle--) | 画像に変換される領域を定義する矩形を取得します。デフォルトは null で、この場合はページ全体が画像に変換されます。 |
| [getFormPresentationMode](#getFormPresentationMode--) | フォームの表示モードを取得します。 |
| [getHeight](#getHeight--) | 画像の出力高さを取得します。 |
| [getRenderingOptions](#getRenderingOptions--) | レンダリング オプションを取得します。 |
| [getResolution](#getResolution--) | 画像の解像度を取得します。 |
| [getWidth](#getWidth--) | 画像の出力幅を取得します。 |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | シェーディング処理のパフォーマンスが高いかどうかを示します。デフォルトは true です。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。 |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | 画像に変換される領域を定義する矩形を設定します。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | フォームの表示モードを設定します。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | レンダリング オプションを設定します。 |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | シェーディング処理のパフォーマンスが高いかどうかを設定します。 |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

{@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

提供された画像サイズとデフォルト解像度 (=150) で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
{@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
{@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
{@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
{@code ImageDevice} の派生クラス用の抽象イニシャライザで、解像度を 150x150 に設定します。

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
ページを {@link java.awt.image.BufferedImage} に変換します。

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。

**Returns:**
PageCoordinateType 要素 @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

画像に変換される領域を定義する矩形を取得します。デフォルトは null で、この場合はページ全体が画像に変換されます。

**Returns:**
Rectangle オブジェクト

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

フォームの表示モードを取得します。

**Returns:**
FormPresentationMode 要素 @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

画像の出力高さを取得します。

**Returns:**
int 値です。

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

レンダリング オプションを取得します。

**Returns:**
RenderingOptions 要素

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

画像の解像度を取得します。

**Returns:**
Resolution 要素

### getWidth {#getWidth--}
```
public int getWidth()
```

画像の出力幅を取得します。

**Returns:**
int 値です。

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

シェーディング処理のパフォーマンスが高いかどうかを示します。デフォルトは true です。

**Returns:**
ブール値

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
画像に変換される領域を定義する矩形を設定します。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

フォームの表示モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | FormPresentationMode 要素 @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
レンダリング オプションを設定します。

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

シェーディング処理のパフォーマンスが高いかどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
