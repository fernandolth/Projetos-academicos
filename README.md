# 📚 Sistema de Notas dos Alunos

Projeto acadêmico simples desenvolvido em **Python** para calcular a média final de um aluno e informar se ele foi aprovado ou reprovado.

## 💻 Funcionamento

O programa:

* Solicita duas notas;
* Calcula a média;
* Verifica o resultado;
* Mostra se o aluno foi **Aprovado** ou **Reprovado**.

## 🛠️ Tecnologias

* Python 3

## ▶️ Como executar

Clone o repositório:

```bash
git clone https://github.com/fernandolth/Projetos-academicos.git
```

Entre na pasta:

```bash
cd Projetos-academicos
```

Depois, execute o arquivo Python:

```bash
python main.py
```
## 📋 Exemplo de uso
```Codigo
def calcular_media():

    print("=== Sistema de notas dos alunos.")
    n1 = float(input("digigte a primeira nota: "))
    n2 = float(input("digigte a segunda nota: "))
    media = (n1 + n2) / 2
    print("A média final é", media)
    if media >= 7:
        print("Status: Aprovado")
    else:
        print("Status: Reprovado")
calcular_media()
```


```text
=== Sistema de notas dos alunos. ===

Digite a primeira nota: 8
Digite a segunda nota: 7

A média final é 7.5
Status: Aprovado
```

## 👨‍💻 Autor

**Fernando Leal**

Estudante de Ciência da Computação.

## 📫 Contato

GitHub: https://github.com/fernandolth
