
# 📄 Atividade Prática: Validação e Correção de Sintaxe XML

> **Unidade Curricular:** Linguagens de Marcação  
> **Curso:** Técnico em Desenvolvimento de Sistemas — Escola SENAI "Dr. Celso Charuri" (Sumaré)  
> **Aluno:** Lucas Nunes Sutério dos Santos  

---

## 🎯 Objetivo
Esta atividade teve como objetivo analisar, identificar e corrigir erros estruturais e de sintaxe em documentos **XML** (*Extensible Markup Language*), aplicando as regras fundamentais para a criação de arquivos **bem-formados** (*well-formed*).

---

## 🧠 Principais Conceitos Aplicados

Durante a resolução dos exercícios, foram aplicadas as 6 regras essenciais da especificação XML:

1. **Fechamento Obrigatório de Tags:** Toda tag aberta deve possuir sua respectiva tag de fechamento (`<tag></tag>`).
2. **Aspas em Atributos:** Valores de atributos devem estar obrigatoriamente entre aspas duplas e padronizadas (`atributo="valor"`).
3. **Aninhamento Correto (*Proper Nesting*):** As tags devem ser fechadas na ordem inversa de abertura (conceito de "caixas dentro de caixas").
4. **Caracteres Especiais (Entidades):** Símbolos como `&` não podem ficar soltos no texto e devem ser substituídos por entidades nativas (`&amp;`).
5. **Regras de Nomeação de Elementos:** Nomes de tags não podem conter espaços em branco nem iniciar por caracteres numéricos.
6. **Declaração do Cabeçalho:** A instrução de processamento inicial deve seguir exatamente o padrão `<?xml version="1.0" encoding="UTF-8"?>`.

---

## 📁 Estrutura dos Arquivos do Repositório

* 📄 **`ex01_cadastro_de_livro.xml`**  
  * *Correção:* Inclusão da tag de fechamento `</titulo>` que estava ausente.
* 📄 **`ex02_cadastro_de_aluno.xml`**  
  * *Correção:* Adição de aspas no atributo `matricula` e correção na sintaxe do valor da tag `<idade>`.
* 📄 **`ex03_empresa.xml`**  
  * *Correção:* Adição de aspas no atributo `version`, correção do fechamento do cabeçalho (`?>`) e substituição do símbolo `&` por `&amp;`.
* 📄 **`ex04_pedido_de_venda.xml`**  
  * *Correção:* Reorganização do aninhamento das tags `<cliente>` e `<itens>`.
* 📄 **`ex05_cadastro_de_produtos.xml`**  
  * *Correção:* Remoção do espaço do elemento `<nome_produto>` e alteração do nome da tag `<1preco>` para que não inicie com número.
* 📄 **`ex06_sistema_escolar.xml`** *(Desafio)*  
  * *Correção:* Padronização de aspas na declaração XML, inclusão de aspas nos atributos, substituição de `&` por `&amp;` e fechamento da tag `<disciplina>`.

---

## 🛠️ Ferramentas Utilizadas

* **Visual Studio Code (VS Code)**
* **Git & GitHub** (Controle de versão e hospedagem do código)
* **Linguagem de Marcação XML**