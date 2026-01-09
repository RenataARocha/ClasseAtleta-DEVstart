# 🏅 Dados dos Atletas

Projeto de certificação em **JavaScript** que utiliza **Programação Orientada a Objetos (POO)** para armazenar e calcular informações de um atleta em uma competição esportiva.

---

## 📌 Descrição do projeto

Neste projeto, foi criada uma aplicação capaz de receber os dados de um atleta — como nome, idade, peso, altura e notas — e calcular automaticamente:

- Categoria do atleta
- IMC (Índice de Massa Corporal)
- Média válida das notas (desconsiderando a maior e a menor)

Toda a lógica foi organizada dentro de uma **classe**, tornando o código mais limpo, reutilizável e fácil de manter.

---

## 🧠 Funcionalidades

A aplicação realiza as seguintes ações:

- Cria um atleta a partir da classe `Atleta`
- Calcula a **categoria** com base na idade
- Calcula o **IMC** usando a fórmula padrão
- Calcula a **média válida** das notas
- Exibe todas as informações no console

---

## 🏷️ Regras de negócio

### 📍 Categorias por idade

- Infantil: 9 a 11 anos
- Juvenil: 12 a 13 anos
- Intermediário: 14 a 15 anos
- Adulto: 16 a 30 anos
- Sem categoria: demais idades

### 📍 Cálculo do IMC

```
IMC = peso / (altura × altura)
```

### 📍 Média válida

- Ordena as 5 notas
- Remove a maior e a menor
- Calcula a média das 3 notas restantes

---

## 📂 Estrutura do projeto

```
dados-atletas
├── dados-atletas.js
└── README.md
```

---

## 🚀 Tecnologias utilizadas

- JavaScript (ES6)
- Programação Orientada a Objetos
- Git
- GitHub

---

## ▶️ Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/dados-atletas.git
```

2. Acesse a pasta do projeto:

```bash
cd dados-atletas
```

3. Execute o arquivo JavaScript no terminal:

```bash
node dados-atletas.js
```

4. Veja o resultado no console.

---

## 📈 Exemplo de saída

```
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68166089965398
Média válida: 9.25333333
```

---

## ✨ Aprendizados

- Criação e uso de classes em JavaScript
- Uso de `constructor` e métodos
- Aplicação de regras de negócio
- Manipulação de arrays
- Organização de código com POO

---

## 👩‍💻 Autora

**Renata Alexandre Rocha**
Desenvolvedora Front-End em transição de carreira

---

## 🔗 Link do repositório

[https://github.com/seu-usuario/dados-atletas](https://github.com/seu-usuario/dados-atletas)
