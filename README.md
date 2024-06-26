# Laporan Resmi Praktikum Jaringan Komputer Modul 4 Kelompok IT19

| NRP | Nama Anggota |
|-----|--------------|
| 5027221061 | Hafiz Akmaldi Santosa |
| 5027221049 | Arsyad Rizantha Maulana Salim |

## Keterangan
- Subnetting & Routing Classless (CIDR) menggunakan Cisco Packet Tracer (CPT)
- Subnetting & Routing Classless (VLSM) menggunakan GNS3
- Prefix IP 10.73

## Topology
### Cisco Packet Tracer (CPT)
![CPT](https://github.com/HafizSantosa/Jarkom-Modul-4-IT19-2024/blob/main/images/topology.png)

### GNS3
![](https://cdn.discordapp.com/attachments/1021585230844395580/1248993734063030323/25acb7d0-3e11-4b62-8c47-70d2960686a5.png?ex=6665af8f&is=66645e0f&hm=d5379d71c9df87b8da5cedf05a8d32a43cc0956eed1b9570eaed3264e6bc9fb6&)

## VLSM - GNS3
VLSM atau Variable Length Subnet Mask adalah sebuah metode dalam desain jaringan yang memungkinkan penggunaan lebih efisien dari alamat IP dengan memberikan subnet mask yang berbeda-beda pada subnet yang berbeda dalam jaringan yang sama.

Tradisionalnya, dalam subnetting, subnet mask yang sama diterapkan ke seluruh jaringan, yang berarti setiap subnet akan memiliki jumlah host yang sama. Namun, dengan VLSM, subnet mask disesuaikan untuk setiap subnet sesuai dengan jumlah host yang dibutuhkan di dalamnya. Hal ini memungkinkan untuk mengoptimalkan penggunaan alamat IP dan menghindari pemborosan alamat IP.

## Pembagian IP
Pembagian IP dilakukan berdasarkan subnet yang telah ditentukan pada Topologi.

![](https://cdn.discordapp.com/attachments/1021585230844395580/1248995334437212233/image.png?ex=6665b10c&is=66645f8c&hm=ebae5251787d556bb6a4447f8f310d474c17fc71c8187df0de3d17ce29ff5beb&)

## IP Tree
Tree nya sendiri belum selesai jadi kami kumpulkan seadanya.
![](https://cdn.discordapp.com/attachments/1021585230844395580/1249008641726742558/Tree20VLSM201.png?ex=6665bd71&is=66646bf1&hm=86f756392200a904a259f63ca298422a20c216798ecfbf5a31d474dc45b0ffb5&)

## CIDR - CPT

![alt text](images/topology.png)

### Pembagian IP

Berikut merupakan hasil pembagian dari topology yang ada.

![alt text](<images/Sub A.png>) ![alt text](<images/Sub B.png>) ![alt text](<images/Sub C.png>) ![alt text](<images/Sub D.png>) ![alt text](<images/Sub E.png>) ![alt text](<images/Sub F.png>) ![alt text](<images/Sub G.png>) ![alt text](<images/Sub H.png>) ![alt text](<images/Sub I.png>) ![alt text](<images/Sub J.png>)
![alt text](<images/Pembagian CIDR.png>)
dan berikut merupakan tree hasil pembagian IP dari penggabungan yang dilakukan.

![alt text](images/Flowcharts.png)
![images/Pembagian IP CIDR.png](<images/Pembagian IP CIDR.png>)
