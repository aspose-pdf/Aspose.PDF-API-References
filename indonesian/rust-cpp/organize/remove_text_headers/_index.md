---
title: "remove_text_headers"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus header teks dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_text_headers/
---

_Menghapus header teks dari dokumen PDF._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Hapus header teks dari dokumen PDF
    pdf.remove_text_headers()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```