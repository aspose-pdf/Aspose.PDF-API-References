---
title: "PageToPdf"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée en tant que Pdf."
type: docs
url: /fr/go-cpp/convert/pagetopdf/
---

_Convertir et enregistrer la page spécifiée en PDF._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageToPdf(num int32, filename string) enregistre la page spécifiée en fichier PDF
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
