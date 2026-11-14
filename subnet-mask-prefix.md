# Subnet Mask dan Prefix

## 1. Pengertian Subnet Mask

Subnet Mask adalah angka yang digunakan untuk membedakan bagian Network ID dan Host ID pada sebuah alamat IP.

Subnet Mask membantu perangkat mengetahui bagian jaringan dan bagian perangkat dari sebuah IP Address.

## 2. Fungsi Subnet Mask

- Menentukan identitas jaringan.
- Menentukan bagian host pada IP Address.
- Membantu proses pembagian jaringan.
- Membantu perangkat berkomunikasi dalam jaringan yang sama.

## 3. Pengertian Prefix

Prefix adalah penulisan jumlah bit 1 pada Subnet Mask menggunakan tanda garis miring (/).

Contoh:

```text
IP Address  : 192.168.1.10
Subnet Mask : 255.255.255.0
Prefix      : /24
```

## 4. Tabel Subnet Mask dan Prefix

| Prefix | Subnet Mask |
|---|---|
| /8 | 255.0.0.0 |
| /16 | 255.255.0.0 |
| /24 | 255.255.255.0 |
| /25 | 255.255.255.128 |
| /26 | 255.255.255.192 |
| /27 | 255.255.255.224 |
| /28 | 255.255.255.240 |
| /29 | 255.255.255.248 |
| /30 | 255.255.255.252 |
| /32 | 255.255.255.255 |

## 5. Contoh Penggunaan Prefix

Misalnya terdapat IP Address:

```text
192.168.1.10/24
```

Artinya:
- IP Address: 192.168.1.10
- Prefix: /24
- Subnet Mask: 255.255.255.0
- Jumlah alamat dalam satu subnet: 256
- Jumlah alamat host yang dapat digunakan: 254

## 6. Kesimpulan

Subnet Mask dan Prefix merupakan bagian penting dalam pengalamatan jaringan. Keduanya digunakan untuk menentukan pembagian Network ID dan Host ID serta membantu proses Subnetting.
