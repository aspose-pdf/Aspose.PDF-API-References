---
title: "CharacterCount"
second_title: "Aspose.PDF per Go via C++"
description: "Restituisce il conteggio dei caratteri nel documento PDF."
type: docs
url: /it/go-cpp/core/charactercount/
---

_Restituisce il conteggio dei caratteri nel PDF-document._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// CharacterCount() restituisce il conteggio dei caratteri nel PDF-document
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
