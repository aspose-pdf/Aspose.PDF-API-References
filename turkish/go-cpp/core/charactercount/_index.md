---
title: "CharacterCount"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dökümanındaki karakter sayısını döndür."
type: docs
url: /tr/go-cpp/core/charactercount/
---

_PDF belgesindeki karakter sayısını döndür._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// CharacterCount() PDF belgesindeki karakter sayısını döndürür
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
