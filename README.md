# Curso Completo de C++ para Iniciantes 🚀

Bem-vindo ao curso completo de **C++ do zero**.

Este repositório foi criado para ensinar programação em C++ passo a passo, de forma simples, prática e organizada.

---

# 📚 O que você vai aprender

- Lógica de programação
- Sintaxe do C++
- Variáveis
- Condições
- Loops
- Funções
- Arrays
- Strings
- Ponteiros
- Orientação a Objetos
- STL
- Estruturas de Dados
- Projetos práticos

---

# 🛠️ Instalação do Ambiente

## 1. Instale o Visual Studio Code

Download:

https://code.visualstudio.com

---

## 2. Instale um compilador C++

### Windows
Instale:
- MinGW

Tutorial:
https://code.visualstudio.com/docs/languages/cpp

---

# 📂 Estrutura do Curso

```text
curso-cpp/
│
├── aula-01-introducao/
├── aula-02-variaveis/
├── aula-03-operadores/
├── aula-04-condicionais/
├── aula-05-loops/
├── aula-06-funcoes/
├── aula-07-arrays/
├── aula-08-strings/
├── aula-09-ponteiros/
├── aula-10-classes/
├── aula-11-stl/
├── projetos/
└── README.md
```

---

# Aula 01 — Introdução ao C++

---

## 📖 O que é C++?

C++ é uma linguagem de programação criada para desenvolver:
- jogos
- sistemas operacionais
- aplicativos
- inteligência artificial
- softwares rápidos

Ela é muito usada porque possui:
- alta performance
- controle de memória
- grande mercado de trabalho

---

# Seu Primeiro Programa

Crie um arquivo chamado:

```text
main.cpp
```

Digite:

```cpp
#include <iostream>

using namespace std;

int main() {

    cout << "Olá Mundo!";

    return 0;
}
```

---

# 🔍 Explicação Linha por Linha

## `#include <iostream>`

Importa recursos de entrada e saída.

Permite usar:
- `cout`
- `cin`

---

## `using namespace std;`

Evita escrever `std::` antes dos comandos.

---

## `int main()`

Função principal do programa.

Todo programa começa aqui.

---

## `cout`

Mostra informações na tela.

```cpp
cout << "Texto";
```

---

## `return 0;`

Indica que o programa terminou corretamente.

---

# ▶️ Como Executar

Compile:

```bash
g++ main.cpp -o programa
```

Execute:

```bash
./programa
```

No Windows:

```bash
programa.exe
```

---

# 🧠 Exercícios

## Exercício 1

Mostre seu nome na tela.

Exemplo:

```text
Meu nome é João
```

---

## Exercício 2

Mostre:
- idade
- cidade
- profissão

---

# Aula 02 — Variáveis

---

# 📖 O que são Variáveis?

Variáveis armazenam informações na memória.

Exemplo:

```cpp
int idade = 20;
```

---

# Tipos de Dados

| Tipo | Exemplo |
|------|----------|
| int | 10 |
| float | 5.5 |
| double | 10.99 |
| char | 'A' |
| bool | true |
| string | "Olá" |

---

# Exemplo Completo

```cpp
#include <iostream>
#include <string>

using namespace std;

int main() {

    int idade = 25;
    double altura = 1.80;
    string nome = "Carlos";

    cout << nome << endl;
    cout << idade << endl;
    cout << altura << endl;

    return 0;
}
```

---

# 📖 Entrada de Dados

## `cin`

Permite o usuário digitar valores.

```cpp
cin >> idade;
```

---

# Exemplo

```cpp
#include <iostream>

using namespace std;

int main() {

    int idade;

    cout << "Digite sua idade: ";

    cin >> idade;

    cout << "Sua idade é: " << idade;

    return 0;
}
```

---

# 🧠 Exercícios

## Exercício 1

Peça:
- nome
- idade

Mostre:

```text
Olá João, você tem 20 anos
```

---

## Exercício 2

Peça dois números e mostre a soma.

---

# Aula 03 — Operadores

---

# Operadores Matemáticos

| Operador | Significado |
|----------|-------------|
| + | Soma |
| - | Subtração |
| * | Multiplicação |
| / | Divisão |
| % | Resto |

---

# Exemplo

```cpp
#include <iostream>

using namespace std;

int main() {

    int a = 10;
    int b = 5;

    cout << a + b << endl;
    cout << a - b << endl;
    cout << a * b << endl;
    cout << a / b << endl;

    return 0;
}
```

---

# Operadores Relacionais

| Operador | Significado |
|----------|-------------|
| == | Igual |
| != | Diferente |
| > | Maior |
| < | Menor |
| >= | Maior ou igual |
| <= | Menor ou igual |

---

# Aula 04 — Condicionais

---

# 📖 IF e ELSE

Permitem tomar decisões.

---

# Exemplo

```cpp
#include <iostream>

using namespace std;

int main() {

    int idade;

    cin >> idade;

    if (idade >= 18) {

        cout << "Maior de idade";

    } else {

        cout << "Menor de idade";

    }

    return 0;
}
```

---

# ELSE IF

```cpp
if (nota >= 9) {

    cout << "Excelente";

} else if (nota >= 7) {

    cout << "Bom";

} else {

    cout << "Reprovado";

}
```

---

# 🧠 Exercícios

## Exercício 1

Peça uma senha.

Se for:
```text
1234
```

Mostre:
```text
Acesso permitido
```

---

# Aula 05 — Loops

---

# 📖 WHILE

Repete enquanto a condição for verdadeira.

---

# Exemplo

```cpp
int i = 1;

while (i <= 5) {

    cout << i << endl;

    i++;
}
```

---

# 📖 FOR

Muito usado em programação.

---

# Exemplo

```cpp
for (int i = 0; i < 10; i++) {

    cout << i << endl;
}
```

---

# 🧠 Exercícios

## Exercício 1

Mostre números de 1 até 100.

---

## Exercício 2

Faça uma tabuada.

---

# Aula 06 — Funções

---

# 📖 O que são Funções?

Funções organizam o código.

---

# Exemplo

```cpp
#include <iostream>

using namespace std;

void mensagem() {

    cout << "Olá";
}

int main() {

    mensagem();

    return 0;
}
```

---

# Função com Retorno

```cpp
int soma(int a, int b) {

    return a + b;
}
```

---

# Aula 07 — Arrays

---

# 📖 O que é um Array?

Array guarda vários valores.

---

# Exemplo

```cpp
int numeros[5] = {1, 2, 3, 4, 5};
```

---

# Percorrendo Array

```cpp
for (int i = 0; i < 5; i++) {

    cout << numeros[i] << endl;
}
```

---

# Aula 08 — Strings

---

# 📖 Trabalhando com Textos

```cpp
#include <string>
```

---

# Exemplo

```cpp
string nome = "Maria";
```

---

# Concatenando

```cpp
string nome = "João";

cout << "Olá " + nome;
```

---

# Aula 09 — Ponteiros

---

# 📖 O que é um Ponteiro?

Ponteiros armazenam endereços de memória.

---

# Exemplo

```cpp
int x = 10;

int* p = &x;
```

---

# Explicação

| Símbolo | Significado |
|----------|-------------|
| * | Ponteiro |
| & | Endereço |

---

# Aula 10 — Classes

---

# 📖 Programação Orientada a Objetos

---

# Criando Classe

```cpp
class Pessoa {

public:

    string nome;
    int idade;
};
```

---

# Criando Objeto

```cpp
Pessoa p;

p.nome = "Carlos";
p.idade = 20;
```

---

# Aula 11 — STL

---

# 📖 O que é STL?

Biblioteca pronta do C++.

Muito usada profissionalmente.

---

# Vector

```cpp
#include <vector>

vector<int> numeros;
```

---

# Adicionando Valores

```cpp
numeros.push_back(10);
```

---

# Projeto 01 — Calculadora

```cpp
#include <iostream>

using namespace std;

int main() {

    int a;
    int b;

    cout << "Digite dois números: ";

    cin >> a >> b;

    cout << "Soma: " << a + b << endl;
    cout << "Subtração: " << a - b << endl;
    cout << "Multiplicação: " << a * b << endl;
    cout << "Divisão: " << a / b << endl;

    return 0;
}
```

---

# 🚀 Próximos Passos

Depois deste curso você pode estudar:
- Estruturas de Dados
- Algoritmos
- C++ Moderno
- OpenGL
- Unreal Engine
- Desenvolvimento de Jogos
- Inteligência Artificial

---

# 📚 Recomendações

Pratique todos os dias.

Programação se aprende:
- escrevendo código
- errando
- corrigindo
- construindo projetos

---

# ⭐ Objetivo Final

Ao concluir este curso você será capaz de:
- criar programas em C++
- entender lógica
- desenvolver projetos
- iniciar estudos avançados

---

# 🤝 Contribuição

Sinta-se livre para:
- melhorar exemplos
- adicionar exercícios
- criar projetos
- abrir pull requests

---

# 📄 Licença

Este projeto é livre para estudos.

MIT License

https://youtu.be/yKoLERQUZ1A?si=b4bkyIKW8bhP8fQ8
