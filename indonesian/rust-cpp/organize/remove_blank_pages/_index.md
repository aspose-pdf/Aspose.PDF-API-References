---
title: "remove_blank_pages"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus halaman kosong dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_blank_pages/
---

_Menghapus halaman kosong dari dokumen PDF._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Hapus halaman kosong dari PDF-document
    pdf.remove_blank_pages()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```