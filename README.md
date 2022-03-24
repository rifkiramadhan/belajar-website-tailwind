# CSS Tailwind

## Keterangan

### Menurut

- https://tailwindcss.com
  - "A Utility-first CSS Framwork that packed with classes"
    - Sebuah utility first framework yang di dalam nya terdapat banyak sekali class2 yang tentu saja dapat digunakan
    - Jadi utility first adalah suatu component yang di dalamnya hanya ada utility2 nya saja atau tidak ada satu class yang di dalamnya banyak CSS
  
  - "Rapidly build modern website without ever leaving your HTML"
    - Sebuah framework yang dapat membuat kita dengan cepat membangun website yang modern
    - Jadi semuanya bisa kita buat tanpa meninggalkan codingan HTML kita, jadi kita bahkan tidak perlu menyentuh file CSS
    - Karena semua utility CSS nya sudah menjadi class di HTML

  - CSS Utility Classes and "Separation of Concenrs"
    - Membuat CSS secara Terpisah

### Fase Pembuatan Tailwind CSS

- Fase 1: "Semantic CSS"
  - Dimana kita memberikan makna terhadap code kita
- Fase 2: "Decoupling' style from structure
  - Memisahkan style dari struktur
  - Block
    - Adalah element2 yang secara entitas itu berdiri sendir dan memiliki makna sendiri
      - header, container, menu, checkbox, input
  - Element
    - Adalah bagian dari block yang tidak memiliki arti tersendiri dan secara semantic terikat ke dalam block nya
      - menu item, list item, checkbox caption, header title
  - Modifier
    - Untuk memodifikasi elemen pada tiap keadaan
      - disabled, highlighted, checked, fixed, size big, color yellow
- Fase 3: "Content-agnostic CSS components"
  - Komponen CSS yang tidak bergantung pada konten
- Fase 4: "Content-agnostic CSS components + Utility classes"
  - Jadi modifier2 yang sama ditarik menjadi sebuah utility class
- Fase 5: "Utility-first class"
  - Semua component dibangun dari utility2 class yang tersedia
  - Supaya jika ada beragam notifikasi kita hanya membongkar pasang utility2 class nya saja

### Utilities

- Preflight
  - Digunakan untuk mereset property2 default yang ada didalam element2 HTML, jadi sudah ada bawaan reset nya sendiri
- Layout
  - Desain Website
- Flexbox
  - Margin dan pading
- Spacing & Sizing
  - Width & Height
- Typography
  - Untuk mengatur font
- Background & Borders
- Effect & Filters
- Transition, Transformation & Animation
- Tables

### Features

- Interactivity
  - Jadi kita bisa memberikan interaksi pada element kita menggunakan utility class
- Responsive Design
  - Merancang halaman untuk utility class nya
- Dark Mode
  - Dapat dengan mudah menambahkan Dark Mode untuk aplikasi kita
- Reusability
  - Untuk membuat element2 yang akan di jadikan sebuah component yang akan di pakai berulang kali, maka fitur ini akan bisa membantu kita
- Costom Style
  - Dan kalau styling belum cukup untuk kebutuhan kita, kita dapat memberikan style costom kita sendiri dengan cukup mudah
- Functions & Directives
  - Kita bisa menggunakan function dan directives karea tailwind menggunakan preprocessor di dalamnya sama seperti kita menggunakan SASS

### Interactivity

- Pseudo-classes
  - hover, focus, acive, first, latest
- Pseudo-element
  - before, after, placeholder, file, selection

### Pre-Requise

- HTML
- CSS
- Bootstrap
- CSS Pre-processor
- NPM

### Software Requirements

- Web Browser: Google Chrome
- Code Editor: Visual Studio Code
- VSCodeExtension: Tailwind CSS IntelliSense, Live Preview, PostCSS Language Support
- Package Manager: NPM (Node.js)
