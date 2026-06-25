# 🚗 Trabalho Final — Sistemas de Gestão

**Instituto Federal de Educação, Ciência e Tecnologia do Piauí — IFPI / Campus Corrente**

**Disciplina:** Algoritmos e Lógica de Programação

**Curso:** Análise e Desenvolvimento de Sistemas (ADS)

---

## 🎯 Objetivo

Desenvolver um **sistema de gestão** completo, aplicando os conceitos estudados ao longo da disciplina: variáveis e tipos de dados, estruturas de decisão e repetição, listas e dicionários, funções, validação de dados e organização do código.

Cada equipe escolherá **um** dos temas disponíveis abaixo e deverá implementar o sistema atendendo aos requisitos descritos para aquele tema, além dos **requisitos mínimos comuns** a todos os projetos.

> 💡 Todos os temas têm o **mesmo grau de complexidade**. Não há tema "mais fácil" — a nota depende da qualidade da implementação, não do tema escolhido.

---

## 📋 Orientações Gerais

- **Equipes:** Ian Souza Lisboa; Deus
- **Tema:** Sistema de Oficina Mecânica (4)
- **Linguagem:** Python 3.
- **Entrega:** repositório/pasta com o código-fonte + este README preenchido com os nomes da equipe.
- **Apresentação:** demonstração do sistema funcionando + explicação do código.
- **Prazo de entrega:** `15/07/2026`

---

## ✅ Requisitos Mínimos (comuns a todos os temas)

Independentemente do tema escolhido, o sistema **deve** conter:

1. **Menu principal** com navegação (laço de repetição até o usuário escolher sair).
2. **Cadastro completo (CRUD)** das principais entidades:
   - **C**riar (incluir novo registro)
   - **R**ecuperar (listar / consultar)
   - **U**pdate (alterar dados de um registro)
   - **D**elete (remover registro)
3. **Pelo menos 4 entidades** relacionadas entre si.
4. **Validação de dados de entrada** (não aceitar valores inválidos, campos vazios, opção inexistente no menu etc.).
5. **Regras de negócio** específicas do tema (cálculos, multas, descontos, verificação de disponibilidade etc.).
6. **Manipulação de datas/horas** quando o tema exigir (uso do módulo `datetime`).
7. **Pelo menos 2 relatórios/consultas** com filtro (ex.: listar todos os registros de um período, calcular um total etc.).
8. **Uso de funções** para organizar o código (evitar todo o programa em um único bloco).

### ⭐ Diferenciais (pontuação extra)
- Persistência de dados em arquivo (`.json`, `.csv` ou `.txt`).
- Tratamento de exceções (`try / except`).
- Interface organizada e amigável no terminal.
- Código comentado e bem identado.

---

## 🗂️ Tema

---

### 4. 🔧 Sistema de Oficina Mecânica

A oficina mantém um **estoque de peças** de diferentes marcas, valores e quantidades. Eventualmente uma peça esgota e atinge o ponto de reposição, ou é descontinuada; novos itens são adquiridos e há diversos **serviços** oferecidos, cada um com seu valor de mão de obra — sendo necessário manter o cadastro de peças e serviços sempre atualizado.

Os clientes trazem seus veículos para reparo. Primeiro é necessário cadastrá-los e registrar os veículos vinculados. Depois, o veículo é avaliado e abre-se uma **Ordem de Serviço (OS)** com o diagnóstico inicial — **o valor varia conforme as peças necessárias e as horas de mão de obra**. Antes de iniciar, a oficina apresenta o **orçamento**, que o cliente precisa **aprovar**; apenas as peças aprovadas e disponíveis em estoque são reservadas.

Ao finalizar, define-se a OS como concluída, registra-se data/hora de entrega e dá-se **baixa no estoque** das peças usadas, somando peças + mão de obra. Se durante a execução surgirem **problemas adicionais**, eles vão para nova aprovação e somam ao total; se um serviço orçado não for necessário, seu valor é **descontado** do total final.

---

## 📊 Critérios de Avaliação

| Critério | Descrição | Pontos |
|---|---|---|
| Funcionamento do menu e CRUD | Menu navegável e cadastro completo das entidades | 2,0 |
| Regras de negócio | Cálculos, multas, descontos e verificações corretas | 2,5 |
| Validação de dados | Tratamento de entradas inválidas | 1,5 |
| Relatórios/consultas | Consultas com filtro funcionando | 1,5 |
| Organização do código | Uso de funções, identação e clareza | 1,5 |
| Apresentação | Demonstração e domínio do código pela equipe | 1,0 |
| **Total** | | **10,0** |

> ⭐ Os diferenciais (persistência, tratamento de exceções, interface caprichada) podem render **pontuação extra** a critério do professor.

---

## 👥 Identificação do Aluno

| Nome | Sistema |
|---|---|
| Ian Souza Lisboa | 4 - Mecânica|

---

## 🚀 Como Executar

```bash
python main.py
```

> _Descreva aqui quaisquer instruções adicionais para rodar o seu sistema (bibliotecas necessárias, arquivos de dados etc.)._

---

_Bons estudos e mãos à obra! 💻_
