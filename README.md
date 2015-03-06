# Tabungan
public class Tabungan {
	public int saldo;

	public Tabungan(int initsaldo){
		this.saldo = initsaldo;

	}
	public int saldo(){
		return saldo;
	}
		public int ambiluang (int jumlah) {
			saldo=saldo-jumlah;
			return saldo;
			
		}
	public static void main(String[] args) {
		Tabungan tabungan = new Tabungan (5000);
		System.out.println("Saldo Awal :"+tabungan.saldo());
		System.out.println("jumlah uang yang diambil : 2300");
		tabungan.ambiluang(2300);
		System.out.println("Saldo Akhir :"+tabungan.saldo());
	}
}
