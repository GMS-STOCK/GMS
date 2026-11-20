# GMS Stock

Sistema web de controle de estoque para a **GMS Human Nutrition**, distribuidora de suplementos alimentares de Sorocaba/SP. Projeto Integrador II do curso de Análise e Desenvolvimento de Sistemas da Fatec Sorocaba.

🔗 **Aplicação:** https://projeto-final-dweb-gms.netlify.app/

## Problema

A empresa controla o estoque em documentos de texto, sem padronização. Isso gera:

- Divergência entre o estoque registrado e o estoque físico
- Produtos vendidos sem estar em estoque, porque a saída é registrada com atraso
- Falta dos produtos mais vendidos e excesso dos de baixa rotatividade
- Nenhum registro de validade dos lotes nem de quem alterou o estoque
- Cerca de 1 hora por dia gasta conferindo o documento com o estoque físico
- Retrabalho de digitação: cada venda das plataformas é digitada de novo no controle

## Objetivo

Substituir o controle manual por um sistema que cadastra produtos, controla lotes e validades, registra entradas e saídas, se integra às plataformas de venda (Shopee, Mercado Livre e Magalu) e alerta quando o estoque chega ao mínimo.

## Funcionalidades

| Funcionalidade | Requisito | Status |
|---|---|---|
| Gerenciar produtos (cadastrar, consultar, editar e excluir) | RF04 | ✅ Implementado |
| Consultar estoque total e lotes por produto | RF06 | 🚧 Tela pronta, com dados fixos |
| Login e logout | RF01, RF02 | 📋 Planejado |
| Gerenciar usuários | RF03 | 📋 Planejado |
| Gerenciar fabricante, local e unidade | RF05 | 📋 Planejado |
| Registrar entrada de mercadorias | RF07 | 📋 Planejado |
| Atualizar estoque automaticamente | RF08 | 📋 Planejado |
| Registrar saída por nota fiscal | RF09 | 📋 Planejado |
| Integração com plataformas de venda | RF10, RF12 | 📋 Planejado |
| Alerta de estoque mínimo | RF11 | 📋 Planejado |
| Leitura de código de barras | RF13 | 📋 Planejado |
| Histórico de entradas e saídas | RF14 | 📋 Planejado |

## Tecnologias

- HTML5, CSS3 e JavaScript, sem framework
- SQLite no navegador com [SQL.js](https://sql.js.org/)
- `localStorage` para manter os dados entre os acessos
- Canva, Figma e Google Stitch para o protótipo das telas
- GitHub, com quadro Kanban para organizar as tarefas
- Netlify para hospedagem

## Estrutura do projeto

```
GMS/
├── ProjetoFinal/
│   ├── assets/            # CSS e imagens
│   ├── database/          # DDL.sql, DML.sql e DQL.sql
│   ├── produtos.html
│   ├── produtos.js
│   ├── estoque.html
│   └── estoque.js
├── Telas - Google Stitch/ # protótipo das telas
├── Documentacao-Final-P.I-GMS-Stock.docx
└── Deploy-Projeto_Final   # link do deploy
```

## Documentação

A documentação completa (requisitos, casos de uso, telas, BPMN e glossário) está em [`Documentacao-Final-P.I-GMS-Stock.docx`](./Documentacao-Final-P.I-GMS-Stock.docx).

## Equipe

**Grupo 404 Name Not Found**

- Guilherme Augusto Felicidade
- João Vitor Mangili da Silva
- Luís Henrique Ribeiro Barrile
- Renan Muniz de Almeida
- Vinicius Walter Schimidt

**Instituição:** Faculdade de Tecnologia de Sorocaba (Fatec), Análise e Desenvolvimento de Sistemas
**Disciplina:** Projeto Integrador II, diurno, 2º semestre
**Data:** novembro de 2026
