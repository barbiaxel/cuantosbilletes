# cuantosbilletes
Contar el mínimo de billetes para una cantidad de dinero
package cuantosBilletes;

public class cuantosBilletes {

	public static void main(String[] args) {
		int importe=233;
		int a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p;
		
		//Billetes 500
		a=importe/500;
		j=importe%500;
		
		//Billetes 200
		b=j/200;
		k=j%200;
		
		//Billetes 100
		c=k/100;
		l=k%100;
		
		//Billetes 50
		d=l/50;
		m=l%50;
		
		//Billetes 20
		e=m/20;
		n=m%20;
		
		//Billetes 10
		f=n/10;
		o=n%10;
		
		//Billetes 5
		g=o/5;
		p=o%5;
		
		//Monedas 2
		h=p/2;
		o=p%2;
		
		//Monedas 1
		i=o/1;
		
		
		
		System.out.println(importe+" euros:");
		if (a ==1 ){
			System.out.println(a+" billete de 500€");}
				else if(a == 0){
					System.out.print("");}
						else{System.out.println(a+" billetes de 500€");}
		
		if (b == 1){
			System.out.println(b+" billete de 200€");}
				else if(b == 0){
					System.out.print("");}
						else{System.out.println(b+" billetes de 200€");}
		
		if (c == 1){
			System.out.println(c+" billete de 100€");}
				else if(c == 0){
					System.out.print("");}
						else{System.out.println(c+" billetes de 100€");}
		
		if (d == 1){
			System.out.println(d+" billete de 50€");}
				else if(d == 0){
					System.out.print("");}
						else{System.out.println(d+" billetes de 50€");}
		
		if (e == 1){
			System.out.println(e+" billete de 20€");}
				else if(e == 0){
					System.out.print("");}
						else{System.out.println(e+" billetes de 20€");}
		
		if (f == 1){
			System.out.println(f+" billete de 10€");}
				else if(f == 0){
					System.out.print("");}
						else{System.out.println(f+" billetes de 10€");}
		
		if (g == 1){
			System.out.println(g+" billete de 5€");}
				else if(g == 0){
					System.out.print("");}
						else{System.out.println(g+" billetes de 5€");}


		if (h == 1){
			System.out.println(h+" moneda de 2€");}
				else if (h == 0){
					System.out.print("");}
						else{System.out.println(h+" moneda de 2€");}

		if (i == 1){
			System.out.println(i+" moneda de 1€");}
				else if (i == 0){
					System.out.print("");}
						else{System.out.println(i+" moneda de 1€");}
		
		}
}
