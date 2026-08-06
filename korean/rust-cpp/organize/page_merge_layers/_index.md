---
title: "page_merge_layers"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어에 병합합니다."
type: docs
url: /ko/rust-cpp/organize/page_merge_layers/
---

_페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어에 병합합니다._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어에 병합
    pdf.page_merge_layers(1, "New Layer Name")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```