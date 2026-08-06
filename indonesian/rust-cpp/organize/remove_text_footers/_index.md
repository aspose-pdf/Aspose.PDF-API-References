---
title: "remove_text_footers"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus footer teks dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_text_footers/
---

_Menghapus footer teks dari dokumen PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Hapus footer teks dari dokumen PDF
    pdf.remove_text_footers()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```