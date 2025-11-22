---
title: "CharacterCount"
second_title: Aspose.PDF for Go via C++
description: "Return character count in PDF-document."
type: docs
url: /go-cpp/core/charactercount/
---

_Return character count in PDF-document._

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
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// CharacterCount() returns character count in PDF-document
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
