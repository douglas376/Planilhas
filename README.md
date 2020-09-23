pacote senai;

import java.util.ArrayList;

import javax.swing.JOptionPane;

funcoes de classe pública {
	
	public static void main (String [] args) {
		
		ArrayList <Integer> numeros = novo ArrayList <Integer> ();
		ArrayList <Duplo> medias = novo ArrayList <Duplo> ();
		
		Inteiro menorNumero = 9999;
		Integer maiorNumero = 0;
		Inteiro indiceMenorNumero = 0;
		Inteiro indiceMaiorNumero = 0;
		numeros.add (15);
		numeros.add (23);
		numeros.add (05);
		numeros.add (30);
		numeros.add (3);
		numeros.add (29);
	
	
		valor duplo 1 = 0,0;
		valor duplo 2 = 0,0;
		mídia dupla = 0,0;
		soma duplo = 0,0;
		
		
		para (int i = 0; i <numeros.size (); i ++) {
			if (menorNumero> numeros.get (i)) {
				menorNumero = numeros.get (i);
				indiceMenorNumero = i;
				JOptionPane.showMessageDialog (null, "Novo Menor numero Encontrado! \ N" + menorNumero);
		
			}
		
		
		
		JOptionPane.showMessageDialog (null, "o menor numero da lista: \ n" + numeros + "\ n é o numero:" + numeros.get (indiceMenorNumero));
	}

	{
para (int i = 0; i <numeros.size (); i ++) {
	if (maiorNumero <numeros.get (i)) {
		maiorNumero = numeros.get (i);
		indiceMaiorNumero = i;
		JOptionPane.showMessageDialog (null, "Novo Maior numero Encontrado! \ N" + maiorNumero);
	}
	JOptionPane.showMessageDialog (null, "o Maior numero da lista: \ n" + numeros + "\ n é o numero:" + numeros.get (indiceMaiorNumero));
}

}


	

valor1 = Double.parseDouble (JOptionPane.showInputDialog ("digite o primeiro valor"));
valor2 = Double.parseDouble (JOptionPane.showInputDialog ("digite o segundo valor"));


mídia = (valor1 + valor2) / 2;
soma = valor1 + valor2;
JOptionPane.showMessageDialog (null, "A media" + "é" + media);
JOptionPane.showMessageDialog (null, "A soma" + "é" + soma);
	
	
	}
	
	
	}
