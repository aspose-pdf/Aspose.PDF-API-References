---
title: "ExporterXfdf"
second_title: "Aspose.PDF pour Go via C++"
description: "Exporter le PDF-document précédemment ouvert avec AcroForm vers le format XFDF-document."
type: docs
url: /fr/go-cpp/convert/exportxfdf/
---

_Exporter du PDF-document précédemment ouvert avec AcroForm vers le document XFDF._

```go
func (document *Document) ExportXfdf(filename string) error
```

**Parameters**: 
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
	// ExportXfdf(filename string) exporte du PDF-document précédemment ouvert avec AcroForm vers le document XFDF avec le nom de fichier
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
