---
title: "ReplaceText"
second_title: "Aspose.PDF pour Go via C++"
description: "Remplacer le texte dans le PDF-document."
type: docs
url: /fr/go-cpp/organize/replacetext/
---

_Remplacer le texte dans un document PDF._

```go
func (document *Document) ReplaceText(findText, replaceText string) error
```

**Parameters**: 
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

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
	// ReplaceText(findText, replaceText string) remplace le texte dans un document PDF
	err = pdf.ReplaceText("PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
