---
title: "Classe HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML, un fichier HTML par page convertie, sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l’enregistrement personnalisé du balisage d’une page HTML lors de la conversion de PDF en HTML."
type: docs
weight: 5800
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l’enregistrement personnalisé du balisage d’une page HTML lors de la conversion de PDF en HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Défini par le convertisseur. Représente le HTML enregistré sous forme de flux. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Doit être défini dans le code personnalisé lorsque nécessaire. Ce drapeau doit être réglé sur "true" dans le code personnalisé si, pour certaines raisons, le balisage HTML fourni doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard. Ainsi, définir ce drapeau dans le code personnalisé indique que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l’ordre du fichier HTML enregistré. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et, si le fractionnement en pages est désactivé, cette valeur contient toujours « 1 » puisque dans ce cas une seule grande page HTML est générée pour l’ensemble du Document source. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Défini par le convertisseur. Si la propriété SplitToPages est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé à partir de quelle page du PDF original le balisage HTML enregistré a été créé. Si le numéro de page original est inconnu ou si SplitOnPages=false, cette propriété contient toujours « 0 », ce qui signale que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


