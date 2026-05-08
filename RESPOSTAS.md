# 🧠 Exercícios + Respostas + Resoluções

---

# Aula 01 — Introdução

## Exercício 1

Mostre seu nome na tela.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    cout << "Meu nome é João";

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-01/exercicio-01

---

# Exercício 2

Mostre:
- idade
- cidade
- profissão

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    cout << "Idade: 20" << endl;
    cout << "Cidade: São Paulo" << endl;
    cout << "Profissão: Programador" << endl;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-01/exercicio-02

---

# Aula 02 — Variáveis

## Exercício 1

Peça:
- nome
- idade

Mostre:

```text
Olá João, você tem 20 anos
```

---

## ✅ Resposta

```cpp
#include <iostream>
#include <string>

using namespace std;

int main() {

    string nome;
    int idade;

    cout << "Digite seu nome: ";
    cin >> nome;

    cout << "Digite sua idade: ";
    cin >> idade;

    cout << "Olá " << nome << ", você tem " << idade << " anos";

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-02/exercicio-01

---

# Exercício 2

Peça dois números e mostre a soma.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int a;
    int b;

    cout << "Digite o primeiro número: ";
    cin >> a;

    cout << "Digite o segundo número: ";
    cin >> b;

    cout << "Soma: " << a + b;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-02/exercicio-02

---

# Aula 03 — Operadores

## Exercício 1

Peça dois números e mostre:
- soma
- subtração
- multiplicação
- divisão

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int a;
    int b;

    cin >> a;
    cin >> b;

    cout << "Soma: " << a + b << endl;
    cout << "Subtração: " << a - b << endl;
    cout << "Multiplicação: " << a * b << endl;
    cout << "Divisão: " << a / b << endl;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-03/exercicio-01

---

# Aula 04 — Condicionais

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

Caso contrário:
```text
Senha incorreta
```

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int senha;

    cout << "Digite a senha: ";

    cin >> senha;

    if (senha == 1234) {

        cout << "Acesso permitido";

    } else {

        cout << "Senha incorreta";
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-04/exercicio-01

---

# Exercício 2

Peça uma nota.

Se:
- maior ou igual a 7 → Aprovado
- menor que 7 → Reprovado

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    double nota;

    cin >> nota;

    if (nota >= 7) {

        cout << "Aprovado";

    } else {

        cout << "Reprovado";
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-04/exercicio-02

---

# Aula 05 — Loops

## Exercício 1

Mostre números de 1 até 100.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    for (int i = 1; i <= 100; i++) {

        cout << i << endl;
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-05/exercicio-01

---

# Exercício 2

Faça uma tabuada.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int numero;

    cout << "Digite um número: ";

    cin >> numero;

    for (int i = 1; i <= 10; i++) {

        cout << numero << " x " << i << " = " << numero * i << endl;
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-05/exercicio-02

---

# Aula 06 — Funções

## Exercício 1

Crie uma função que mostre:
```text
Olá Mundo
```

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

void mensagem() {

    cout << "Olá Mundo";
}

int main() {

    mensagem();

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-06/exercicio-01

---

# Exercício 2

Crie uma função de soma.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int soma(int a, int b) {

    return a + b;
}

int main() {

    cout << soma(5, 10);

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-06/exercicio-02

---

# Aula 07 — Arrays

## Exercício 1

Crie um array com 5 números.

Mostre todos eles.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int numeros[5] = {1, 2, 3, 4, 5};

    for (int i = 0; i < 5; i++) {

        cout << numeros[i] << endl;
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-07/exercicio-01

---

# Aula 08 — Strings

## Exercício 1

Peça o nome do usuário e mostre:
```text
Olá João
```

---

## ✅ Resposta

```cpp
#include <iostream>
#include <string>

using namespace std;

int main() {

    string nome;

    cout << "Digite seu nome: ";

    cin >> nome;

    cout << "Olá " << nome;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-08/exercicio-01

---

# Aula 09 — Ponteiros

## Exercício 1

Crie uma variável e um ponteiro para ela.

---

## ✅ Resposta

```cpp
#include <iostream>

using namespace std;

int main() {

    int x = 10;

    int* p = &x;

    cout << x << endl;
    cout << p << endl;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-09/exercicio-01

---

# Aula 10 — Classes

## Exercício 1

Crie uma classe Pessoa.

---

## ✅ Resposta

```cpp
#include <iostream>
#include <string>

using namespace std;

class Pessoa {

public:

    string nome;
    int idade;
};

int main() {

    Pessoa p;

    p.nome = "Carlos";
    p.idade = 20;

    cout << p.nome << endl;
    cout << p.idade << endl;

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-10/exercicio-01

---

# Aula 11 — STL

## Exercício 1

Crie um vector e adicione números.

---

## ✅ Resposta

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {

    vector<int> numeros;

    numeros.push_back(10);
    numeros.push_back(20);
    numeros.push_back(30);

    for (int numero : numeros) {

        cout << numero << endl;
    }

    return 0;
}
```

---

## ▶️ Resolução

https://github.com/seu-usuario/curso-cpp/tree/main/resolucoes/aula-11/exercicio-01

---

# 📂 Estrutura Recomendada do GitHub

```text
curso-cpp/
│
├── README.md
│
├── resolucoes/
│   │
│   ├── aula-01/
│   │   ├── exercicio-01/
│   │   └── exercicio-02/
│   │
│   ├── aula-02/
│   ├── aula-03/
│   ├── aula-04/
│   ├── aula-05/
│   ├── aula-06/
│   ├── aula-07/
│   ├── aula-08/
│   ├── aula-09/
│   ├── aula-10/
│   └── aula-11/
```

---

# 🚀 Dica Importante

Tente resolver os exercícios sozinho antes de olhar as respostas.

Programação se aprende:
- praticando
- errando
- corrigindo
- repetindo

---
