---
title: "VerifySigns"
second_title: Aspose.PDF for Go via C++
description: "Verify signs from PDF-document."
type: docs
url: /go-cpp/security/verifysigns/
---

_Verify signs from PDF-document._

```go
func (document *Document) VerifySigns() ([]PdfSignStatus, error)
```

**Parameters**: 

**Return**: 
  * **[]PdfSignStatus** - slice of PdfSignStatus structs, deserialized from a JSON string:
```go
// PdfSignStatus contains status of signature in PDF-document.
type PdfSignStatus struct {
	Name   string     `json:"sign_name"`   // name of signature
	Status SignStatus `json:"sign_status"` // status of signature
}

// Enumeration of possible status of signature.
type SignStatus string
const (
	SignStatusValid    SignStatus = "VALID"    // Status is VALID.
	SignStatusInvalid  SignStatus = "INVALID"  // Status is INVALID.
	SignStatusInactive SignStatus = "INACTIVE" // Status is INACTIVE.
)
```
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
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()

	// VerifySigns() verifies signs from PDF-document
	signs, err := pdf.VerifySigns()
	if err != nil {
		log.Fatal(err)
	}

	// Print signatures with status in the PDF-document
	for _, sign := range signs {
		fmt.Printf("Signature: %s, Status: %s\n", sign.Name, sign.Status)
	}
}
```
