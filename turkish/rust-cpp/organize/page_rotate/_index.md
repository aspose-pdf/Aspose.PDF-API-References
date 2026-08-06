---
title: "page_rotate"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandaki bir sayfayı döndürür."
type: docs
url: /tr/rust-cpp/organize/page_rotate/
---

_PDF-dokümandaki bir sayfayı döndürür._

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
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfayı döndür
    pdf.page_rotate(1, Rotation::On180)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```