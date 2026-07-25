---
title: "CharacterCount"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le nombre de caractères dans le document PDF."
type: docs
url: /fr/go-cpp/core/charactercount/
---

_Renvoie le nombre de caractères dans le PDF-document._

```go
func (document *Document) CharacterCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - character count of the PDF-document
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
	// CharacterCount() renvoie le nombre de caractères dans le PDF-document
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
