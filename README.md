# Appunti di Algebra 📘

Questo repository raccoglie gli **appunti di Algebra** del Corso di Laurea in Informatica presso l’Università degli Studi di Napoli *Federico II*.  
Il progetto utilizza una **classe LaTeX personalizzata** (`unina_doc_class.cls`) e un `Makefile` per la compilazione automatica.

---

## 🚀 Come iniziare

### Requisiti
- [LaTeX (TeX Live / MikTeX)](https://www.latex-project.org/get/)
- `make`
- Font presenti nella cartella `fonts/`

### Compilazione
Per generare il PDF degli appunti:
```bash
make build
```

### 📂 Struttura

La repo è organizzata così:
```bash
├── chapters/     # Capitoli suddivisi
├── fonts/        # Font richiesti (link simbolico)
├── pdf/          # Risorse PDF
├── res/          # Risorse aggiuntive
├── sources/      # Risorse comuni (logo, ecc.)
├── index.ist     # Stile indice
├── main.tex      # Documento principale
├── Makefile      # Compilazione automatica
└── unina_doc_class.cls
```
___
### 🤝 Contribuire

Le regole di contribuzione sono spiegate [qui](./CONTRIBUTING.md)
___
### 🛠 Supporto

Se riscontri problemi:

* Apri una Issue su GitHub
* Oppure proponi una Pull Request con la correzione
___
### 📄 Licenza
Questo lavoro è distribuito con licenza Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](./LICENSE).
Puoi usarlo e modificarlo liberamente solo per scopi non commerciali, citando questa repository come fonte e mantenendo la stessa licenza.
