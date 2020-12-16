# ResponsiKey
Program  ini berguna untuk menambahkan menu yang kita pilih dan menghitung totalnya mirip dengan the cashier kemarin tetapi dengan tamilan yang berbeda
program ini dibuat untuk melanjutkan pembelajaran MVC sekaligus untuk jawaban Responsi sebelum UTS bulan lalu.
## Fitur
- dapat menambah dan menghapus menu yang terpilih
- terdapat pop up pilihan menu
## Class Diagram
![Class Diagram](https://github.com/hafit0/ResponsiKey/blob/main/ClassDiagram1.png)
## Penjelasan
Class yang terdapat dalam **folder Model** yaitu `Item.cs` `KeranjangBelanja.cs` dan `Payment.cs`. 
- class `Item.cs` digunakan untuk get dan set dari nama item dan harganya. 
- class `Payment.cs` digunakan untuk mengatur logika  dari saldo OnO nya.
- class `KeranjangBelanja.cs` digunakan untuk menampung item, menghapus item, menambah item, dan menghitung sub total.

Class yang terdapat pada **folder Controller** yang digunakan untuk mengatur logika yaitu `MainWindowController.cs` dan `PenawaranController.cs`.
- Class `MainWindowController.cs` mengatur logika menambah dan menghapus item.
- Class `PenawaranController.cs`mengatur logika menu apa saja yang ada.

Kemudian Ada class `MainWindow.xml.cs` dan `Penawaran.xml.cs`. 
- `MainWindow.xml.cs`  berfungsi untuk mengatur tampilan awalnya, item yang dipilih dan lainnya kemudian ada pop up nya juga.
- `Penawaran.xml.cs` berfungsi untuk mengatur tampilan dari pop up nya.
