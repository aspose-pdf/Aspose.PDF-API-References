---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form classe. La classe che rappresenta l'oggetto della forma.
type: docs
weight: 5070
url: /it/net/aspose.pdf.forms/form/
---
## Classe Form

Classe che rappresenta l'oggetto modulo.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Se impostato, tutti i campi del modulo verranno ricalcolati quando viene modificato un campo. Il valore predefinito è true. Impostare su false per aumentare le prestazioni durante la compilazione del modulo con un grande numero di campi calcolati. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Consente di impostare l'ordine di calcolo dei campi. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Ottiene il numero dei campi su questo modulo. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Ottiene o imposta l'aspetto predefinito del modulo (oggetto che descrive il font predefinito, la dimensione del testo e il colore per i campi del modulo). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Ottiene le risorse predefinite collocate su questo modulo. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Se questa proprietà è true, verranno disegnati rettangoli di confine rossi aggiuntivi per i contenitori degli elementi exclGroup richiesti di Xfa. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per l'exclGroup durante la conversione della rappresentazione Xfa dei moduli in standard. È false per impostazione predefinita. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Ottiene l'elenco di tutti i campi nel livello più basso del modulo gerarchico. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Se questa proprietà è true, il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo standard. È false per impostazione predefinita. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Restituisce true se l'oggetto è thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Ottiene il campo del modulo per nome del campo. Genera un'eccezione se il campo non è stato trovato. (2 indicizzatori) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Se questa proprietà è true, il dizionario "Perms" verrà rimosso dal documento pdf dopo la conversione dei documenti dinamici in standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat reader. È false per impostazione predefinita. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Se impostato, il documento contiene firme che possono essere invalidate se il file viene salvato (scritto) in un modo che altera i suoi contenuti precedenti, a differenza di un aggiornamento incrementale. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Se impostato, il documento contiene almeno un campo firma. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Restituisce l'oggetto di sincronizzazione. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Ottiene il tipo del modulo. I valori possibili sono: Standard, Statico, Dinamico. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Ottiene i dati XFA del modulo (se presenti). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Aggiunge un campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Aggiunge un campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Aggiunge un nuovo campo al modulo; se questo campo è già presente su un altro modulo o su questo modulo, viene creata una copia del campo. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento nella posizione specificata. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Imposta l'XFA del modulo al valore specificato. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Copia i campi collocati nel modulo in un array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Elimina un campo dal modulo. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Elimina un campo dal modulo per nome. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Esporta i campi del modulo PDF in formato JSON e scrive il risultato nel file specificato. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Rimuove tutti i campi del modulo e posiziona i loro valori direttamente sulla pagina. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Ottiene l'enumerazione dei campi del modulo. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Restituisce i campi all'interno del rettangolo specificato. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Controlla se il modulo ha già il campo specificato. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Determina se il campo con il nome specificato è già stato aggiunto al modulo. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Determina se il campo con il nome specificato è già stato aggiunto al modulo, con la possibilità di esaminare la gerarchia dei campi figli. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importa i campi del modulo PDF dal formato JSON fornito nello stream. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importa i campi del modulo PDF dal formato JSON fornito nel file specificato. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Rende le annotazioni dei campi del modulo indipendenti. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Rimuove l'aspetto del campo all'indice specificato. Se rimane solo un aspetto figlio, il metodo lo incorpora nel campo. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad esempio, durante la conversione del modulo XFA in modulo standard) se il modulo risultante deve essere visualizzato come firmato o non firmato. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Classe che descrive le impostazioni per la procedura di appiattimento del modulo. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | I moduli possono contenere informazioni di firma e possono essere firmati o non firmati. A volte la visualizzazione dei moduli nel visualizzatore deve dipendere dal fatto che il modulo sia firmato o meno. Questo enum elenca i possibili modi di rendering durante la conversione del tipo di modulo in relazione alla firma. |

### Vedi anche

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)