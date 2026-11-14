# Kelas IP Address

## 1. Pengertian Kelas IP Address

Kelas IP Address adalah pembagian alamat IPv4 berdasarkan rentang alamat dan kebutuhan jaringan. Secara tradisional, IPv4 dibagi menjadi lima kelas, yaitu A, B, C, D, dan E.

## 2. Jenis-Jenis Kelas IP Address

### A. Kelas A

- Rentang alamat: 1.0.0.0 – 126.255.255.255
- Subnet mask default: 255.0.0.0
- Prefix: /8
- Digunakan untuk jaringan berskala besar.

### B. Kelas B

- Rentang alamat: 128.0.0.0 – 191.255.255.255
- Subnet mask default: 255.255.0.0
- Prefix: /16
- Digunakan untuk jaringan berskala menengah.

### C. Kelas C

- Rentang alamat: 192.0.0.0 – 223.255.255.255
- Subnet mask default: 255.255.255.0
- Prefix: /24
- Digunakan untuk jaringan berskala kecil.

### D. Kelas D

- Rentang alamat: 224.0.0.0 – 239.255.255.255
- Digunakan untuk komunikasi multicast.

### E. Kelas E

- Rentang alamat: 240.0.0.0 – 255.255.255.255
- Dicadangkan untuk keperluan eksperimen dan penelitian.

## 3. Tabel Kelas IP Address

| Kelas | Rentang Oktet Pertama | Prefix Default |
|---|---|---|
| A | 1–126 | /8 |
| B | 128–191 | /16 |
| C | 192–223 | /24 |
| D | 224–239 | - |
| E | 240–255 | - |

Catatan: Alamat 127.x.x.x digunakan untuk loopback, sedangkan 0.x.x.x memiliki penggunaan khusus.

## 4. Contoh Kelas IP Address

- 10.0.0.1 termasuk kelas A.
- 172.16.0.1 termasuk kelas B.
- 192.168.1.1 termasuk kelas C.
- 224.0.0.1 termasuk kelas D.

## 5. Kesimpulan

Kelas IP Address merupakan pembagian alamat IPv4 secara tradisional berdasarkan kebutuhan dan fungsi jaringan. Pemahaman kelas IP membantu mempelajari dasar pengalamatan jaringan sebelum memahami Subnetting.
