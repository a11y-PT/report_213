---
website: "Fundo Rainha D. Leonor"          # Entre as aspas escreve o nome do website
date: "30/10/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://frdl.scml.pt"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://frdl.scml.pt/acessibilidade." # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
a11y_statement_date: "24/09/2026" # Data da declaração de acessibilidade
owner: "Santa Casa da Misericórdia"         # Entre as aspas escrever o nome do owner do website
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "dd/mm/aaaa a dd/mm/aaaa" # Entre as aspas escreve data de início e data de fim no formato 31/12/1999 a 31/12/2000
status: "A aguardar correções da entidade" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Sítio Web: {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="30102026_report.html">(30/10/2026). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Web (v.1.0.4)</small></p>
