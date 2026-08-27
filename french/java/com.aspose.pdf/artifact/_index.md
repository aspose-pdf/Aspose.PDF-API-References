---
title: "Artefact"
linktitle: "Artefact"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant un objet PDF Artifact."
type: docs
weight: 190
url: /fr/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Classe représentant un objet PDF Artifact.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Constructeur de l'artefact avec le type et le sous‑type spécifiés |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Ce constructeur est utilisé lorsque l'artefact est lu depuis la page. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Constructeur de l'artefact avec le type et le sous‑type spécifiés |

## Méthodes

| Méthode | Description |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Commencez les mises à jour supprimées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artefact afin d'améliorer les performances. Habituellement, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact est changée. Cela entraîne la modification du contenu de la page à chaque modification de l'artefact. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [dispose](#dispose--) | Libère l'artefact. Cette méthode est obsolète, utilisez close() à la place. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Obtient l'alignement horizontal de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Obtient l'alignement vertical de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getBottomMargin](#getBottomMargin--) | Obtient la marge inférieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getContents](#getContents--) | Obtient la collection des opérateurs internes de l'artefact. |
| [getCustomSubtype](#getCustomSubtype--) | Obtient le nom du sous‑type de l'artefact. Peut être utilisé si le sous‑type de l'artefact n'est pas un sous‑type standard. |
| [getCustomType](#getCustomType--) | Obtient le nom du type de l'artefact. Peut être utilisé si le type de l'artefact n'est pas standard. |
| [getForm](#getForm--) | Obtient le XForm de l'artefact (si le XForm est utilisé). |
| [getImage](#getImage--) | Obtient l'image de l'artefact (si elle est présente). |
| [getLeftMargin](#getLeftMargin--) | Obtient la marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getLines](#getLines--) | Lignes de l'artefact texte multiligne. |
| [getOpacity](#getOpacity--) | Obtient l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1. |
| [getPosition](#getPosition--) | Obtient la position de l'artefact. Si cette propriété est spécifiée, les marges et les alignements sont ignorés. |
| [getRectangle](#getRectangle--) | Obtient le rectangle de l'artefact. |
| [getRightMargin](#getRightMargin--) | Obtient la marge droite de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getRotation](#getRotation--) | Obtient l'angle de rotation de l'artefact. |
| [getSubtype](#getSubtype--) | Obtient le sous‑type de l'artefact. Si l'artefact possède un sous‑type non standard, le nom du sous‑type peut être lu via CustomSubtype. |
| [getText](#getText--) | Obtient le texte de l'artefact. |
| [getTextState](#getTextState--) | État du texte pour le texte de l'artefact. |
| [getTopMargin](#getTopMargin--) | Obtient la marge supérieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [getType](#getType--) | Obtient le type d'artefact. |
| [getValue](#getValue-java.lang.String-) | Obtient la valeur personnalisée de l'artefact. |
| [isBackground](#isBackground--) | Si vrai, l'artefact est placé derrière le contenu de la page. |
| [removeValue](#removeValue-java.lang.String-) | Supprime la valeur personnalisée de l'artefact. |
| [saveUpdates](#saveUpdates--) | Enregistre toutes les mises à jour de l'artefact qui ont été effectuées après l'appel de BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtient l'alignement horizontal de l'artefact. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit l'alignement vertical de l'artefact. |
| [setBackground](#setBackground-boolean-) | Si vrai, l'artefact est placé derrière le contenu de la page. |
| [setBottomMargin](#setBottomMargin-double-) | Définit la marge inférieure de l'artefact. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Définit le nom du type d'artefact. Peut être utilisé si le type d'artefact n'est pas standard. |
| [setImage](#setImage-java.io.InputStream-) | Définit l'image de l'artefact. |
| [setImage](#setImage-java.lang.String-) | Définit l'image de l'artefact. |
| [setLeftMargin](#setLeftMargin-double-) | Définit la marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Définit le texte et les propriétés du texte de l'artefact. Permet de spécifier plusieurs lignes. |
| [setOpacity](#setOpacity-double-) | Définit l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Définit la chaîne qui sera remplacée par le numéro de page. La valeur par défaut est #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Définit la page PDF qui est placée sur la page du document en tant qu'artefact. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Définit la position de l'artefact. |
| [setRightMargin](#setRightMargin-double-) | Définit la marge droite de l'artefact. |
| [setRotation](#setRotation-double-) | Définit l'angle de rotation de l'artefact. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Définit le sous-type de l'artefact. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Définit le texte de l'artefact. |
| [setText](#setText-java.lang.String-) | Définit le texte de l'artefact. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Définit le texte et les propriétés du texte de l'artefact. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | État du texte pour le texte de l'artefact. |
| [setTopMargin](#setTopMargin-double-) | Définit la marge supérieure de l'artefact. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Définit le type d'artefact. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Définit la valeur personnalisée de l'artefact. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Constructeur de l'artefact avec le type et le sous‑type spécifiés

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Ce constructeur est utilisé lorsque l'artefact est lu depuis la page.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Constructeur de l'artefact avec le type et le sous‑type spécifiés

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Commencez les mises à jour supprimées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artefact afin d'améliorer les performances. Habituellement, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact est changée. Cela entraîne la modification du contenu de la page à chaque modification de l'artefact. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libère l'artefact. Cette méthode est obsolète, utilisez close() à la place.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Obtient l'alignement horizontal de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Obtient l'alignement vertical de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
Valeur de VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtient la marge inférieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
marge inférieure.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Obtient la collection des opérateurs internes de l'artefact.

**Returns:**
liste des opérateurs internes de l'artefact.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Obtient le nom du sous‑type de l'artefact. Peut être utilisé si le sous‑type de l'artefact n'est pas un sous‑type standard.

**Returns:**
valeur String

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Obtient le nom du type de l'artefact. Peut être utilisé si le type de l'artefact n'est pas standard.

**Returns:**
Nom de l'artefact String

### getForm {#getForm--}
```
public XForm getForm()
```

Obtient le XForm de l'artefact (si le XForm est utilisé).

**Returns:**
objet XForm

### getImage {#getImage--}
```
public XImage getImage()
```

Obtient l'image de l'artefact (si elle est présente).

**Returns:**
objet XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtient la marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
marge gauche de l'artefact.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Lignes de l'artefact texte multiligne.

**Returns:**
Liste de chaînes

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtient l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1.

**Returns:**
opacité de l'artefact.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtient la position de l'artefact. Si cette propriété est spécifiée, les marges et les alignements sont ignorés.

**Returns:**
position de l'artefact.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle de l'artefact.

**Returns:**
objet Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtient la marge droite de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
marge droite de l'artefact.

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtient l'angle de rotation de l'artefact.

**Returns:**
angle de rotation de l'artefact.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Obtient le sous‑type de l'artefact. Si l'artefact possède un sous‑type non standard, le nom du sous‑type peut être lu via CustomSubtype.

**Returns:**
sous-type de l'artefact. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Obtient le texte de l'artefact.

**Returns:**
valeur String

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

État du texte pour le texte de l'artefact.

**Returns:**
instance TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtient la marge supérieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Returns:**
marge supérieure de l'artefact.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Obtient le type d'artefact.

**Returns:**
valeur du type d'artefact. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Obtient la valeur personnalisée de l'artefact.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Si vrai, l'artefact est placé derrière le contenu de la page.

**Returns:**
valeur booléenne

### removeValue {#removeValue-java.lang.String-}
Supprime la valeur personnalisée de l'artefact.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Enregistre toutes les mises à jour de l'artefact qui ont été effectuées après l'appel de BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtient l'alignement horizontal de l'artefact.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit l'alignement vertical de l'artefact.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Si vrai, l'artefact est placé derrière le contenu de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Définit la marge inférieure de l'artefact.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | marge inférieure. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Définit le nom du type d'artefact. Peut être utilisé si le type d'artefact n'est pas standard.

### setImage {#setImage-java.io.InputStream-}
Définit l'image de l'artefact.

### setImage {#setImage-java.lang.String-}
Définit l'image de l'artefact.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Définit la marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | marge gauche de l'artefact. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Définit le texte et les propriétés du texte de l'artefact. Permet de spécifier plusieurs lignes.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Définit l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | opacité de l'artefact. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Définit la chaîne qui sera remplacée par le numéro de page. La valeur par défaut est #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Définit la page PDF qui est placée sur la page du document en tant qu'artefact.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Définit la position de l'artefact.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Définit la marge droite de l'artefact.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | marge droite de l'artefact. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Définit l'angle de rotation de l'artefact.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | angle de rotation de l'artefact. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Définit le sous-type de l'artefact.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Définit le texte de l'artefact.

### setText {#setText-java.lang.String-}
Définit le texte de l'artefact.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Définit le texte et les propriétés du texte de l'artefact.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
État du texte pour le texte de l'artefact.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Définit la marge supérieure de l'artefact.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | marge supérieure de l'artefact. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Définit le type d'artefact.

### setValue {#setValue-java.lang.String-java.lang.String-}
Définit la valeur personnalisée de l'artefact.
