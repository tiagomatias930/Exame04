
---

# 📝 Exame 04 - 42 Luanda

Este repositório contém a minha solução para o **Exame 04** da **42 Luanda**. O exame abrange diversos conceitos fundamentais da programação em C, desafiando os alunos a implementar soluções eficientes e seguindo as normas da escola.

## 📚 Conteúdos abordados

Este exame exige domínio de vários tópicos essenciais, incluindo:

- Manipulação de strings e memória
- Tratamento de erros
- Manipulação de arquivos
- Recursão e iteração
- Manipulação de ponteiros
- Leitura e gravação em arquivos
- Implementação de funções personalizadas (sem uso de funções de bibliotecas padrões)

## 🚀 Instruções para Compilação e Execução

Para compilar os arquivos do projeto, certifique-se de que todos os arquivos `.c` estão presentes no diretório.

### Compilação

Execute o seguinte comando no terminal para compilar o código:

```bash
gcc -Wall -Wextra -Werror -o exame04 main.c <outros_arquivos>.c
```

### Execução

Após a compilação, execute o programa:

```bash
./exame04
```

## 🛠️ Funções Implementadas

Aqui estão algumas das funções implementadas e seus propósitos:

- **ft_strcpy**: Cópia de strings
- **ft_strlen**: Cálculo do comprimento de strings
- **ft_memset**: Preenchimento de blocos de memória
- **ft_atoi**: Conversão de string para inteiro
- **ft_printf**: Função personalizada para formatação e impressão

## 📑 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
├── includes/
│   └── *.h           # Arquivos de cabeçalho
├── srcs/
│   └── *.c           # Implementação das funções
├── main.c            # Arquivo principal para testar as funções
└── Makefile          # Script para automatizar a compilação
```

## ⚠️ Normas 42

Todo o código segue as [normas da 42](https://github.com/42School/norminette). O código foi cuidadosamente verificado usando o **Norminette**, e está livre de erros de formatação ou estilo.

## 📋 Requisitos

- Linguagem de programação: **C**
- Sistema operacional: **Linux** ou **MacOS**
- Compilador: **GCC**

## 🧠 Dificuldades Encontradas

Durante a implementação, alguns dos principais desafios foram:

- Manter o código eficiente e seguir a Norminette.
- Gerenciar adequadamente a alocação e desalocação de memória.
- Lidar com entradas de dados complexas e garantir o tratamento adequado de erros.
