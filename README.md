# Sistema de Cadastro de Clientes em Linguagem C
> **Uma abordagem introdutória para construção de ERP Modular**

Este projeto foi desenvolvido como parte da disciplina de **Algoritmos e Programação** do curso de **Engenharia de Software** no **UNICEPLAC**. O objetivo principal é aplicar conceitos fundamentais de programação estruturada em C como base para o entendimento de sistemas corporativos (ERP).

## 🎓 Informações Acadêmicas
* **Instituição:** UNICEPLAC – Centro Universitário
* **Curso:** Engenharia de Software
* **Disciplina:** Algoritmos e Programação
* **Professor/Autor:** Hudson Neves
* **Local:** Brasília – DF
* **Ano:** 2026

---

## 📝 Resumo
O projeto apresenta o desenvolvimento de um sistema de gerenciamento de clientes operando em memória volátil. Focado na lógica computacional, o sistema implementa as funcionalidades de inserção, listagem e busca, simulando a construção incremental de um módulo integrante de um **Enterprise Resource Planning (ERP)**.

**Palavras-chave:** Linguagem C, Algoritmos, ERP, Cadastro de Clientes, Programação Estruturada.

---

## 🎯 Objetivos

### Geral
Desenvolver um sistema simplificado em C para gerenciamento de dados, consolidando o aprendizado em lógica e estruturas de dados.

### Específicos
* Implementar estruturas de dados complexas utilizando `struct`.
* Manipular vetores para armazenamento temporário de registros.
* Desenvolver funcionalidades de CRUD básico (Create, Read).
* Aplicar estruturas de controle de fluxo e repetição.
* Introduzir a arquitetura modular de sistemas ERP.

---

## 🛠️ Tecnologias e Conceitos
* **Linguagem:** C (Padrão ANSI)
* **Paradigma:** Programação Estruturada
* **Interface:** CLI (Command Line Interface)
* **Estruturas Principais:** `struct`, `arrays`, `loops`, `condicionais`.

---

## 💻 Desenvolvimento Técnico

### Estrutura de Dados Principal
A base do sistema utiliza a seguinte definição para os registros de clientes:
```c
struct Cliente {
    int id;
    char nome[50];
    char telefone[20];
};

Funcionalidades Implementadas
Cadastro: Registro de novos clientes no vetor em memória.

Listagem: Exibição detalhada de todos os registros armazenados.

Busca: Localização de clientes através do nome (comparação de strings).

🚧 Limitações e Trabalhos Futuros
Limitações Atuais
[x] Armazenamento volátil (dados são perdidos ao fechar o programa).

[x] Ausência de persistência em arquivos ou banco de dados.

[x] Interface restrita ao terminal/console.

Próximos Passos (Roadmap)
[ ] Implementação de manipulação de arquivos (FILE *) para persistência.

[ ] Expansão para novos módulos (Estoque, Financeiro, Vendas).

[ ] Criação de uma interface gráfica (GUI).

[ ] Implementação de sistema de autenticação e permissões.

📖 Referências
DEITEL, H. M.; DEITEL, P. J. C: Como Programar. 6. ed. São Paulo: Pearson, 2011.

SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.

PRESSMAN, Roger S. Engenharia de Software: Uma Abordagem Profissional. 8. ed. Porto Alegre: AMGH, 2016.
