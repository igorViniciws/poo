# 🧱 Revisão de POO (Programação Orientada a Objetos)

Este repositório reúne os conceitos mais importantes sobre **Programação Orientada a Objetos**, com resumos, exemplos e exercícios. Ideal pra quem quer revisar a base sólida da programação moderna.

---

## 📌 O que é POO?

POO é um paradigma de programação que organiza o código baseado em **objetos**, que são instâncias de **classes**. Ele aproxima a programação do mundo real, tornando o código mais modular, reutilizável e fácil de manter.

---

## 🧱 Pilares da POO

### 🔹 1. **Abstração**
Focar apenas nos detalhes essenciais.  
➡️ Exemplo: Um objeto `Carro` não precisa expor como o motor funciona, só que ele liga, acelera e freia.

### 🔹 2. **Encapsulamento**
Proteger os dados, deixando acessível apenas o necessário.  
➡️ Atributos privados com métodos `get` e `set`.

### 🔹 3. **Herança**
Permitir que uma classe herde características de outra.  
➡️ `class Aluno extends Pessoa {}`

### 🔹 4. **Polimorfismo**
Objetos diferentes podem responder de formas diferentes ao **mesmo método**.  
➡️ `animal.fazerSom()` pode emitir sons diferentes dependendo da classe (`Cachorro`, `Gato`...).

---

## 🛠️ Componentes Básicos

- **Classe**: Molde, definição de como o objeto deve ser.
- **Objeto**: Instância da classe (um “exemplar”).
- **Método**: Ação que o objeto pode executar.
- **Atributo**: Característica que o objeto possui.

---

## 🧑‍💻 Exemplo (JavaScript)
```js
class Pessoa {
  constructor(nome, idade) {
    this.nome = nome;
    this.idade = idade;
  }

  falar() {
    console.log(`Olá, meu nome é ${this.nome}`);
  }
}

const igor = new Pessoa("Igor", 17);
igor.falar(); // Olá, meu nome é Igor
