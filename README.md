# Ciclo da Arte — Collab Prestação de Contas

Sistema web de gestão comercial e prestação de contas para artistas e colaboradores da **Ciclo da Arte**.

🔗 **Acesso:** [eduardocarloscardoso.github.io/ciclo-prestacao-contas](https://eduardocarloscardoso.github.io/ciclo-prestacao-contas)

---

## Sobre o projeto

Plataforma single-page para gestão das operações comerciais de artistas e collabs, incluindo:

- Cadastro de **Collabs / Vendedores**
- Gestão de **Produtos** por collab e coleção
- Controle de **Canais de Venda**
- Registro e acompanhamento de **Clientes**
- **Prestação de Contas** com cálculo automático de comissões, impostos e descontos
- **Dashboard** com KPIs e indicadores financeiros

## Regras de negócio

| Campo | Taxa padrão |
|---|---|
| Comissão | 15% |
| Imposto | 10% |
| Desconto Operacional | 20% |

Todas as taxas são configuráveis por collab.

## Stack

- HTML5 + CSS3 + Vanilla JavaScript
- `localStorage` como banco de dados
- [XLSX.js](https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js) — importação de planilhas
- [LZ-String](https://cdnjs.cloudflare.com/ajax/libs/lz-string/1.4.4/lz-string.min.js) — compressão de dados
- Fontes: DM Serif Display · Space Mono · Syne (Google Fonts)

## Como usar

Acesse diretamente pelo link público — nenhuma instalação necessária.  
Os dados são salvos localmente no navegador via `localStorage`.

---

*Ciclo da Arte © 2025*
