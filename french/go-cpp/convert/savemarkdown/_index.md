---
title: "EnregistrerMarkdown"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format Markdown-document."
type: docs
url: /fr/go-cpp/convert/savemarkdown/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en tant que document Markdown._

```go
func (document *Document) SaveMarkdown(filename string) error
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
	// SaveMarkdown(filename string) enregistre le PDF-document précédemment ouvert en tant que document Markdown avec le nom de fichier
	err = pdf.SaveMarkdown("sample.md")
	if err != nil {
		log.Fatal(err)
	}
}
```
