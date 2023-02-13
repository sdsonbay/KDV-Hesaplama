# KDV-Hesaplama

float tutar, kdv;

Scanner scanner = new Scanner(System.in);

System.out.println("Tutar giriniz: ");
tutar = scanner.nextFloat();

if(tutar => 0 && tutar <= 1000)
{
  kdv = 0.18;
}
else
{
  kdv = 0.08;
}

float kdvTutar = tutar * kdv;

System.out.println("KDV'li tutar: " + kdvTutar);
