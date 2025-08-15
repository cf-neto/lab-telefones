# 📒 Lab-Telefones - EM DESENVOLVIMENTO

**Lab-Telefones** é um projeto em Go que permite limpar, normalizar e formatar números de telefone do Brasil, considerando todas as variações possíveis de entrada, como DDD com parênteses, códigos de país, números sem o dígito 9, zeros extras, e formatos incorretos.  

---

## ✨ Visão Geral

Lab-Telefones permite que você:

- Limpe números de telefone removendo caracteres inválidos
- Formate números para o padrão `(XX) XXXXX-XXXX`
- Ignore números inválidos ou com dígitos insuficientes
- Teste múltiplos formatos de entrada de maneira automatizada

---

## 📁 Tecnologias Utilizadas

| Tecnologia | Função                                  |
|------------|-----------------------------------------|
| Go         | Linguagem principal do projeto          |
| regexp     | Expressões regulares para limpeza dos números |

---

## 🧑‍🎓 Público-Alvo
- Desenvolvedores que precisam normalizar números de telefone  
- Projetos de CRM ou sistemas que lidam com contatos do Brasil  
- Qualquer pessoa que precise padronizar listas de números  

---

## 📂 Estrutura do Projeto

```plaintext
lab-telefones/
├── main.go         # Código principal do projeto
├── go.mod          # Arquivo de módulos Go
└── README.md       # Documentação do projeto
