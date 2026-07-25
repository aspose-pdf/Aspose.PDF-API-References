---
title: "ExtractText"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le contenu du document PDF en texte brut."
type: docs
url: /fr/go-cpp/core/extracttext/
---

_Retourner le contenu du PDF-document en texte brut._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// ExtractText() renvoie le contenu du PDF-document en texte brut
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
