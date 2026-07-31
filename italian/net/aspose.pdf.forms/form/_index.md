---
title: "Classe Form"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Forms.Form classe. Classe che rappresenta l'oggetto modulo."
type: docs
weight: 5190
url: /it/net/aspose.pdf.forms/form/
---
## Form class

Classe che rappresenta l'oggetto modulo.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare su false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Consente di impostare l'ordine di calcolo dei campi. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Ottiene il numero dei campi in questo modulo. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Ottiene o imposta l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Ottiene le risorse predefinite collocate in questo modulo. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Se questa proprietà è true, verranno disegnati rettangoli rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti. Questa proprietà è stata introdotta a causa dell'assenza di analoghi per l'exclGroup durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Ottiene l'elenco di tutti i campi al livello più basso del modulo gerarchico. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | Ottiene un valore che indica se il documento contiene un modulo XFA. Questa proprietà è stata introdotta per determinare se [`IgnoreNeedsRendering`](./ignoreneedsrendering/) deve essere utilizzato per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e [`NeedsRendering`](./needsrendering/) è false. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Se questa proprietà è true, il valore della chiave NeedsRendering verrà ignorato durante la conversione del modulo XFA in modulo Standard. È false per impostazione predefinita. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Restituisce true se l'oggetto è thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Ottiene il campo del modulo per nome del campo. Genera un'eccezione se il campo non è stato trovato. (2 indicizzatori) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | Restituisce un valore che indica se il documento richiede la rimozione del modulo XFA dinamico. Questa proprietà è stata introdotta per determinare se [`IgnoreNeedsRendering`](./ignoreneedsrendering/) deve essere usata per rimuovere il modulo XFA nei casi in cui il modulo XFA è presente e [`NeedsRendering`](./needsrendering/) è false. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Se questa proprietà è true, il dizionario \"Perms\" verrà rimosso dal documento pdf dopo la conversione dei documenti dinamici in standard. Il dizionario \"Perms\" può contenere regole che disturbano la visualizzazione della selezione dei campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in modo da alterare il contenuto precedente, anziché con un aggiornamento incrementale. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Se impostato, il documento contiene almeno un campo firma. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Restituisce l'oggetto di sincronizzazione. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Ottiene i dati XFA del modulo (se presenti). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Aggiunge un campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Aggiunge un campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Aggiunge un nuovo campo al modulo; se questo campo è già posizionato su un altro modulo o su questo, viene creata una copia del campo. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento nella posizione indicata. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Imposta XFA del modulo al valore specificato. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Copia i campi posizionati sul modulo in un array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Elimina il campo dal modulo. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Elimina il campo dal modulo per nome. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Esporta i campi del modulo PDF in formato JSON e scrive il risultato nel file specificato. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Rimuove tutti i campi del modulo e posiziona i loro valori direttamente sulla pagina. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Ottiene l'enumerazione dei campi del modulo. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Restituisce i campi all'interno del rettangolo specificato. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Verifica se il modulo ha già il campo specificato. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Determina se il campo con il nome specificato è già stato aggiunto al modulo. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Determina se il campo con il nome specificato è già stato aggiunto al modulo, con la possibilità di esaminare la gerarchia dei campi figli. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importa i campi del modulo PDF dal formato JSON fornito nello stream. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importa i campi del modulo PDF dal formato JSON fornito nel file specificato. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Rende le annotazioni dei campi modulo indipendenti. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Rimuove l'aspetto del campo all'indice specificato. Se rimane un solo aspetto figlio, il metodo lo incorpora nel campo. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad es. durante la conversione di un modulo XFA in un modulo Standard) se il modulo risultante deve essere renderizzato come firmato o non firmato. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Classe che descrive le impostazioni per la procedura di appiattimento del modulo. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | I moduli possono contenere informazioni di firma e possono essere firmati o non firmati. A volte la visualizzazione dei moduli nel visualizzatore deve dipendere dal fatto che il modulo sia firmato o meno. Questa enumerazione elenca le possibili modalità di rendering durante la conversione del tipo di modulo in relazione alla firma. |

### Vedi anche

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


