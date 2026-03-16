# Exercícios – Capítulo 3 (Classes e Objetos)

Estes exercícios são baseados no **Capítulo 3 do livro _Java: Como Programar (Deitel)_**.  
Eles focam nos conceitos iniciais de **Programação Orientada a Objetos (POO)** em Java.

---

# Conceitos praticados

- criação de classes
- criação de objetos
- métodos
- variáveis de instância
- encapsulamento
- métodos `get` e `set`
- construtores

---

# 1. Classe Saudacao

Crie uma classe chamada `Saudacao`.

Ela deve possuir um método:

```
exibirMensagem()
```

que imprime:

```
Bem-vindo ao mundo da programação orientada a objetos!
```

Crie uma classe `Main` para instanciar o objeto e chamar o método.

---

# 2. Classe Livro

Crie uma classe chamada `Livro` com o atributo:

```
titulo
```

Crie métodos:

```
setTitulo
getTitulo
```

No `main`, crie um objeto `Livro`, defina o título e imprima o título.

---

# 3. Classe Estudante

Crie uma classe `Estudante` com os atributos:

```
nome
idade
```

Crie métodos `set` e `get` para ambos os atributos.

No `main`, crie um objeto estudante e exiba seus dados.

---

# 4. Classe Carro

Crie uma classe `Carro` com os atributos:

```
marca
modelo
ano
```

Crie métodos para definir e obter os valores.

Depois imprima:

```
Marca: ...
Modelo: ...
Ano: ...
```

---

# 5. Classe Produto

Crie uma classe `Produto` com os atributos:

```
nome
preco
```

Crie métodos:

```
setNome
setPreco
getNome
getPreco
```

No programa principal, mostre as informações do produto.

---

# 6. Classe Pessoa com Construtor

Crie uma classe `Pessoa` com os atributos:

```
nome
idade
```

Crie um **construtor** que receba esses valores.

No `main`, crie um objeto passando os dados no construtor.

---

# 7. Classe ContaBancaria

Crie uma classe `ContaBancaria` com o atributo:

```
saldo
```

Crie métodos:

```
depositar(double valor)
sacar(double valor)
```

Mostre o saldo final após as operações.

---

# 8. Classe Retangulo

Crie uma classe `Retangulo` com:

```
largura
altura
```

Crie um método:

```
calcularArea()
```

que retorna a área do retângulo.

---

# 9. Classe GradeBook (estilo Deitel)

Crie uma classe `GradeBook` com o atributo:

```
nomeCurso
```

Crie métodos:

```
setNomeCurso
getNomeCurso
exibirMensagem()
```

A mensagem deve ser:

```
Bem-vindo ao curso de [nomeCurso]
```

---

# 10. Classe Funcionario

Crie uma classe `Funcionario` com:

```
nome
salario
```

Crie métodos para definir e obter esses valores.

Depois mostre:

```
Funcionario: João
Salario: 3000
```
