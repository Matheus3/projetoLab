package apresentacao;

import java.util.Scanner;

import entidades.Cliente;

public class ClienteApresentacao {

	Scanner sc = new Scanner(System.in);

	public Cliente preencherAluno() {

		System.out.println("================= Digite seu nome: =================");
		String nome = sc.next();

		System.out.println("================= Digite sua Idade: =================");
		int idade = sc.nextInt();

		System.out.println("================= Digite seu CPF: =================");
		int cpf = sc.nextInt();

		System.out.println("================= Digite seu Email: =================");
		String email = sc.next();

		System.out.println("================= Digite seu Celular: =================");
		int celular = sc.nextInt();

		return new Cliente(nome, idade, cpf, email, celular);

	}

}
