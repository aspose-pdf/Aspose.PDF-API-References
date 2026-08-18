---
title: "clear_meta_info"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus semua nilai meta informasi dari PDF-document."
type: docs
url: /id/rust-cpp/core/clear_meta_info/
---

_Menghapus semua nilai meta informasi dari PDF-document._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Hapus semua nilai meta informasi dari PDF-document
    pdf.clear_meta_info()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```