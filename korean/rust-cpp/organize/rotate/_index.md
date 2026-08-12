---
title: "rotate"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서를 회전합니다."
type: docs
url: /ko/rust-cpp/organize/rotate/
---

_PDF 문서를 회전합니다._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서 회전
    pdf.rotate(Rotation::On270)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```