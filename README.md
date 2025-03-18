# Phase-2-Week-1

# JavaScript Week 1: Events, DOM, CSS Framework

## 1. JavaScript Events

### Penjelasan
Event adalah kejadian yang terjadi pada halaman web, seperti klik tombol, perubahan input, atau pemuatan halaman. JavaScript dapat digunakan untuk menangani event dengan menambahkan event listener ke elemen HTML.

### Contoh Penggunaan
#### Menggunakan `addEventListener()`
```javascript
document.getElementById("myButton").addEventListener("click", function() {
    alert("Button diklik!");
});
```

#### Menggunakan Event di HTML
```html
<button onclick="showMessage()">Klik Saya</button>
<script>
function showMessage() {
    alert("Halo, ini event handler!");
}
</script>
```

---

## 2. Document Object Model (DOM)

### Penjelasan
DOM adalah representasi struktur halaman web dalam bentuk pohon yang dapat diakses dan dimodifikasi dengan JavaScript.

### Contoh Penggunaan
#### Mengubah Konten Elemen
```javascript
document.getElementById("myText").innerText = "Teks telah diubah!";
```

#### Mengubah Gaya Elemen
```javascript
document.getElementById("myText").style.color = "red";
```

#### Menambahkan Elemen Baru
```javascript
let newElement = document.createElement("p");
newElement.innerText = "Paragraf baru!";
document.body.appendChild(newElement);
```

---

## 3. CSS Framework

### Penjelasan
CSS Framework seperti Bootstrap dan Tailwind digunakan untuk mempercepat pengembangan tampilan web dengan menyediakan kelas CSS siap pakai.

### Contoh Penggunaan
#### Menggunakan Bootstrap
Tambahkan Bootstrap ke halaman HTML:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
```
Lalu gunakan kelas Bootstrap:
```html
<button class="btn btn-primary">Tombol Bootstrap</button>
```

#### Menggunakan Tailwind CSS
Tambahkan Tailwind CSS:
```html
<script src="https://cdn.tailwindcss.com"></script>
```
Gunakan kelas Tailwind:
```html
<button class="bg-blue-500 text-white px-4 py-2 rounded">Tombol Tailwind</button>
```

---

## 4. Assignment

### Tugas 1: Event Handling
Buat halaman HTML dengan tombol yang saat diklik akan mengubah warna background halaman.

### Tugas 2: Manipulasi DOM
Buat halaman HTML yang memiliki paragraf. Tambahkan tombol untuk mengubah teks paragraf tersebut saat diklik.

### Tugas 3: Menggunakan CSS Framework
Gunakan Bootstrap atau Tailwind untuk membuat tombol yang terlihat menarik.

Selamat belajar! 🚀

