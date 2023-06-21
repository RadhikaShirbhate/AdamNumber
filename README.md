# AdamNumber

public class AdamNumber{

	public static void main(String[] args) {
		int n =12;// Integer.parseInt(args[0]);
		int c = n * n;//144
		int b = (n % 10) * 10 + (n / 10);//21
		int d = b * b;//441
		int r=0;
		while(d!=0)
		{
			int e=d%10;
			r=r*10+e;
			d/=10;
		}
		if(r==c)
			System.out.println("The given number is Adam number");
		else
			System.out.println("The given numberc is not Adam number");
	}

}
