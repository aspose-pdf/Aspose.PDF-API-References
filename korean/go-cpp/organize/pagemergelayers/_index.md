---
title: "PageMergeLayers"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어로 병합합니다."
type: docs
url: /ko/go-cpp/organize/pagemergelayers/
---

_페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어에 병합합니다._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// PageMergeLayers(num int32, newLayerName string) 은 페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어에 병합합니다
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
