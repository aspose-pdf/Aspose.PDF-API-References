---
title: "Marca"
linktitle: "Marca"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe astratta per vari tipi di timbri che vengono come discendenti."
type: docs
weight: 4620
url: /it/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Una classe astratta per vari tipi di timbri che vengono come discendenti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Ottiene il margine inferiore della marca. |
| [getHeight](#getHeight--) | Ottiene l'altezza desiderata della marca nella pagina. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ottiene l'allineamento orizzontale della marca nella pagina. |
| [getLeftMargin](#getLeftMargin--) | Ottiene il margine sinistro della marca. |
| [getOpacity](#getOpacity--) | Ottiene un valore che indica l'opacità della marca. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Ottiene un valore che indica l'opacità del contorno della marca. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Ottiene un valore della larghezza del contorno della marca. Per impostazione predefinita il valore è 1.0. |
| [getRightMargin](#getRightMargin--) | Ottiene il margine destro della marca. |
| [getRotate](#getRotate--) | Ottiene la rotazione del contenuto della marca secondo i valori {@code Rotation}. Nota. Questa proprietà è per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Ottiene l'angolo di rotazione della marca in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [getStampId](#getStampId--) | Ottiene l'ID della marca. |
| [getTopMargin](#getTopMargin--) | Ottiene il margine superiore della marca. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene l'allineamento verticale della marca nella pagina. |
| [getWidth](#getWidth--) | Ottiene la larghezza desiderata della marca nella pagina. |
| [getXIndent](#getXIndent--) | Ottiene la coordinata orizzontale della marca, a partire da sinistra. |
| [getYIndent](#getYIndent--) | Ottiene la coordinata verticale della marca, a partire dal basso. |
| [getZoom](#getZoom--) | Ottiene il fattore di zoom della marca. Consente di scalare la marca. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| [getZoomX](#getZoomX--) | Ottiene il fattore di zoom orizzontale della marca. Consente di scalare la marca orizzontalmente. |
| [getZoomY](#getZoomY--) | Ottiene il fattore di zoom verticale della marca. Consente di scalare la marca verticalmente. |
| [isBackground](#isBackground--) | Ottiene un valore booleano che indica se il contenuto è stampato come sfondo. Se il valore è true, il contenuto della marca è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto della marca è posizionato in alto. |
| [put](#put-com.aspose.pdf.Page-) | Aggiunge la marca nella pagina. |
| [setBackground](#setBackground-boolean-) | Imposta un valore booleano che indica se il contenuto è stampato come sfondo. Se il valore è true, il contenuto della marca è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto della marca è posizionato in alto. |
| [setBottomMargin](#setBottomMargin-double-) | Imposta il margine inferiore della marca. |
| [setHeight](#setHeight-double-) | Imposta l'altezza desiderata del timbro nella pagina. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento orizzontale del timbro nella pagina. |
| [setLeftMargin](#setLeftMargin-double-) | Imposta il margine sinistro del timbro. |
| [setOpacity](#setOpacity-double-) | Imposta un valore per indicare l'opacità del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Imposta un valore per indicare l'opacità del contorno del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Imposta un valore per la larghezza del contorno del timbro. Per impostazione predefinita il valore è 1.0. |
| [setRightMargin](#setRightMargin-double-) | Imposta il margine destro del timbro. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Imposta la rotazione del contenuto del timbro secondo i valori {@code Rotation}. Nota. Questa proprietà è per angoli impostati che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [setStampId](#setStampId-int-) | Imposta l'ID del timbro. |
| [setTopMargin](#setTopMargin-double-) | Imposta il margine superiore del timbro. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale del timbro nella pagina. |
| [setWidth](#setWidth-double-) | Imposta la larghezza desiderata del timbro nella pagina. |
| [setXIndent](#setXIndent-double-) | Imposta la coordinata orizzontale del timbro, a partire da sinistra. |
| [setYIndent](#setYIndent-double-) | Imposta la coordinata verticale del timbro, a partire dal basso. |
| [setZoom](#setZoom-double-) | Ottiene il fattore di zoom della marca. Consente di scalare la marca. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| [setZoomX](#setZoomX-double-) | Imposta il fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente. |
| [setZoomY](#setZoomY-double-) | Imposta il fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Ottiene il margine inferiore della marca.

**Returns:**
valore double

### getHeight {#getHeight--}
```
public double getHeight()
```

Ottiene l'altezza desiderata della marca nella pagina.

**Returns:**
valore double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ottiene l'allineamento orizzontale della marca nella pagina.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Ottiene il margine sinistro della marca.

**Returns:**
valore double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Ottiene un valore che indica l'opacità della marca. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0.

**Returns:**
valore double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Ottiene un valore che indica l'opacità del contorno della marca. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0.

**Returns:**
valore double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Ottiene un valore della larghezza del contorno della marca. Per impostazione predefinita il valore è 1.0.

**Returns:**
valore double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Ottiene il margine destro della marca.

**Returns:**
valore double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Ottiene la rotazione del contenuto della marca secondo i valori {@code Rotation}. Nota. Questa proprietà è per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None.

**Returns:**
Valore di rotazione @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Ottiene l'angolo di rotazione della marca in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario.

**Returns:**
valore double

### getStampId {#getStampId--}
```
public int getStampId()
```

Ottiene l'ID della marca.

**Returns:**
Identificatore del timbro.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Ottiene il margine superiore della marca.

**Returns:**
valore double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ottiene l'allineamento verticale della marca nella pagina.

**Returns:**
Valore di VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza desiderata della marca nella pagina.

**Returns:**
valore double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Ottiene la coordinata orizzontale della marca, a partire da sinistra.

**Returns:**
valore double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Ottiene la coordinata verticale della marca, a partire dal basso.

**Returns:**
valore double

### getZoom {#getZoom--}
```
public double getZoom()
```

Ottiene il fattore di zoom della marca. Consente di scalare la marca. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX.

**Returns:**
valore double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Ottiene il fattore di zoom orizzontale della marca. Consente di scalare la marca orizzontalmente.

**Returns:**
valore double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Ottiene il fattore di zoom verticale della marca. Consente di scalare la marca verticalmente.

**Returns:**
valore double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Ottiene un valore booleano che indica se il contenuto è stampato come sfondo. Se il valore è true, il contenuto della marca è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto della marca è posizionato in alto.

**Returns:**
valore booleano

### put {#put-com.aspose.pdf.Page-}
Aggiunge la marca nella pagina.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Imposta un valore booleano che indica se il contenuto è stampato come sfondo. Se il valore è true, il contenuto della marca è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto della marca è posizionato in alto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Imposta il margine inferiore della marca.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Imposta l'altezza desiderata del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento orizzontale del timbro nella pagina.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Imposta il margine sinistro del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Imposta un valore per indicare l'opacità del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Imposta un valore per indicare l'opacità del contorno del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Imposta un valore per la larghezza del contorno del timbro. Per impostazione predefinita il valore è 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Imposta il margine destro del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Imposta la rotazione del contenuto del timbro secondo i valori {@code Rotation}. Nota. Questa proprietà è per angoli impostati che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | angolo di rotazione |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Imposta l'ID del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Nuovo valore dell'ID del timbro. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Imposta il margine superiore del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale del timbro nella pagina.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza desiderata del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Imposta la coordinata orizzontale del timbro, a partire da sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Imposta la coordinata verticale del timbro, a partire dal basso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Ottiene il fattore di zoom della marca. Consente di scalare la marca. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Imposta il fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Imposta il fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
