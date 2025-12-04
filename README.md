# Relatório Power BI - Análise Financeira

## Visuais criados

### 🗺️ Visual Mapa 1
- **Tipo:** Mapa coroplético
- **Objetivo:** Mostrar a soma de *Sales* e *Units Sold* por país
- **Campos utilizados:**
  - Localização: `Country`
  - Valores: `Sales` (Soma), `Units Sold` (Soma)
  - Tooltip: `Profit`, `Gross Sales`

### 🗺️ Visual Mapa 2
- **Tipo:** Mapa coroplético
- **Objetivo:** Mostrar a soma de *Profit* por país
- **Campos utilizados:**
  - Localização: `Country`
  - Valores: `Profit` (Soma)
  - Tooltip: `Sales`, `Units Sold`

### Visual de Rosca
- **Tipo:** Gráfico de pizza
- **Objetivo:** Mostrar a distribuição do *Profit* por segmento
- **Campos utilizados:**
  - Legenda: `Segment`
  - Valores: `Profit` (Soma)
  - Tooltip: `Sales`, `Units Sold`

---

## Ajustes realizados
- **Disposição dos visuais:** organizada em layout limpo e intuitivo:
  - Mapas lado a lado na parte superior
  - Gráfico de pizza centralizado abaixo
- **Nomes dos visuais modificados:**
  - Mapa 1 → "Vendas e Unidades por País"
  - Mapa 2 → "Lucro por País"
  - Pizza → "Lucro por Segmento"
- **Campos de tooltip revisados:** adicionados `Sales`, `Units Sold` e `Profit` para contexto adicional.

---

## Publicação
- Relatório publicado no Power BI Service.
- Compartilhado como suplemento no PowerPoint para apresentações.
- Caso não haja PowerPoint disponível, o projeto foi salvo diretamente no Power BI Desktop (`.pbix`).

---

## Estrutura do projeto
- **Fonte de dados:** `Financial Sample.xlsx`
- **Ferramenta:** Microsoft Power BI
- **Saída:** Relatório interativo com mapas e gráfico de pizza
