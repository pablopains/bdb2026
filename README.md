# Banco de Dados Biológicos — 2026

**Tópicos Especiais em Ecologia, Conservação e Manejo da Vida Silvestre II: Banco de Dados Biológicos**  
Universidade Federal de Minas Gerais (UFMG) • Instituto de Ciências Biológicas • PPG-ECMVS  
**Código:** DIP BIG863 • **Créditos:** 2 • **Carga horária:** 30 h  
**Curso intensivo:** 11 a 14 de agosto de 2026

## Sobre a disciplina

Esta disciplina apresenta ferramentas e metodologias para **organização, documentação, publicação, intercâmbio, avaliação e reúso de dados biológicos** em ecologia, conservação e manejo da vida silvestre.

O percurso parte da busca e interpretação de dados em diferentes fontes de biodiversidade, passa pela estruturação de dados tabulares e relacionais e culmina na leitura e publicação de dados segundo o padrão **Darwin Core**, incluindo **Simple Darwin Core, Darwin Core Archive (DwC-A), Darwin Core Data Package (DwC-DP), EML e IPT**.

A disciplina também integra **princípios FAIR, licenças, proveniência, versionamento, qualidade e fitness-for-use** ao uso responsável de dados secundários.

## Objetivos

Ao final da disciplina, espera-se que o estudante seja capaz de:

- distinguir tabelas chapadas, dados tidy e estruturas relacionais;
- reconhecer unidades observacionais, entidades, atributos, chaves e relacionamentos;
- navegar, filtrar, baixar e avaliar criticamente dados de biodiversidade;
- aplicar e interpretar o vocabulário Darwin Core;
- compreender a estrutura de Simple Darwin Core, DwC-A e DwC-DP;
- interpretar `meta.xml`, EML, `id`, `coreid`, `rowType` e extensões;
- relacionar metadados, identificadores, licenças, proveniência e qualidade aos princípios FAIR e ao reúso responsável.

## Organização do curso

| Unidade | Questão central | Conteúdo principal |
|---|---|---|
| **Aula 1 — Fontes de dados de biodiversidade** | Onde encontrar dados e como reutilizá-los responsavelmente? | Fontes e infraestruturas de biodiversidade, busca e filtros, produtos de dados, FAIR, licenças, proveniência e qualidade. |
| **Aula 2 — Estruturação de dados tabulares e relacionais** | Por que separar informações em diferentes tabelas pode tornar os dados mais consistentes sem perder as relações que existem entre eles? | Tabelas chapadas, tidy data, entidades, identidade, PK/FK, cardinalidades, JOIN e introdução estrutural ao DwC-A. |
| **Aula 3_4 — Darwin Core e intercâmbio de dados** | Como Darwin Core expressa classes, propriedades, relações e formatos de intercâmbio? | Classes e propriedades Darwin Core, RDF/IRI, DwC-A, Simple Darwin Core, DwC-DP, IPT, publicação, validação e dados legados. |

## Fontes e infraestruturas trabalhadas

Entre as fontes utilizadas na disciplina estão **speciesLink, JABOT, Reflora, Flora e Funga do Brasil, Catálogo Taxonômico da Fauna do Brasil, GBIF, SiBBr, Catalogue of Life, Plants of the World Online (POWO) e iNaturalist**.

Os exemplos preservam, sempre que possível, a estrutura, os campos, as licenças e os metadados efetivamente disponibilizados por cada fonte, evitando forçar equivalências entre produtos diferentes.

## Como usar este repositório

O ponto de entrada local é:

- [`Banco_de_Dados_Biologicos.html`](Banco_de_Dados_Biologicos.html) — índice geral da disciplina, com acesso às aulas, atividades e referências.

Para utilizar todos os materiais e exploradores interativos, **baixe ou clone o repositório mantendo a estrutura de pastas**. Em seguida, abra `Banco_de_Dados_Biologicos.html` em um navegador.

Para projeção em sala, utilize preferencialmente os PDFs das pastas `projecao/`, pois eles preservam a paginação revisada das apostilas.

## Estrutura do repositório

```text
.
├── 00_Disciplina/
│   ├── Ementa.docx
│   ├── Politica_de_atividades_e_avaliacao.docx
│   ├── Roteiro_integrado_da_disciplina.docx
│   └── referencias/
├── 01_Aula_1/
│   ├── Aula_1_Material_do_estudante.docx
│   ├── atividade/
│   ├── data/
│   ├── explorador/
│   ├── gabarito/
│   └── projecao/
├── 02_Aula_2/
│   ├── Aula_2_Material_do_estudante.docx
│   ├── atividade/
│   ├── data/
│   ├── explorador/
│   ├── gabarito/
│   └── projecao/
├── 03_Aula_3_4/
│   ├── Aula_3_4_Material_do_estudante.docx
│   ├── atividade/
│   ├── data/
│   ├── explorador/
│   ├── gabarito/
│   └── projecao/
├── 05_avaliacao/
│   ├── AF1_Resposta_do_estudante.docx
│   ├── Explorador_Questao_8.html
│   ├── AF1_Gabarito_docente.docx
│   └── Planilha_de_acompanhamento_e_correcao.xlsx
├── Banco_de_Dados_Biologicos.html
├── README.md
└── LEIA-ME.txt
```

## Acesso rápido aos materiais

### Documentos da disciplina

- [Ementa](00_Disciplina/Ementa.docx)
- [Roteiro integrado](00_Disciplina/Roteiro_integrado_da_disciplina.docx)
- [Política de atividades e avaliação](00_Disciplina/Politica_de_atividades_e_avaliacao.docx)
- [Referências da disciplina](00_Disciplina/referencias/Referencias_da_disciplina.html)

### Aula 1

- [Material do estudante](01_Aula_1/Aula_1_Material_do_estudante.docx)
- [Projeção em PDF](01_Aula_1/projecao/Aula_1_Projecao.pdf)
- [Explorador da Aula 1](01_Aula_1/explorador/Explorador_Aula1.html)
- [Instruções da Atividade Aula 1](01_Aula_1/atividade/Atividade_Aula_1_Instrucoes.docx)

### Aula 2

- [Material do estudante](02_Aula_2/Aula_2_Material_do_estudante.docx)
- [Projeção em PDF](02_Aula_2/projecao/Aula_2_Projecao.pdf)
- [Explorador da Aula 2](02_Aula_2/explorador/Explorador_Aula2.html)
- [Atividade Aula 2](02_Aula_2/atividade/Atividade_Aula_2.docx)

### Aula 3_4

- [Material do estudante](03_Aula_3_4/Aula_3_4_Material_do_estudante.docx)
- [Projeção em PDF](03_Aula_3_4/projecao/Aula_3_4_Projecao.pdf)
- [Explorador da Atividade Aula 3_4](03_Aula_3_4/explorador/Explorador_Atividade_Aula_3_4.html)
- [Atividade Aula 3_4](03_Aula_3_4/atividade/Atividade_Aula_3_4_Resposta_do_estudante.docx)

### Avaliação final

- [AF1 — resposta do estudante](05_avaliacao/AF1_Resposta_do_estudante.docx)
- [Explorador da Questão 8](05_avaliacao/Explorador_Questao_8.html)

## Avaliação

| Componente | Pontos |
|---|---:|
| Participação | 10 |
| Atividade Aula 1 | 15 |
| Atividade Aula 2 | 15 |
| Atividade Aula 3_4 | 15 |
| Avaliação final integrada — AF1 | 45 |
| **Total** | **100** |

As atividades podem ser discutidas e desenvolvidas em grupo, mas **todas as entregas são individuais**.

## Entregas

Todas as atividades devem ser enviadas para **pablopains@yahoo.com.br**.

- **Atividade Aula 1:** enviar `Atividade Aula 1 - Nome Sobrenome.docx` como anexo e informar, no corpo do e-mail, o link compartilhado para `Atividade Aula 1 - Nome Sobrenome.zip`. O ZIP deve conter somente os arquivos baixados das bases.
- **Atividade Aula 2:** enviar `Atividade Aula 2 - Nome Sobrenome.docx` como anexo.
- **Atividade Aula 3_4:** enviar `Atividade Aula 3_4 - Nome Sobrenome.docx` como anexo.
- **AF1:** enviar `AF1_Sobrenome_Nome.docx` como anexo.

A Atividade Aula 3_4 e a AF1 possuem o mesmo prazo, mas são entregas e notas independentes.

## Referências e documentação técnica

A bibliografia básica e a documentação técnica utilizada estão reunidas em [`00_Disciplina/referencias/`](00_Disciplina/referencias/).

Entre as referências centrais estão trabalhos sobre **FAIR, tidy data, qualidade de dados, Darwin Core e IPT**, além da documentação oficial da TDWG e do GBIF.

## Licenças, proveniência e reúso

Os conjuntos de dados, documentos externos e demais recursos de terceiros mantêm suas **licenças, direitos e requisitos de citação próprios**. Consulte sempre os metadados e a fonte original antes de reutilizá-los.

A licença dos **materiais autorais deste repositório** deve ser definida em um arquivo `LICENSE` antes de uma publicação pública destinada ao reúso por terceiros.

## Versão

Este README foi preparado a partir da **versão de produção v142** dos materiais da disciplina.

O histórico técnico detalhado das versões está em [`LEIA-ME.txt`](LEIA-ME.txt). Para manutenção do repositório no GitHub, recomenda-se futuramente migrar esse histórico para um arquivo `CHANGELOG.md`.
