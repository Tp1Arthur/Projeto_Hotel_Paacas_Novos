<div align="center">

<img src="https://raw.githubusercontent.com/Tp1Arthur/Projeto_Hotel_Paacas_Novos/main/logo.png" alt="Pacaás Novos Hotel" width="200">

<br>

# `S P R I N T   0 1`
### D O C U M E N T O &nbsp;D E &nbsp;E S P E C I F I C A Ç Ã O &nbsp;E &nbsp;R E Q U I S I T O S

*O registro do processo: da primeira ideia rascunhada ao documento final entregue.*

<br>

<img src="https://placehold.co/200x4/3E5525/3E5525.png" width="200" height="4">

<br><br>

[![Sprint](https://img.shields.io/badge/SPRINT-01-2F471A?style=for-the-badge&labelColor=D4A32A)](#-o-que-foi-a-sprint-1)
[![Prazo](https://img.shields.io/badge/PRAZO-06%2F09%2F2026-2F471A?style=for-the-badge&labelColor=D4A32A)](#-o-que-foi-a-sprint-1)
[![Peso](https://img.shields.io/badge/PESO-20%20PONTOS-2F471A?style=for-the-badge&labelColor=D4A32A)](#-o-que-foi-a-sprint-1)
[![Versões](https://img.shields.io/badge/8%20VERSÕES-V1%20→%20V6-2F471A?style=for-the-badge&labelColor=D4A32A)](#-linha-do-tempo-das-versões)

</div>

<br>
<p align="center">
<img src="https://placehold.co/160x3/3E5525/3E5525.png" height="3">
<img src="https://placehold.co/160x3/2F471A/2F471A.png" height="3">
<img src="https://placehold.co/160x3/D4A32A/D4A32A.png" height="3">
<img src="https://placehold.co/160x3/C99A28/C99A28.png" height="3">
</p>
<br>

## 🧭 Neste documento

<div align="center">
<table>
<tr>
<th align="center">📖 Contexto</th>
<th align="center">🛠️ Processo</th>
<th align="center">🏁 Entrega</th>
</tr>
<tr valign="top">
<td>

[O que foi a Sprint 1](#-o-que-foi-a-sprint-1)
[Objetivo](#-objetivo-da-sprint)
[Divisão de trabalho](#-divisão-de-trabalho)

</td>
<td>

[Arquivos enviados](#-arquivos-originais-enviados)
[Como foi feito](#️-como-foi-feito)
[Linha do tempo](#-linha-do-tempo-das-versões)

</td>
<td>

[Mudanças simples](#-mudanças-simples)
[Mudanças brutais](#-mudanças-brutais)
[Resultado final](#-resultado-final)

</td>
</tr>
</table>
</div>

<br>
<div align="center"><sub>▽ ▽ ▽</sub></div>

## 📖 O que foi a Sprint 1

A **Sprint 1** é a primeira etapa do Projeto de Software da disciplina de **Engenharia de Software**, correspondente ao **Capítulo 01** do projeto: o **Documento de Especificação e Documento de Requisitos**.

<table>
<tr><td width="30%"><b>📌 Escopo</b></td><td>Sistema comercial de arquitetura <b>desktop</b> ou <b>web (PC)</b></td></tr>
<tr><td><b>🗓️ Abertura</b></td><td>Sábado, 29 de agosto de 2026 — 15:09</td></tr>
<tr><td><b>⏰ Prazo final</b></td><td>Domingo, 6 de setembro de 2026 — 23:59</td></tr>
<tr><td><b>⚖️ Peso</b></td><td>20 pontos, avaliando (a) formatação + uso do gerenciador de tarefas, e (b) qualidade dos artefatos</td></tr>
<tr><td><b>🗂️ Ferramenta de gestão</b></td><td>Taiga (Kanban), com tarefas divididas pelo líder e revisão em pares registrada</td></tr>
</table>

> Segundo a orientação da disciplina, todo projeto de software é também **um documento de cunho científico** — por isso, entrevistas com o cliente fictício e decisões de modelagem foram documentadas, e referências de mercado (Accor, Booking, Marriott, entre outras) foram usadas para embasar o domínio.

<br>

## 🎯 Objetivo da Sprint

<div align="center">
<table><tr><td align="center" style="padding:16px">

### *Produzir, de forma colaborativa, o Domínio da Informação, os Requisitos Primários, os Requisitos Funcionais (RF) e os Requisitos Não Funcionais (RNF) do sistema hoteleiro Pacaás Novos — organizados, revisados em pares e formatados em um único documento final.*

</td></tr></table>
</div>

<br>

## 👥 Divisão de Trabalho

Os **15 requisitos primários** do domínio foram distribuídos entre os cinco integrantes da equipe, cada um responsável por levantar os RFs e RNFs de três módulos:

<div align="center">

| Integrante | Requisitos primários sob responsabilidade |
|:--|:--|
| **Ariele** | 1. Cadastro de hóspedes · 2. Reservas · 3. Quartos |
| **Arthur** | 4. Check-in/Check-out · 5. Consumos · 6. Estoque |
| **Jonas** | 7. Pacotes e tarifas · 8. Financeiro · 9. Funcionários |
| **Yuri Alencar** | 10. Limpeza e manutenção · 11. Eventos e salas · 12. Comunicações |
| **Yves** | 13. Notas fiscais e recibos · 14. Controle de acesso · 15. Relatórios e dashboards |

</div>

Cada entrega passou por **revisão em pares** antes de ser incorporada ao documento final — prática registrada no Taiga, conforme exigido pela disciplina.

<br>
<div align="center"><sub>▽ ▽ ▽</sub></div>

## 📂 Arquivos Originais Enviados

Ao todo, **8 arquivos** documentam o processo de construção — dois núcleos de trabalho que caminharam em paralelo (Requisitos Funcionais e Requisitos Não Funcionais) até serem unificados:

<div align="center">

| Arquivo | Frente de trabalho | Conteúdo |
|:--|:--:|:--|
| `Requisitos_Nao_Funcionais_Hotel.docx` | 🛡️ RNF | 1ª versão dos RNFs, já em tabelas por módulo (Nome/ID/Descrição + ID RNF/Descrição/Categoria) |
| `Requisitos_Nao_Funcionais_Hotel_v2.docx` | 🛡️ RNF | Revisão de redação e ajuste de categorias ISO/IEC 25010 |
| `RFeRNF_Hotel - V2.docx` | ⚙️ RF | RFs no estilo curto ("Cadastrar cliente"), com lista de Objetos Computacionais por módulo |
| `RFeRNF_Hotel requisito 13 a 15 editado.docx` | ⚙️ RF + RNF | **Versão alternativa e mais extensa** — RFs e RNFs reescritos como frases completas ("O sistema deve permitir...") para todos os 15 módulos |
| `RFeRNF_Hotel_V3.docx` | 🔗 Unificado | Primeira fusão: RF (estilo curto) + RNF (tabela por categoria), por módulo, com link do diagrama drawDB |
| `RFeRNF_Hotel_V4.docx` | 🔗 Unificado | Ajustes finos de formatação sobre a V3 |
| `RFeRNF_Hotel v5.docx` | 🔗 Unificado | Renumeração de RFs e reescrita de RNFs incompletos/imprecisos |
| `RFeRNF_Hotel v6.docx` | ✅ Final | Adição da capa (título, Sprint, integrantes) — versão entregue |

</div>

<br>

## 🛠️ Como foi feito

<table>
<tr><td align="center" width="6%">1️⃣</td><td><b>Levantamento individual</b> — cada integrante redigiu o requisito primário e os RFs/RNFs de seus três módulos, com apoio de pesquisa de mercado (Accor, Booking, Marriott, Let's Atlantica) e da norma <b>ISO/IEC 25010</b> para classificar os RNFs em categorias (Adequação, Eficiência, Compatibilidade, Usabilidade, Confiabilidade, Segurança, Manutenibilidade, Portabilidade).</td></tr>
<tr><td align="center">2️⃣</td><td><b>Duas frentes em paralelo</b> — os RFs foram escritos em estilo <i>curto</i> (ex.: <code>RF01 – Cadastrar cliente</code>) com objetos computacionais explícitos, enquanto os RNFs nasceram diretamente em formato de tabela, um "cartão" por módulo.</td></tr>
<tr><td align="center">3️⃣</td><td><b>Experimento de formato</b> — paralelamente, testou-se reescrever <i>todo</i> o documento (RF e RNF, 15 módulos) em frases completas no padrão "O sistema deve permitir...", gerando mais de 130 RFs e 97 RNFs detalhados. Esse formato foi comparado ao estilo curto para decidir qual seguiria como padrão oficial.</td></tr>
<tr><td align="center">4️⃣</td><td><b>Revisão em pares</b> — cada bloco produzido foi revisado por outro integrante, com correções registradas como tarefas no Taiga.</td></tr>
<tr><td align="center">5️⃣</td><td><b>Unificação</b> — o líder consolidou as duas frentes (RF + RNF) em um único documento, módulo a módulo, em tabelas padronizadas, e incluiu o link do diagrama de entidades no drawDB.</td></tr>
<tr><td align="center">6️⃣</td><td><b>Revisão de consistência</b> — releitura completa para corrigir numeração quebrada, RNFs incompletos e descrições ambíguas.</td></tr>
<tr><td align="center">7️⃣</td><td><b>Formatação final</b> — capa com título, nome da Sprint e integrantes; exportação para PDF para envio no AVA.</td></tr>
</table>

<br>
<div align="center"><sub>▽ ▽ ▽</sub></div>

## 🕒 Linha do Tempo das Versões

<div align="center">

```
 RNF v1 ──▶ RNF v2 ┐
                    ├──▶  V3  ──▶  V4  ──▶  v5  ──▶  v6 (FINAL)
  RF v2 ────────────┘
        ╲
         ╲──▶ "req. 13 a 15 editado" (formato longo, avaliado e não adotado)
```

</div>

| Etapa | O que mudou |
|:--:|:--|
| **RNF v1 → v2** | Ajuste de redação e precisão das descrições de cada RNF |
| **RF v2 → V3** | RF (curto) + RNF (tabela) unificados por módulo; inclusão do diagrama drawDB |
| **V3 → V4** | Ajustes de formatação (sem alteração de conteúdo) |
| **V4 → v5** | Renumeração completa dos RFs após fusões de módulos; reescrita de RNFs incompletos |
| **v5 → v6** | Inclusão da capa oficial (título, Sprint, autores) — versão entregue |

<br>

## ✏️ Mudanças Simples

Ajustes pontuais de redação e formatação, sem impacto na estrutura do documento:

- Correção de digitação e padronização de travessões (`–` no lugar de `-`) na numeração dos RFs.
- Remoção de marcadores duplicados (`- -`) na lista de Objetos Computacionais.
- Reescrita de RNFs vagos para versões mais específicas e verificáveis — por exemplo, o RNF01 de Funcionários passou de:
  > *"Preservação do histórico do funcionário de forma íntegra, sem possibilidade de edição ou exclusão."*

  para:
  > *"O sistema deve registrar automaticamente no histórico do funcionário as alterações realizadas em seu cadastro, mantendo os registros de forma íntegra, sem permitir edição ou exclusão posterior."*

  — deixando explícito **quando** o histórico é criado, não só que ele é imutável.
- Adição de RNFs que faltavam em alguns módulos (ex.: dois RNFs novos sobre composição da fatura e integração automática dos consumos, no módulo de Check-in/Check-out).

<br>

## 💥 Mudanças Brutais

Decisões estruturais que alteraram o documento de forma significativa:

<table>
<tr>
<td width="4%" align="center">🔀</td>
<td><b>Fusão de objetos computacionais.</b> Os objetos <code>tarifa</code> e <code>pagamento</code> do módulo de Reservas foram unificados em <code>recebimento</code>, eliminando RFs redundantes (de 12 RFs em Reservas/Tarifas/Pagamentos para 8 RFs em Reservas/Recebimento). Motivo: pagamento e tarifa tratavam do mesmo fluxo financeiro da reserva; separá-los gerava CRUDs duplicados sem necessidade real de negócio.</td>
</tr>
<tr>
<td align="center">🔀</td>
<td><b>Consumos deixaram de ter RFs próprios.</b> O módulo de Consumos (<code>faturaitem</code>) tinha 4 RFs de CRUD completo (Cadastrar/Consultar/Atualizar/Deletar fatura item); passou a ser tratado apenas como Requisito Não Funcional de integração da fatura, já que os consumos são sempre lançados <i>dentro</i> do fluxo de hospedagem/fatura, não como uma tela independente. Isso reduziu retrabalho e refletiu melhor a operação real de um hotel.</td>
</tr>
<tr>
<td align="center">🔢</td>
<td><b>Renumeração geral dos RFs.</b> Toda vez que um módulo perdia ou ganhava requisitos, a numeração de <b>todos</b> os RFs seguintes precisava ser recalculada manualmente (ex.: RF29 virou RF24 depois da fusão do módulo de Reservas). Esse foi o ajuste mais trabalhoso e repetido entre as versões V4 → v5.</td>
</tr>
<tr>
<td align="center">📐</td>
<td><b>Dois formatos concorrentes de redação.</b> Chegou a existir uma versão completa do documento (<code>requisito 13 a 15 editado.docx</code>) reescrevendo <b>todos</b> os RFs e RNFs como frases longas e descritivas ("O sistema deve permitir cadastrar hóspedes com nome completo, CPF..."), em vez do padrão curto ("RF01 – Cadastrar cliente" + objetos computacionais). A equipe optou pelo <b>formato curto + tabela de RNF por categoria</b> por ser mais objetivo, mais fácil de rastrear (RF ↔ objeto computacional) e mais alinhado ao padrão dos demais grupos/professor.</td>
</tr>
<tr>
<td align="center">🗺️</td>
<td><b>Inclusão do diagrama de entidades.</b> A partir da V3, passou a constar no topo do documento o link do modelo de dados feito no drawDB, amarrando visualmente os objetos computacionais citados em cada módulo às entidades reais do banco.</td>
</tr>
<tr>
<td align="center">📄</td>
<td><b>Adição da capa formal.</b> Somente na versão final (v6) o documento ganhou capa com título do projeto, identificação da Sprint e nome completo dos integrantes — exigência de formatação da disciplina, que penaliza fortemente sua ausência.</td>
</tr>
</table>

<br>
<div align="center"><sub>▽ ▽ ▽</sub></div>

## 🏁 Resultado Final

<div align="center">

| | |
|:--:|:--:|
| 🧩 | **15** módulos / requisitos primários |
| ⚙️ | **141** Requisitos Funcionais |
| 🛡️ | **~97** Requisitos Não Funcionais, classificados por ISO/IEC 25010 |
| 🗺️ | Diagrama de entidades publicado no drawDB |
| 📄 | Documento único, com capa, formatado e exportado em **PDF** |
| ✅ | Entregue pelo líder no AVA, dentro do prazo de 06/09/2026 |

</div>

A versão **v6** consolidou o trabalho de todas as frentes — RF, RNF, diagrama e formatação — em um único documento coeso, servindo de base direta para os arquivos `hotel (1).docx` e `RFeRNF_Hotel v3.docx` publicados no repositório e para o [README principal do projeto](README.md).

<br>

---

<div align="center">

<img src="https://placehold.co/200x4/D4A32A/D4A32A.png" width="200" height="4">

<br><br>

### 🏔️ SPRINT 1 · PROJETO DE SOFTWARE

**Instituto Federal de Rondônia — IFRO**

<sub>Ariele de Souza Mourão · Arthur Ricardo de Jesus Silva · João Carlos da Silva Terras · Jonas Neves Pereira · Yves Alencar Sampaio</sub>

<br><br>

<img src="https://raw.githubusercontent.com/Tp1Arthur/Projeto_Hotel_Paacas_Novos/main/logo.png" width="60">

**`PACAÁS NOVOS HOTEL`**

</div>
