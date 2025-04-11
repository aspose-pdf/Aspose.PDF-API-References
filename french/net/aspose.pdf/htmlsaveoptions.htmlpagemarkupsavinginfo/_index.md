---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l'enregistrement personnalisé du balisage d'une page HTML lors de la conversion de PDF en HTML.
type: docs
weight: 5670
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Classe HtmlSaveOptions.HtmlPageMarkupSavingInfo

Si la propriété SplitToPages de HtmlSaveOptions est activée, alors plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l'enregistrement personnalisé du balisage d'une page HTML lors de la conversion de PDF en HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Défini par le convertisseur. Représente le HTML enregistré sous forme de flux |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Doit être défini dans le code personnalisé si nécessaire. Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour une raison quelconque, le balisage HTML fourni doit être traité non pas avec le code personnalisé mais avec le code du convertisseur lui-même de manière standard pour le convertisseur. Ainsi, définir ce drapeau dans le code personnalisé signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui-même |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Défini par le convertisseur. Si la propriété SplitToPages est définie, alors plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété contient l'ordre du fichier de la page HTML enregistrée. La propriété peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer la page HTML et si le fractionnement en pages est désactivé, cette valeur contient toujours '1' puisque dans ce cas, une seule grande page HTML est générée pour l'ensemble du document source. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Défini par le convertisseur. Si la propriété SplitToPages est définie, alors plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion. Cette propriété indique au code personnalisé de quelle page du PDF original a été créé le balisage HTML enregistré. Si le numéro de page original est inconnu pour une raison quelconque ou si SplitOnPages=false, alors cette propriété contient toujours '0', ce qui signale que le convertisseur ne peut pas fournir le numéro de page exact du PDF original pour le fichier de balisage HTML fourni. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)