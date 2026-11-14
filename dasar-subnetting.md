# Dasar-Dasar Subnetting

## 1. Pengertian Subnetting

Subnetting adalah proses membagi sebuah jaringan komputer menjadi beberapa jaringan yang lebih kecil. Tujuannya agar penggunaan alamat IP menjadi lebih teratur dan pengelolaan jaringan lebih mudah.

## 2. Tujuan Subnetting

- Membagi jaringan besar menjadi beberapa jaringan kecil.
- Mengatur penggunaan alamat IP.
- Mengurangi pemborosan alamat IP.
- Mempermudah pengelolaan jaringan.
- Membantu membatasi broadcast dalam jaringan.

## 3. Istilah Penting dalam Subnetting

- **Network Address:** Alamat yang menunjukkan identitas suatu jaringan.
- **Broadcast Address:** Alamat yang digunakan untuk mengirim data ke seluruh perangkat dalam satu subnet IPv4.
- **Host Address:** Alamat IP yang dapat diberikan kepada perangkat.
- **Subnet Mask:** Penanda bagian jaringan dan bagian host.
- **Prefix:** Jumlah bit jaringan yang ditulis menggunakan tanda garis miring.

## 4. Rumus Dasar Subnetting

Beberapa rumus yang sering digunakan:

**Jumlah alamat IP:**

2^(jumlah bit host)

**Jumlah host yang dapat digunakan:**

2^(jumlah bit host) - 2

**Jumlah subnet:**

2^(jumlah bit subnet yang dipinjam)

Catatan: Rumus jumlah host dikurangi 2 berlaku pada subnet IPv4 biasa, bukan untuk kondisi khusus seperti /31 dan /32.

## 5. Contoh Pembagian Subnet

Misalnya terdapat jaringan:

```text
192.168.1.0/24
```

Jaringan tersebut dibagi menjadi dua subnet menggunakan prefix /25.

Hasil pembagiannya:

| Keterangan | Subnet 1 | Subnet 2 |
|---|---|---|
| Network Address | 192.168.1.0 | 192.168.1.128 |
| Host Pertama | 192.168.1.1 | 192.168.1.129 |
| Host Terakhir | 192.168.1.126 | 192.168.1.254 |
| Broadcast | 192.168.1.127 | 192.168.1.255 |
| Prefix | /25 | /25 |

Setiap subnet memiliki 128 alamat IP dan 126 alamat host yang dapat digunakan.

## 6. Manfaat Subnetting

Dengan menggunakan Subnetting, administrator jaringan dapat membagi jaringan berdasarkan kebutuhan, misalnya jaringan untuk ruang guru, laboratorium komputer, dan ruang administrasi.

## 7. Kesimpulan

Subnetting merupakan teknik penting dalam jaringan komputer untuk membagi jaringan menjadi beberapa bagian yang lebih kecil. Dengan memahami Subnetting, pengelolaan alamat IP dapat dilakukan secara lebih efisien dan terstruktur.
