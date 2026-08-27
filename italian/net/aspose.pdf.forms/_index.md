---
title: "Aspose.Pdf.Forms"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Lo spazio dei nomi Aspose.Pdf.Forms contiene classi che descrivono lo standard dei moduli statici, dinamici e vari tipi di campi come casella di testo, casella di riepilogo, pulsante radio, ecc."
type: docs
weight: 110
url: /it/net/aspose.pdf.forms/
---
Lo spazio dei nomi **Aspose.Pdf.Forms** contiene classi che descrivono i moduli (standard, statici, dinamici) e vari tipi di campi come casella di testo, casella di riepilogo, pulsante radio, ecc.

## Classi

| Classe | Descrizione |
| --- | --- |
| [BarcodeField](./barcodefield/) | Classe che rappresenta il campo codice a barre. |
| [ButtonField](./buttonfield/) | Classe che rappresenta il campo pulsante. |
| [CheckboxField](./checkboxfield/) | Classe che rappresenta il campo casella di controllo. |
| [ChoiceField](./choicefield/) | Rappresenta la classe base per i campi di scelta. |
| [ComboBoxField](./comboboxfield/) | Classe che rappresenta il campo combobox del modulo. |
| [DateField](./datefield/) | Campo data con visualizzazione calendario. |
| [DocMDPSignature](./docmdpsignature/) | Rappresenta la classe del tipo di firma MDP (rilevamento e prevenzione delle modifiche) del documento. |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7 distaccata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili. |
| [Field](./field/) | Classe base per i campi del modulo acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo per l'elemento casella di selezione file. |
| [Form](./form/) | Classe che rappresenta l'oggetto modulo. |
| [IconFit](./iconfit/) | Descrive come l'icona dell'annotazione widget deve essere visualizzata all'interno del suo rettangolo di annotazione. |
| [ListBoxField](./listboxfield/) | Classe che rappresenta il campo ListBox. |
| [NumberField](./numberfield/) | Campo di testo con caratteri validi specificati. |
| [Option](./option/) | Classe che rappresenta l'opzione di un campo di scelta. |
| [OptionCollection](./optioncollection/) | Classe che rappresenta la raccolta di opzioni del campo di scelta. |
| [PasswordBoxField](./passwordboxfield/) | Classe che descrive il campo di testo per l'inserimento della password. |
| [PKCS1](./pkcs1/) | Rappresenta l'oggetto firma relativo allo standard PKCS#1. L'algoritmo di crittografia RSA e il metodo di digest SHA-1 sono utilizzati per la firma. |
| [PKCS7](./pkcs7/) | Rappresenta l'oggetto PKCS#7 che conforma alla specifica PKCS#7 nell'Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Versione 1.5. Il `SHA1 digest` del byte range del Document è incapsulato nel campo SignedData di PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Rappresenta l'oggetto PKCS#7 che conforma alla specifica PKCS#7 nell'Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Versione 1.5. Il digest originale del messaggio firmato sul byte range del Document è incorporato come campo SignedData normale di PKCS#7. Nessun dato deve essere incapsulato nel campo SignedData di PKCS#7. |
| [RadioButtonField](./radiobuttonfield/) | Classe che rappresenta il campo pulsante radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe che rappresenta l'elemento del campo RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | Classe che descrive il componente editor di testo formattato. |
| [Signature](./signature/) | Una classe astratta che rappresenta l'oggetto firma nel pdf Document. Le firme sono campi con valori di oggetti firma, quest'ultimo contiene dati utilizzati per verificare la validità del Document. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una classe astratta che rappresenta l'oggetto di aspetto personalizzato della firma. |
| [SignatureField](./signaturefield/) | Rappresenta il campo modulo firma. |
| [SignHash](./signhash/) | Delegato per la firma personalizzata dell'hash del documento. |
| [TextBoxField](./textboxfield/) | Classe che rappresenta il campo casella di testo. |
| [XFA](./xfa/) | Rappresenta il modulo XML relativo all'XML Forms Architecture (XFA). |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [BoxStyle](./boxstyle/) | Rappresenta gli stili per il disegno del segno di spunta nella casella di controllo. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Le autorizzazioni di accesso concesse per questo Document. I valori validi sono: 1 - Non sono consentite modifiche al Document; qualsiasi modifica al Document invalida la firma. 2 - Le modifiche consentite sono la compilazione di moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma. 3 - Le modifiche consentite sono le stesse della 2, oltre alla creazione, eliminazione e modifica di Annotation; altre modifiche invalidano la firma. |
| [FormType](./formtype/) | Enumerazione dei possibili tipi di Acro Form. |
| [IconCaptionPosition](./iconcaptionposition/) | Descrive la posizione dell'icona. |
| [ScalingMode](./scalingmode/) | Il tipo di ridimensionamento da utilizzare. |
| [ScalingReason](./scalingreason/) | Le circostanze in cui l'icona deve essere ridimensionata all'interno del Rectangle di Annotation. |
| [SubjectNameElements](./subjectnameelements/) | L'enumerazione descrive gli elementi nella stringa oggetto della firma. |
| [Symbology](./symbology/) | Una simbologia (Barcode) definisce i dettagli tecnici di un particolare tipo di codice a barre: la larghezza delle barre, il set di caratteri, il metodo di codifica, le specifiche del checksum, ecc. |


