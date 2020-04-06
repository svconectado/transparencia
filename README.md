# transparencia
Este repositorio contiene todos los documentos relacionados a temas de transparencia de la iniciativa El Salvador Conectado

Para verificar los archivos y su firmas digitales necesitas el software [GNUPG](https://gnupg.org/).

Importa las llaves públicas de los miembros del Grupo de Coordinación:

```bash
# Llave de mxgxw.alpha@gmail.com
gpg --keyserver keyserver.ubuntu.com --receive-keys e1916f1376e9d7ede6baa11ea6f0f2eac000da4f
```

Verifica los archivos .sig con el siguiente comando:
```bash
gpg --verify README.md.sig
```

Deberías de obtener una salida como la siguiente:
```bash
gpg: assuming signed data in 'README.md'
gpg: Signature made dom 05 abr 2020 21:51:38 +03
gpg:                using DSA key E1916F1376E9D7EDE6BAA11EA6F0F2EAC000DA4F
gpg: Good signature from "Mario Gomez <mxgxw.alpha@gmail.com>" [ultimate]
```
