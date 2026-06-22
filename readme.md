# Travel Planning

Trabalho final da cadeira de engenharia de Requisitos

# Equipe

- Ernesto Dalva
- Lucas Cabral
- José Alberto
- Guilherme Galvão
- Tiago Mamede

## Links importantes

docs(primeira entrega)

```
https://docs.google.com/document/d/1jLB9Yxtayv4dCQtP0uUrSLfZ26l13PBpWmABeeOp2fw/edit?tab=t.0#heading=h.gmlshb1h4vo2
```

Figma

```
https://www.figma.com/design/rrRjt9cdopz6585Scgbdab/Travel-Planning?node-id=0-1&t=Fx5uF5UZxy9GgyDO-1
```

docs(requisitos)

```
https://docs.google.com/document/d/1rlgwg_IXVa_m1FGJnBPioBf1nW0noKdgyUpe6sHonGQ/edit?tab=t.jeddu51ocs8j
```

Apresentação(figma)

```
https://www.figma.com/proto/rrRjt9cdopz6585Scgbdab/Travel-Planning?node-id=1-2&p=f&t=c98WRXtetCZROJCu-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2
```

Diagramas

```
https://excalidraw.com/#room=05bb312e8eb339a6f300,-nJa5ykSdIxt7iuD3NZHFA
```

## Estrutura

```
TM01 - Planejamento colaborativo da viagem
│
├── EP01 Criar e gerenciar viagens em grupo
├── EP02 Gerenciar participantes da viagem
├── EP03 Configurar informações iniciais da viagem
└── EP04 Avaliar e decidir opções da viagem em grupo


TM02 - Geração de roteiro com IA
│
├── EP05 Identificar preferências dos participantes
├── EP06 Gerar recomendações personalizadas
├── EP07 Criar roteiro inteligente



TM03 - Organização do itinerário
│
├── EP08 Organizar cronograma da viagem
├── EP09 Gerenciar atividades
└── EP10 Comunicar alterações


TM04 - Modelo de negócio e parcerias
│
├── EP11 Exibir conteúdo patrocinado
├── EP12 Gerenciar assinaturas premium
```

# Matrizes de Rastreabilidade

## Requisitos de Negócio x Requisitos Funcionais

| RN   | Requisitos Funcionais Relacionados                   |
| ---- | ---------------------------------------------------- |
| RN01 | RF03, RF08, RF09, RF10, RF11                         |
| RN02 | RF01, RF02, RF03, RF08, RF09, RF10, RF11             |
| RN03 | RF04, RF05, RF06, RF07, RF15                         |
| RN04 | RF12, RF13, RF14, RF15                               |
| RN05 | RF04, RF05, RF06, RF07, RF15                         |
| RN06 | RF01, RF02, RF03, RF08, RF09, RF10, RF11, RF12, RF13 |

---

## Regras de Negócio x Requisitos Funcionais

| RGN   | Requisitos Funcionais Relacionados |
| ----- | ---------------------------------- |
| RGN01 | RF01                               |
| RGN02 | RF01, RF02                         |
| RGN03 | RF06, RF08                         |
| RGN04 | RF03                               |
| RGN05 | RF03                               |
| RGN06 | RF04, RF05, RF06                   |
| RGN07 | RF13                               |
| RGN08 | RF08                               |
| RGN09 | RF01, RF09, RF10, RF11             |
| RGN10 | RF12, RF14, RF15                   |

---

## Requisitos Funcionais x Histórias de Usuário

| RF   | Histórias de Usuário |
| ---- | -------------------- |
| RF01 | HU01, HU02, HU05     |
| RF02 | HU03, HU04           |
| RF03 | HU06, HU07           |
| RF04 | HU08                 |
| RF05 | HU09                 |
| RF06 | HU10                 |
| RF07 | HU11                 |
| RF08 | HU12, HU15           |
| RF09 | HU13                 |
| RF10 | HU14                 |
| RF11 | HU16                 |
| RF12 | HU17                 |
| RF13 | HU18                 |
| RF14 | HU19                 |
| RF15 | HU20                 |

---

## Histórias de Usuário x Requisitos Não Funcionais

| HU   | RNF Relacionados           |
| ---- | -------------------------- |
| HU01 | RNF01, RNF02, RNF07, RNF08 |
| HU02 | RNF01, RNF02, RNF06        |
| HU03 | RNF06, RNF07               |
| HU04 | RNF06, RNF07               |
| HU05 | RNF07, RNF08               |
| HU06 | RNF01, RNF04, RNF09        |
| HU07 | RNF04, RNF09               |
| HU08 | RNF03, RNF05               |
| HU09 | RNF03, RNF05               |
| HU10 | RNF03, RNF05               |
| HU11 | RNF01, RNF02               |
| HU12 | RNF09                      |
| HU13 | RNF01, RNF02, RNF04        |
| HU14 | RNF01, RNF04, RNF06        |
| HU15 | RNF09                      |
| HU16 | RNF04, RNF06               |
| HU17 | RNF01, RNF11               |
| HU18 | RNF12                      |
| HU19 | RNF08                      |
| HU20 | RNF03, RNF05, RNF10        |

---

## Requisitos Funcionais x Requisitos Não Funcionais

| RF   | RNF Relacionados                  |
| ---- | --------------------------------- |
| RF01 | RNF01, RNF02, RNF06, RNF07, RNF08 |
| RF02 | RNF06, RNF07                      |
| RF03 | RNF04, RNF09                      |
| RF04 | RNF03, RNF05                      |
| RF05 | RNF03, RNF05                      |
| RF06 | RNF03, RNF05                      |
| RF07 | RNF01, RNF02                      |
| RF08 | RNF09                             |
| RF09 | RNF01, RNF02, RNF04               |
| RF10 | RNF01, RNF04, RNF06               |
| RF11 | RNF04, RNF06                      |
| RF12 | RNF01, RNF11                      |
| RF13 | RNF12                             |
| RF14 | RNF08                             |
| RF15 | RNF03, RNF05, RNF10               |

# Requisitos de Processo

## RP01 – Utilização de protótipos para validação

Descrição:
A equipe deve utilizar protótipos de interface para apoiar a elicitação, validação e refinamento dos requisitos do sistema.

---

## RP02 – Rastreabilidade dos requisitos

Descrição:
Todos os requisitos funcionais devem possuir rastreabilidade com pelo menos uma história de usuário e, quando aplicável, com requisitos de negócio e regras de negócio.

---

## RP03 – Controle de versão dos artefatos

Descrição:
Os artefatos produzidos durante o projeto devem possuir controle de versão, permitindo identificar alterações realizadas ao longo do desenvolvimento.

---

## RP04 – Atualização contínua da documentação

Descrição:
A documentação do projeto deve ser atualizada sempre que ocorrerem alterações significativas nos requisitos, regras de negócio ou protótipos.

---

## RP05 – Desenvolvimento centrado no usuário

Descrição:
As decisões de projeto devem considerar as necessidades dos usuários identificados no sistema, especialmente Organizadores e Participantes de viagens.

---

## RP06 – Consideração dos desafios GrandSI-BR

Descrição:
A equipe deve garantir que os requisitos e protótipos reflitam os desafios GrandSI-BR selecionados:

- Sistemas de Informação Inteligentes sob a Perspectiva Sociotécnica;
- Inteligência Artificial Confiável e Centrada no Ser Humano.

---

## RP07 – Validação dos requisitos pela equipe

Descrição:
Os requisitos levantados devem ser revisados e validados pela equipe antes de serem considerados concluídos.

---

## RP08 – Priorização de funcionalidades essenciais

Descrição:
As funcionalidades relacionadas ao planejamento colaborativo da viagem e geração de roteiros por IA devem possuir prioridade sobre funcionalidades complementares de monetização.

---

## RP09 – Consistência entre requisitos e protótipos

Descrição:
Toda funcionalidade representada nos protótipos deve possuir correspondência nos requisitos do sistema e vice-versa.

---

## RP10 – Documentação das funcionalidades de IA

Descrição:
As funcionalidades que utilizam inteligência artificial devem possuir documentação descrevendo sua finalidade, entradas consideradas e resultados esperados.
