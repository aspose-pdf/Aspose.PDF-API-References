---
title: "PageCharacterCount"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le nombre de caractères sur la page spécifiée du PDF-document."
type: docs
url: /fr/go-cpp/core/pagecharactercount/
---

_Retourner le nombre de caractères sur la page spécifiée du document PDF._

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
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
	// PageCharacterCount(num int32) renvoie le nombre de caractères sur la page spécifiée du document PDF.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count on the first page:", page_character_count)
}
```
