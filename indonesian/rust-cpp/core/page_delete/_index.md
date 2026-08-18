---
title: "page_delete"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus halaman yang ditentukan dari dokumen PDF."
type: docs
url: /id/rust-cpp/core/page_delete/
---

_Menghapus halaman yang ditentukan dari dokumen PDF._

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
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Hapus halaman yang ditentukan dalam dokumen PDF
    pdf.page_delete(1)?;

    // Simpan PDF-document yang sebelumnya dibuka
    pdf.save()?;

    Ok(())
}

```