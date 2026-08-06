---
title: "page_delete"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서에서 지정된 페이지를 삭제합니다."
type: docs
url: /ko/rust-cpp/core/page_delete/
---

_PDF 문서에서 지정된 페이지를 삭제합니다._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // PDF 문서에서 지정된 페이지를 삭제합니다
    pdf.page_delete(1)?;

    // 이전에 열었던 PDF-document를 저장합니다
    pdf.save()?;

    Ok(())
}

```