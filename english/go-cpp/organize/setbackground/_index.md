---
title: "SetBackground"
second_title: Aspose.PDF for Go via C++
description: "Set PDF-document background color."
type: docs
url: /go-cpp/organize/setbackground/
---

_Set PDF-document background color._

```go
func (document *Document) SetBackground(r, g, b int32) error
```

**Parameters**: 
  * **r** - Red color of RGB color model (0-255)
  * **g** - Green color of RGB color model (0-255)
  * **b** - Blue color of RGB color model (0-255)

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
	// SetBackground(r, g, b int32) sets PDF-document background color
	err = pdf.SetBackground(200, 100, 101)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_SetBackground.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
