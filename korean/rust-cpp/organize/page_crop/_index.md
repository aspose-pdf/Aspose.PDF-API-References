---
title: "page_crop"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지를 자릅니다."
type: docs
url: /ko/rust-cpp/organize/page_crop/
---

_페이지를 자릅니다._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지를 자르기
    pdf.page_crop(1, 1.0)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```