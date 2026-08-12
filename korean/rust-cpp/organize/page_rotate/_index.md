---
title: "page_rotate"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서에서 페이지를 회전합니다."
type: docs
url: /ko/rust-cpp/organize/page_rotate/
---

_PDF 문서에서 페이지를 회전합니다._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지 회전
    pdf.page_rotate(1, Rotation::On180)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```