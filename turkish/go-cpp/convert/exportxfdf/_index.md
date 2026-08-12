---
title: "ExportXfdf"
second_title: "Aspose.PDF for Go via C++"
description: "AcroForm içeren önceden açılmış PDF-dokümanını XFDF-dokümanına dışa aktar."
type: docs
url: /tr/go-cpp/convert/exportxfdf/
---

_AcroForm içeren daha önce açılmış PDF-belgeden XFDF-belgesine dışa aktar._

```go
func (document *Document) ExportXfdf(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// ExportXfdf(filename string) daha önce açılmış PDF-dokümandan AcroForm ile XFDF-dokümana dosya adıyla dışa aktarır
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
