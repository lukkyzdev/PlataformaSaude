# <img align="center" alt="Python" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"> Sistema de Gestão Clínica | Python CRUD & Estatísticas

Uma aplicação de terminal (CLI) desenvolvida em Python para modernizar e automatizar o cadastro e a gestão de pacientes de uma clínica médica. 

O projeto atua como o motor lógico de um sistema de gestão, focando na manipulação de estruturas de dados em memória, operações de CRUD (Create e Read) e geração de métricas em tempo real.

## 🎯 Business Case & Objetivo
Este projeto foi desenhado para resolver um problema real de negócios: substituir rotinas manuais desorganizadas por um sistema centralizado e seguro. Para construir esta solução, foram aplicados conceitos estruturais de engenharia de software:
- Estruturação de dados utilizando **Dicionários** (`dict`) e **Listas** (`list`).
- Desenvolvimento de algoritmos para pesquisa linear em memória.
- Cálculos estatísticos dinâmicos (médias, contagens, valores mínimos e máximos).
- Criação de laços de repetição de menu (`while`) com tratamento robusto de erros e validação de *inputs* do utilizador.

## 🚀 Funcionalidades Principais
O sistema opera através de um menu interativo contínuo, oferecendo as seguintes capacidades:
1. **Cadastro de Pacientes (Ingestão):** Adição de novos perfis contendo nome, idade e contacto telefónico, armazenados na estrutura de dados principal.
2. **Painel Analítico (Métricas):** Processamento matemático instantâneo que calcula o total de pacientes ativos, a média de idades e identifica os perfis extremos (paciente mais novo e mais velho).
3. **Motor de Busca:** Consulta otimizada para localizar e exibir os dados completos de um paciente específico através do nome.
4. **Listagem Geral:** Renderização formatada de toda a base de dados cadastrada no sistema.

## 💻 Demonstração de Uso
O sistema foi concebido para ser altamente intuitivo através da linha de comandos. Abaixo está a interface de navegação principal e o fluxo de cadastro:

```text
=== SISTEMA CLÍNICA VIDA+ ===
1. Cadastrar paciente
2. Ver estatísticas
3. Buscar paciente
4. Listar todos os pacientes
5. Sair

Escolha uma opção: 1

Nome do paciente: João Silva
Idade: 45
Telefone: (11) 99999-9999

✅ Paciente cadastrado com sucesso!
