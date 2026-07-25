---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le résultat de la conversion peut contenir une ou plusieurs pages HTML (qui peuvent également référencer des fichiers externes tels que des images ou des polices). Vous pouvez assigner à cette propriété un délégué créé à partir de."
type: docs
weight: 2110
url: /fr/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Le résultat de la conversion peut contenir une ou plusieurs pages HTML (qui peuvent également référencer des fichiers externes tels que des images ou des polices). Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue (le HTML lui‑même) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires à l'enregistrement du balisage de la page HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement de ce cas ou de celui‑ci doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, comme si aucun code d'enregistrement personnalisé externe n'existait.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Méthode interne beginInvoke |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Méthode interne endInvoke |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Méthode invoquée |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Méthode interne beginInvoke

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Méthode interne endInvoke

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Méthode invoquée
