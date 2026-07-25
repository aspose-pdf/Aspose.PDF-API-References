---
title: "RemoveSigns"
second_title: "Aspose.PDF per Go via C++"
description: "Rimuovi le firme dal documento PDF."
type: docs
url: /it/go-cpp/security/removesigns/
---

_Rimuovi le firme dal documento PDF._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// RemoveSigns(filename string) rimuove le firme dal documento PDF
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
