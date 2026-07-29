---
title: "CharacterCount"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera antalet tecken i PDF-dokumentet."
type: docs
url: /sv/go-cpp/core/charactercount/
---

_Returnerar teckenantal i PDF-dokumentet._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// CharacterCount() returnerar teckenantal i PDF-dokumentet
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Character count:", character_count)
}
```
