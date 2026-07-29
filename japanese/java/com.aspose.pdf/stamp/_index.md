---
title: "スタンプ"
linktitle: "スタンプ"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "さまざまな種類のスタンプを表す抽象クラスです。"
type: docs
weight: 4620
url: /ja/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

さまざまな種類のスタンプを表す抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Stamp](#Stamp--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | スタンプの下余白を取得します。 |
| [getHeight](#getHeight--) | ページ上のスタンプの希望高さを取得します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | ページ上のスタンプの水平配置を取得します。 |
| [getLeftMargin](#getLeftMargin--) | スタンプの左余白を取得します。 |
| [getOpacity](#getOpacity--) | スタンプの不透明度を示す値を取得します。この値は 0.0 から 1.0 の範囲です。デフォルト値は 1.0 です。 |
| [getOutlineOpacity](#getOutlineOpacity--) | スタンプの輪郭不透明度を示す値を取得します。この値は 0.0 から 1.0 の範囲です。デフォルト値は 1.0 です。 |
| [getOutlineWidth](#getOutlineWidth--) | スタンプの輪郭幅の値を取得します。デフォルト値は 1.0 です。 |
| [getRightMargin](#getRightMargin--) | スタンプの右余白を取得します。 |
| [getRotate](#getRotate--) | スタンプコンテンツの回転を {@code Rotation} の値に従って取得します。注意: このプロパティは 90 度の倍数 (0, 90, 180, 270 度) の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [getRotateAngle](#getRotateAngle--) | スタンプの回転角度（度）を取得します。このプロパティは任意の回転角度を設定できます。 |
| [getStampId](#getStampId--) | スタンプ ID を取得します。 |
| [getTopMargin](#getTopMargin--) | スタンプの上余白を取得します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | ページ上のスタンプの垂直配置を取得します。 |
| [getWidth](#getWidth--) | ページ上のスタンプの希望幅を取得します。 |
| [getXIndent](#getXIndent--) | 左から開始するスタンプの水平座標を取得します。 |
| [getYIndent](#getYIndent--) | 下から開始するスタンプの垂直座標を取得します。 |
| [getZoom](#getZoom--) | スタンプのズーム係数を取得します。スタンプのスケーリングが可能です。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [getZoomX](#getZoomX--) | スタンプの水平ズーム係数を取得します。スタンプを水平に拡大縮小できます。 |
| [getZoomY](#getZoomY--) | スタンプの垂直ズーム係数を取得します。スタンプを垂直に拡大縮小できます。 |
| [isBackground](#isBackground--) | コンテンツが背景としてスタンプされているかを示す bool 値を取得します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。 |
| [put](#put-com.aspose.pdf.Page-) | ページにスタンプを追加します。 |
| [setBackground](#setBackground-boolean-) | コンテンツが背景としてスタンプされているかを示す bool 値を設定します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。 |
| [setBottomMargin](#setBottomMargin-double-) | スタンプの下余白を設定します。 |
| [setHeight](#setHeight-double-) | ページ上のスタンプの希望高さを設定します。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | ページ上のスタンプの水平配置を設定します。 |
| [setLeftMargin](#setLeftMargin-double-) | スタンプの左余白を設定します。 |
| [setOpacity](#setOpacity-double-) | スタンプの不透明度を示す値を設定します。値は 0.0 から 1.0 です。デフォルトでは 1.0 です。 |
| [setOutlineOpacity](#setOutlineOpacity-double-) | スタンプの輪郭不透明度を示す値を設定します。値は 0.0 から 1.0 です。デフォルトでは 1.0 です。 |
| [setOutlineWidth](#setOutlineWidth-double-) | スタンプの輪郭幅の値を設定します。デフォルトでは 1.0 です。 |
| [setRightMargin](#setRightMargin-double-) | スタンプの右余白を設定します。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | スタンプコンテンツの回転を {@code Rotation} の値に従って設定します。注意: このプロパティは 90 度の倍数（0、90、180、270 度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [setRotateAngle](#setRotateAngle-double-) | スタンプの回転角度を度単位で設定します。このプロパティは任意の回転角度を設定できます。 |
| [setStampId](#setStampId-int-) | スタンプの Id を設定します。 |
| [setTopMargin](#setTopMargin-double-) | スタンプの上余白を設定します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | ページ上のスタンプの垂直配置を設定します。 |
| [setWidth](#setWidth-double-) | ページ上のスタンプの希望幅を設定します。 |
| [setXIndent](#setXIndent-double-) | 左端から開始するスタンプの水平座標を設定します。 |
| [setYIndent](#setYIndent-double-) | 下端から開始するスタンプの垂直座標を設定します。 |
| [setZoom](#setZoom-double-) | スタンプのズーム係数を取得します。スタンプのスケーリングが可能です。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [setZoomX](#setZoomX-double-) | スタンプの水平ズーム係数を設定します。スタンプを水平に拡大縮小できます。 |
| [setZoomY](#setZoomY-double-) | スタンプの垂直ズーム係数を設定します。スタンプを垂直に拡大縮小できます。 |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

スタンプの下余白を取得します。

**Returns:**
double 値

### getHeight {#getHeight--}
```
public double getHeight()
```

ページ上のスタンプの希望高さを取得します。

**Returns:**
double 値

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

ページ上のスタンプの水平配置を取得します。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

スタンプの左余白を取得します。

**Returns:**
double 値

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

スタンプの不透明度を示す値を取得します。この値は 0.0 から 1.0 の範囲です。デフォルト値は 1.0 です。

**Returns:**
double 値

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

スタンプの輪郭不透明度を示す値を取得します。この値は 0.0 から 1.0 の範囲です。デフォルト値は 1.0 です。

**Returns:**
double 値

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

スタンプの輪郭幅の値を取得します。デフォルト値は 1.0 です。

**Returns:**
double 値

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

スタンプの右余白を取得します。

**Returns:**
double 値

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

スタンプコンテンツの回転を {@code Rotation} の値に従って取得します。注意: このプロパティは 90 度の倍数 (0, 90, 180, 270 度) の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。

**Returns:**
回転値 @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

スタンプの回転角度（度）を取得します。このプロパティは任意の回転角度を設定できます。

**Returns:**
double 値

### getStampId {#getStampId--}
```
public int getStampId()
```

スタンプ ID を取得します。

**Returns:**
スタンプの識別子です。

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

スタンプの上余白を取得します。

**Returns:**
double 値

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

ページ上のスタンプの垂直配置を取得します。

**Returns:**
VerticalAlignment 値 @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

ページ上のスタンプの希望幅を取得します。

**Returns:**
double 値

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

左から開始するスタンプの水平座標を取得します。

**Returns:**
double 値

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

下から開始するスタンプの垂直座標を取得します。

**Returns:**
double 値

### getZoom {#getZoom--}
```
public double getZoom()
```

スタンプのズーム係数を取得します。スタンプのスケーリングが可能です。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。

**Returns:**
double 値

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

スタンプの水平ズーム係数を取得します。スタンプを水平に拡大縮小できます。

**Returns:**
double 値

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

スタンプの垂直ズーム係数を取得します。スタンプを垂直に拡大縮小できます。

**Returns:**
double 値

### isBackground {#isBackground--}
```
public boolean isBackground()
```

コンテンツが背景としてスタンプされているかを示す bool 値を取得します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。

**Returns:**
ブール値

### put {#put-com.aspose.pdf.Page-}
ページにスタンプを追加します。

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

コンテンツが背景としてスタンプされているかを示す bool 値を設定します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

スタンプの下余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

ページ上のスタンプの希望高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
ページ上のスタンプの水平配置を設定します。

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

スタンプの左余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

スタンプの不透明度を示す値を設定します。値は 0.0 から 1.0 です。デフォルトでは 1.0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

スタンプの輪郭不透明度を示す値を設定します。値は 0.0 から 1.0 です。デフォルトでは 1.0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

スタンプの輪郭幅の値を設定します。デフォルトでは 1.0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

スタンプの右余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
スタンプコンテンツの回転を {@code Rotation} の値に従って設定します。注意: このプロパティは 90 度の倍数（0、90、180、270 度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

スタンプの回転角度を度単位で設定します。このプロパティは任意の回転角度を設定できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 回転角度 |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

スタンプの Id を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | Stamp ID の新しい値。 |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

スタンプの上余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
ページ上のスタンプの垂直配置を設定します。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

ページ上のスタンプの希望幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

左端から開始するスタンプの水平座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

下端から開始するスタンプの垂直座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

スタンプのズーム係数を取得します。スタンプのスケーリングが可能です。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

スタンプの水平ズーム係数を設定します。スタンプを水平に拡大縮小できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

スタンプの垂直ズーム係数を設定します。スタンプを垂直に拡大縮小できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
