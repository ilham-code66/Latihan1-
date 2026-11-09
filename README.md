Console.WriteLine("=== PROGRAM TOTAL HARGA BARANG ===");

Console.Write("Masukkan nama barang: ");
string namaBarang = Console.ReadLine();

Console.Write("Masukkan harga satuan: ");
int hargaSatuan = int.Parse(Console.ReadLine());

Console.Write("Masukkan jumlah barang: ");
int jumlahBarang = int.Parse(Console.ReadLine());

// Menghitung subtotal
int subtotal = hargaSatuan * jumlahBarang;

// Biaya layanan
const int biayaLayanan = 2000;

// Menghitung total
int total = subtotal + biayaLayanan;

// Menampilkan hasil
Console.WriteLine("\n=== HASIL PERHITUNGAN ===");
Console.WriteLine($"Barang = {namaBarang}");
Console.WriteLine($"Subtotal = {subtotal}");
Console.WriteLine($"Biaya layanan = {biayaLayanan}");
Console.WriteLine($"Total harga = {total}");