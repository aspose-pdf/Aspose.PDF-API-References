---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente l’ensemble de."
type: docs
weight: 2100
url: /fr/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l'enregistrement personnalisé du balisage d'une page HTML pendant la conversion de PDF en HTML.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Défini par le convertisseur. Représente le HTML enregistré sous forme de flux |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l’ordinal du fichier de page HTML enregistré. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et, si le fractionnement en pages est désactivé, cette valeur contient toujours « 1 » puisque dans ce cas une seule grande page HTML est générée pour l’ensemble du document source. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé à partir de quelle page du PDF original le balisage HTML enregistré a été créé. Si le numéro de page original est pour une raison quelconque inconnu ou si SplitOnPages=false, alors cette propriété contient toujours « 0 », ce qui indique que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni. |
| [getSupposedFileName](#getSupposedFileName--) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Doit être défini dans le code personnalisé lorsque nécessaire. Ce drapeau doit être mis à \"true\" dans le code personnalisé si, pour certaines raisons, le balisage HTML fourni doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même, de manière standard pour le convertisseur. Ainsi, définir ce drapeau dans le code personnalisé signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑-même. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Défini par le convertisseur. Représente le HTML enregistré sous forme de flux |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Doit être défini dans le code personnalisé lorsque nécessaire. Ce drapeau doit être mis à \"true\" dans le code personnalisé si, pour certaines raisons, le balisage HTML fourni doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même, de manière standard pour le convertisseur. Ainsi, définir ce drapeau dans le code personnalisé signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑-même. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l’ordinal du fichier de page HTML enregistré. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et, si le fractionnement en pages est désactivé, cette valeur contient toujours « 1 » puisque dans ce cas une seule grande page HTML est générée pour l’ensemble du document source. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé à partir de quelle page du PDF original le balisage HTML enregistré a été créé. Si le numéro de page original est pour une raison quelconque inconnu ou si SplitOnPages=false, alors cette propriété contient toujours « 0 », ce qui indique que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Défini par le convertisseur. Représente le HTML enregistré sous forme de flux

**Returns:**
Instance InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l’ordinal du fichier de page HTML enregistré. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et, si le fractionnement en pages est désactivé, cette valeur contient toujours « 1 » puisque dans ce cas une seule grande page HTML est générée pour l’ensemble du document source.

**Returns:**
valeur int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé à partir de quelle page du PDF original le balisage HTML enregistré a été créé. Si le numéro de page original est pour une raison quelconque inconnu ou si SplitOnPages=false, alors cette propriété contient toujours « 0 », ce qui indique que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni.

**Returns:**
valeur int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu.

**Returns:**
valeur String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Doit être défini dans le code personnalisé lorsque nécessaire. Ce drapeau doit être mis à \"true\" dans le code personnalisé si, pour certaines raisons, le balisage HTML fourni doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même, de manière standard pour le convertisseur. Ainsi, définir ce drapeau dans le code personnalisé signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑-même.

**Returns:**
valeur booléenne

### setContentStream {#setContentStream-java.io.InputStream-}
Défini par le convertisseur. Représente le HTML enregistré sous forme de flux

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Doit être défini dans le code personnalisé lorsque nécessaire. Ce drapeau doit être mis à \"true\" dans le code personnalisé si, pour certaines raisons, le balisage HTML fourni doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même, de manière standard pour le convertisseur. Ainsi, définir ce drapeau dans le code personnalisé signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑-même.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| customProcessingCancelled |  | valeur booléenne |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l’ordinal du fichier de page HTML enregistré. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et, si le fractionnement en pages est désactivé, cette valeur contient toujours « 1 » puisque dans ce cas une seule grande page HTML est générée pour l’ensemble du document source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber |  | valeur int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé à partir de quelle page du PDF original le balisage HTML enregistré a été créé. Si le numéro de page original est pour une raison quelconque inconnu ou si SplitOnPages=false, alors cette propriété contient toujours « 0 », ce qui indique que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber |  | valeur int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu.
