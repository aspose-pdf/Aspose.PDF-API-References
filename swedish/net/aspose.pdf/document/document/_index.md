---
title: "Document.Document"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-konstruktor. Initierar en ny Document-instans från indataströmmen"
type: docs
weight: 10
url: /sv/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| lösenord | String | Användar- eller ägarlösenord. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| certOptions | CertificateEncryptionOptions | Certifikatkrypteringsalternativen. |

### Se även

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| certOptions | CertificateEncryptionOptions | Certifikatkrypteringsalternativen. |
| isManagedStream | Boolean | Om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| certOptions | CertificateEncryptionOptions | Certifikatkrypteringsalternativen. |

### Se även

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| certOptions | CertificateEncryptionOptions | Certifikatkrypteringsalternativen. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| lösenord | String | Användar- eller ägarlösenord. |
| customSecurityHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

### Se även

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| lösenord | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | Om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

Initiera en ny Document-instans från *input*-strömmen.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| lösenord | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | Om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |
| customSecurityHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

### Se även

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

Initiera bara Document med *filnamn*. Samma som `Document`.

```csharp
public Document(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Namnet på pdf-dokumentfilen. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

Initiera bara Document med *filnamn*. Samma som `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Namnet på pdf-dokumentfilen. |
| isManagedStream | Boolean | Om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| lösenord | String | Användar- eller ägarlösenord. |
| customSecurityHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

### Se även

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| lösenord | String | Användar- eller ägarlösenord. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| lösenord | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

Initierar en ny instans av klassen [`Document`](../) för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| lösenord | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |
| customSecurityHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

### Se även

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Initierar ett tomt dokument.

```csharp
public Document()
```

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Initierar ett tomt dokument efter version.

```csharp
public Document(PdfVersion version)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | PdfVersion | PDF-versionen. |

### Se även

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

Öppnar ett befintligt document från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få pdf document.

```csharp
public Document(string filename, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Indatafil för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *filename* till pdf-dokument. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Öppnar ett befintligt dokument från en ström som tillhandahåller nödvändig konvertering för att få PDF-dokument.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Indataström för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *input* till pdf-dokument. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


