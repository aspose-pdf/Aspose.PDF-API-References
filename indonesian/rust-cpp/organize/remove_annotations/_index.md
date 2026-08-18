---
title: "remove_annotations"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus anotasi dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_annotations/
---

_Menghapus anotasi dari dokumen PDF._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Hapus anotasi dari PDF-document
    pdf.remove_annotations()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```