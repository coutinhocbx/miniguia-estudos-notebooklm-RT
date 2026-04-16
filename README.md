# Projeto NotebookLM - Reforma Tributária no Brasil
## Projeto de estudo sobre a Reforma Tributária no Brasil, com foco em análise de fontes, uso de IA (NotebookLM) e desenvolvimento de habilidades de engenharia de prompts.

Este projeto foi desenvolvido como parte de um desafio do bootcamp Accenture - Python para Análise e Automação de Dados, com o objetivo de explorar o uso do NotebookLM como ferramenta de apoio ao aprendizado.

O tema escolhido foi Reforma Tributária no Brasil, considerando o atual cenário de transição do sistema tributário brasileiro e a dificuldade de compreensão das informações disponíveis, geralmente apresentadas em linguagem técnica e complexa.

Os objetivos deste estudo incluem compreender os principais pontos da Reforma Tributária, traduzir conceitos complexos para uma linguagem mais acessível e desenvolver habilidades de engenharia de prompts através da utilização de IA para geração de resumos, mapas e até insights.

As fontes abaixo foram selecionadas como base principal do estudo, considerando clareza, relevância e confiabilidade:

Perguntas e respostas oficiais sobre a Reforma Tributária (gov.br) <br>
https://www.gov.br/fazenda/pt-br/acesso-a-informacao/acoes-e-programas/reforma-tributaria/arquivos/perguntas-e-respostas-reforma-tributaria_.pdf 

Emenda Constitucional da Reforma Tributária (EC 132) <br>
https://www.planalto.gov.br/ccivil_03/constituicao/emendas/emc/emc132.htm

Lei Complementar nº 214 (regulamentação de IBS e CBS) <br>
https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp214.htm <br>

Orientações da Receita Federal sobre a reforma do consumo <br>
https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/acoes-e-programas/programas-e-atividades/reforma-consumo/orientacoes-2026

Guia explicativo com análise de mercado (TaxGroup) <br>
https://www.taxgroup.com.br/intelligence/reforma-tributaria-2026-guia-completo-sobre-o-que-muda-e-a-transicao/

Foi necessário uso de fontes complementares, visando perguntas mais específicas para usuários com maior conhecimento contextual. Reforço que todo o material é público, de qualidade e contribuiu para aprofundamento do entendimento sobre o tema:<br>
https://sebraepr.com.br/wp-content/uploads/2025/09/PUB_Reforma-Tributaria-e-seus-Impactos-nos-Pequenos-Negocios.pdf 

https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp123.htm

https://www.planalto.gov.br/ccivil_03/leis/l5172compilado.htm

https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp227.htm

https://www.youtube.com/watch?v=nukrR3WNa1k

https://www.youtube.com/watch?v=OY4YH2npx0c

https://www.youtube.com/watch?v=VYwrYGLQPGg

### Prompts utilizados
"Explique a Reforma Tributária de forma simples"

"Quais são as principais mudanças da Reforma Tributária?"

"Explique a diferença entre IBS e CBS"

"Resuma os impactos da reforma para consumidores"

"Crie um resumo estruturado com base nas fontes fornecidas"

### Dificuldades encontradas
- Linguagem técnica das fontes legais dificultou a interpretação inicial
- Respostas da IA às vezes simplificavam demais o conteúdo
- Necessidade de validação constante nas fontes oficiais
- Confusão entre diferentes normas e etapas da reforma

### Estratégias de melhoria
- Tornar os prompts mais específicos
- Solicitar exemplos práticos
- Pedir comparações entre cenário atual e novo modelo

### Mini Guia de Estudo
- A Reforma Tributária busca simplificar a tributação sobre o consumo no Brasil
- Substituição de tributos como PIS, Cofins, ICMS e ISS
- Criação do IBS (estadual/municipal) e CBS (federal)
- Adoção do modelo de IVA (Imposto sobre Valor Agregado)
- Implementação gradual por meio de período de transição

### Glossário utilizado nas possíveis respostas

IVA Dual (Imposto sobre Valor Agregado Dual): Modelo que unifica a tributação sobre o consumo, dividindo a competência entre a União e os entes subnacionais (Estados e Municípios).

CBS (Contribuição sobre Bens e Serviços): Tributo de competência federal que substitui o PIS e a COFINS.

IBS (Imposto sobre Bens e Serviços): Tributo de competência compartilhada entre Estados e Municípios, que substitui o ICMS e o ISS.

IS (Imposto Seletivo): Popularmente chamado de "imposto do pecado", incide sobre produtos e serviços prejudiciais à saúde ou ao meio ambiente, substituindo o caráter extrafiscal do IPI.

CGIBS (Comitê Gestor do Imposto sobre Bens e Serviços): Entidade pública sob regime especial responsável por administrar, arrecadar e fiscalizar o IBS de forma unificada para Estados e Municípios.

DTE (Domicílio Tributário Eletrônico): Canal de comunicação eletrônica obrigatório e unificado para notificações e intimações do fisco.

PNCT (Programa Nacional de Conformidade Tributária): Programa voluntário que incentiva a regularidade fiscal, oferecendo benefícios como prazos ampliados e redução de multas.

UPF (Unidade Padrão Fiscal): Unidade de referência (inicialmente R$ 200,00) utilizada para o cálculo de multas proporcionais durante o período de transição.


ADCT (Ato das Disposições Constitucionais Transitórias): Parte da Constituição que abriga as regras específicas e o cronograma da transição tributária até 2033.

ClassTrib (Classificação Tributária): Novo nível de detalhamento nos documentos fiscais para identificar o motivo exato de uma alíquota zero, isenção ou redução no IBS/CBS.

NCM/SH (Nomenclatura Comum do Mercosul / Sistema Harmonizado): Código padrão usado para classificar mercadorias e determinar o tratamento tributário.

NBS (Nomenclatura Brasileira de Serviços): Classificação utilizada para identificar serviços, especialmente aqueles com direito a alíquotas reduzidas.

FNDR (Fundo Nacional de Desenvolvimento Regional): Fundo destinado a reduzir desigualdades regionais e sociais, compensando estados pelo fim da "guerra fiscal".

ITCMD (Imposto sobre Transmissão Causa Mortis e Doação): Tributo estadual sobre heranças e doações, que passa a ter alíquotas progressivas e novas regras para bens no exterior.

ZFM (Zona Franca de Manaus): Região que mantém seu diferencial competitivo garantido pela reforma por meio de mecanismos como créditos presumidos e ajustes no IPI.

### Prompts reutilizáveis
"Explique [conceito] de forma simples e objetiva"

"Resuma [tema] em tópicos"

"Compare o sistema atual com o novo modelo tributário"

"Explique o impacto da Reforma Tributária no [tema]"

"Crie um guia de revisão rápida sobre [tema]"


Por fim, este projeto me permitiu desenvolver a habilidade de simplificar conteúdos complexos, melhorar a formulação de prompts e entender a importância da validação de informações através do uso da IA como ferramenta de apoio ao estudo estruturado.

📄  Projeto desenvolvido para fins educacionais em bootcamp. As fontes utilizadas são públicas e pertencem aos seus respectivos autores e instituições, sendo apenas referenciadas e organizadas para fins de estudo com apoio do NotebookLM.
