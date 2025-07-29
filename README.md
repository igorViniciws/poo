🧠 Revisão Rápida: Programação Orientada a Objetos (POO)
Esse repositório é uma revisão direta ao ponto sobre os principais conceitos de POO (Programação Orientada a Objetos). Perfeito pra fixar conteúdo, revisar antes de provas ou aplicar em projetos!

📌 Conceito Geral
POO é um paradigma de programação que estrutura o código em torno de objetos, que combinam dados (atributos) e comportamentos (métodos).

🧱 Pilares da POO
Pilar	Explicação Curta	Exemplo Simples
Abstração	Foca só no essencial	carro.ligar() sem saber o motor
Encapsulamento	Protege os dados internos	Atributos privados e getters/setters
Herança	Reutiliza código de outra classe	class Filho extends Pai
Polimorfismo	Mesmo método, ações diferentes	animal.fazerSom() varia
🧠 Conceitos-Chave
Classe: molde que define atributos e métodos
Objeto: instância da classe (é o que "vive")
Atributos: dados guardados pelo objeto
Métodos: funções que o objeto pode executar
Construtor: método especial pra criar objetos
this: referência ao próprio objeto
⚙️ Sintaxe Base (JavaScript Exemplo)
class Pessoa {
  constructor(nome, idade) {
    this.nome = nome;
    this.idade = idade;
  }

  apresentar() {
    console.log(`Sou ${this.nome} e tenho ${this.idade} anos`);
  }
}

const aluno = new Pessoa("Igor", 17);
aluno.apresentar(); // Sou Igor e tenho 17 anos
