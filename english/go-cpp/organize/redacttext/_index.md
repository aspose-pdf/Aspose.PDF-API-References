---
title: "RedactText"
second_title: Aspose.PDF for Go via C++
description: "Redact permanently and blacks out sensitive text in PDF-document"
type: docs
url: /go-cpp/organize/redacttext/
---

_Redact permanently and blacks out sensitive text in PDF-document._

```go
func (document *Document) RedactText(searchPattern string) error
```

**Parameters**: 
  * **searchPattern** - regular expression (regex, C#-like syntax) pattern used to search

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
	// RedactText(searchPattern string) redacts permanently and blacks out sensitive text in PDF-document
	err = pdf.RedactText("aspose|pdf")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_RedactText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
