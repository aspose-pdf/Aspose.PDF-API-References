---
title: "SaveNUp"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as N-Up PDF-document."
type: docs
url: /go-cpp/convert/savenup/
---

_Convert and save the previously opened PDF-document as N-Up PDF-document._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// SaveNUp(filename string, columns int32, rows int32) saves previously opened PDF-document as N-Up PDF-document with filename
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
