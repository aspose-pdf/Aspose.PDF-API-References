---
title: "PageMergeLayers"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します。"
type: docs
url: /ja/go-cpp/organize/pagemergelayers/
---

_ページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します。_

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
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// PageMergeLayers(num int32, newLayerName string) はページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
