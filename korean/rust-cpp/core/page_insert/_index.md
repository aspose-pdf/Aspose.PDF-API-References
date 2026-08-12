---
title: "page_insert"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 지정된 위치에 새 페이지를 삽입합니다."
type: docs
url: /ko/rust-cpp/core/page_insert/
---

_PDF-document의 지정된 위치에 새 페이지를 삽입합니다._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document의 지정된 위치에 새 페이지를 삽입합니다
    pdf.page_insert(1)?;

    // 이전에 열었던 PDF-document를 저장합니다
    pdf.save()?;

    Ok(())
}

```