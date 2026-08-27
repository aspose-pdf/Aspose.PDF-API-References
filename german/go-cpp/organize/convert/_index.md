---
title: "Convert"
second_title: "Aspose.PDF für Go über C++"
description: "Ein PDF-Dokument in ein PDF-Dokument mit dem angegebenen PDF-Format konvertieren."
type: docs
url: /de/go-cpp/organize/convert/
---

_Konvertiere ein PDF-Dokument in ein PDF-Dokument mit dem angegebenen PDF-Format._

```go
func (document *Document) Convert(pdfFormat PdfFormat, action ConvertErrorAction) (bool, string, error)
```

**Parameters**: 
  * **pdfFormat** - PDF format:
```go
type PdfFormat int32
const (
	PDF_A_1A      PdfFormat = iota // Pdf/A-1a format.
	PDF_A_1B                       // Pdf/A-1b format.
	PDF_A_2A                       // Pdf/A-2a format.
	PDF_A_3A                       // Pdf/A-3a format.
	PDF_A_2B                       // Pdf/A-2b format.
	PDF_A_2U                       // Pdf/A-2u format.
	PDF_A_3B                       // Pdf/A-3b format.
	PDF_A_3U                       // Pdf/A-3u format.
	V_1_0                          // Adobe version 1.0.
	V_1_1                          // Adobe version 1.1.
	V_1_2                          // Adobe version 1.2.
	V_1_3                          // Adobe version 1.3.
	V_1_4                          // Adobe version 1.4.
	V_1_5                          // Adobe version 1.5.
	V_1_6                          // Adobe version 1.6.
	V_1_7                          // Adobe version 1.7.
	V_2_0                          // ISO Standard PDF 2.0.
	PDF_UA_1                       // PDF/UA-1 format.
	PDF_X_1A_2001                  // PDF/X-1a-2001 format.
	PDF_X_1A                       // PDF/X-1a format.
	PDF_X_3                        // PDF/X-3 format.
	ZUGFeRD                        // ZUGFeRD format.
	PDF_A_4                        // PDF/A-4 format.
	PDF_A_4E                       // PDF/A-4e format.
	PDF_A_4F                       // PDF/A-4f format.
	PDF_X_4                        // PDF/X-4 format.
	PDF_E_1                        // PDF/E-1 (PDF 1.6) format.
)
```
  * **action** - conversion errors action:
```go
// Aufzählung möglicher Aktionen für Konvertierungsfehler.
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

**Return**: 
  * **bool** - contains conversion result
  * **string** - contains conversion log
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()

	// Convert(pdfFormat PdfFormat, action ConvertErrorAction) konvertiert PDF-Dokument zu PDF/A
	ok, logStr, err := pdf.Convert(asposepdf.PDF_A_2A, asposepdf.Delete)
	if err != nil {
		log.Fatal("Convert PDF/A error:", err)
	}

	// Konvertierungsergebnis und vollständiges Protokoll ausgeben
	fmt.Printf("Convert PDF/A result: %v\n", ok)
	fmt.Printf("Convert PDF/A log:\n%s\n", logStr)

	// Konvertiertes PDF-Dokument speichern
	err = pdf.SaveAs("sample_Convert.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
