---
title: "page_rotate"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memutar satu halaman dalam dokumen PDF."
type: docs
url: /id/rust-cpp/organize/page_rotate/
---

_Memutar satu halaman dalam dokumen PDF._

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
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Putar halaman
    pdf.page_rotate(1, Rotation::On180)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```