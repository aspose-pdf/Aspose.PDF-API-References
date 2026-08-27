---
title: "PdfFileSecurity"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa el cifrado o descifrado de un archivo Pdf con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña."
type: docs
weight: 300
url: /es/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Representa el cifrado o descifrado de un archivo Pdf con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña.

El tipo PdfFileSecurity expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Inicializa una nueva instancia de la clase PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Inicializa una nueva instancia de la clase PdfFileSecurity |
| PdfFileSecurity() | Inicializa el objeto PdfFileSecurity. |
| PdfFileSecurity(document) | Inicializa una nueva instancia de la clase PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Inicializa una nueva instancia de la clase PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Inicializa una nueva instancia de la clase PdfFileSecurity |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| allow_exceptions | Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de error y la última excepción puede verificarse con la propiedad LastException. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Inicializa la fachada. |
| bind_pdf(src_stream) | Inicializa la fachada. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el documento PDF en el archivo especificado. |
| save(dest_stream) | Guarda el documento PDF en el flujo especificado. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Cifra el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios del documento para el acceso.<br/>            La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada <br/>            por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía.<br/>            Lanza una excepción si el proceso falla. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Cifra el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios del documento para el acceso.<br/>            La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada <br/>            por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía.<br/>            Existen 6 combinaciones posibles de los valores KeySize y Algorithm. <br/>            Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se generará la <br/>            excepción correspondiente si el kit encuentra esta combinación.<br/>            Lanza una excepción si el proceso falla. |
| set_privilege(privilege) | Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías.<br/>            La contraseña de propietario será añadida mediante una cadena aleatoria.<br/>            Lanza una excepción si el proceso falla. |
| set_privilege(user_password, owner_password, privilege) | Establece la seguridad del archivo Pdf con la contraseña original.<br/>            Lanza una excepción si el proceso falla. |
| change_password(owner_password, new_user_password, new_owner_password) | Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, manteniendo la configuración de seguridad original.<br/>             La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada <br/>             por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía.<br/>             Lanza una excepción si el proceso falla. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf.<br/>            La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada <br/>            por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía.<br/>            Lanza una excepción si el proceso falla. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf.<br/> La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada <br/> por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía.<br/> Hay 6 combinaciones posibles de valores de KeySize y Algorithm. <br/> Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y la excepción correspondiente <br/> se lanzará si el kit encuentra esta combinación.<br/> Lanza una excepción si el proceso falla. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Cambia la contraseña de usuario y la contraseña del propietario mediante la contraseña del propietario, mantiene la configuración de seguridad original.<br/> La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada <br/> No lanza una excepción si el proceso falla.<br/> con una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf.<br/> La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada <br/> por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía.<br/> No lanza una excepción si el proceso falla. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf.<br/> La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada <br/> por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía.<br/> Hay 6 combinaciones posibles de valores de KeySize y Algorithm. <br/> Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y la excepción correspondiente <br/> se lanzará si el kit encuentra esta combinación.<br/> No lanza una excepción si el proceso falla. |
| close() | Cierra la fachada. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Encripta el archivo Pdf con la contraseña de usuario y la contraseña del propietario y establece los privilegios del documento para el acceso.<br/> La contraseña de usuario y la contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada <br/> por una cadena aleatoria si la contraseña del propietario de entrada es nula o vacía.<br/> No lanza una excepción si el proceso falla. |
| decrypt_file(owner_password) | Descifra un documento Pdf cifrado mediante la contraseña del propietario. <br/> Si el documento no tiene contraseña del propietario, se permite usar la contraseña de usuario.<br/> Lanza una excepción si el proceso falla. |
| try_decrypt_file(owner_password) | Descifra un documento Pdf cifrado mediante la contraseña del propietario. <br/> Si el documento no tiene contraseña del propietario, se permite usar la contraseña de usuario.<br/> No lanza una excepción si el proceso falla. |
| try_set_privilege(user_password, owner_password, privilege) | Establece la seguridad del archivo Pdf con la contraseña original.<br/> No lanza una excepción si el proceso falla. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

