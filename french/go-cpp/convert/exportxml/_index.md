---
title: "ExportXml"
second_title: "Aspose.PDF pour Go via C++"
description: "Exporter le PDF-document précédemment ouvert avec AcroForm vers le format XML-document."
type: docs
url: /fr/go-cpp/convert/exportxml/
---

_Exporter depuis le PDF-document précédemment ouvert avec AcroForm vers le document XML._

```go
func (document *Document) ExportXml(filename string) error
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
	// ExportXml(filename string) exporte depuis le PDF-document précédemment ouvert avec AcroForm vers le document XML avec filename
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
