# Registro do uso da IA

**Estudante:** Luidy Costa dos Santos
**Caso:** CrowdStrike Falcon Sensor Outage (Julho de 2024)
**Ferramenta(s) usada(s):** Gemini / ChatGPT (Modelo de Linguagem)

> Registre todos os prompts relevantes, na ordem em que foram usados. Não é preciso colar a resposta inteira da IA: resuma o que ela respondeu e diga o que você fez com isso.

---

## Prompt 1

**Data:** 06/10/2026

**Prompt:**

Resuma a falha da CrowdStrike de julho de 2024. Qual foi o sistema afetado, a causa técnica no arquivo de canal (Channel File 291), os impactos mundiais e quais os relatórios oficiais de Análise de Causa Raiz (RCA)?

**Resumo da resposta:** A IA explicou que uma atualização do Falcon Sensor para Windows contendo o arquivo `Channel File 291` causou tela azul (BSOD) em 8,5 milhões de máquinas Windows no mundo todo. Afetou aeroportos, bancos e hospitais. O relatório oficial é o External Root Cause Analysis (RCA) da CrowdStrike.

**O que fiz com isso:** Usei a base para montar as Seções 1, 2 e 3 do README.md e definir quais pontos checar contra a documentação da CrowdStrike e Microsoft.

---

## Prompt 2

**Data:** 06/10/2026

**Prompt:**

Faça uma análise de Qualidade de Software (Unidade I) do apagão da CrowdStrike: identifique erros de Verificação vs Validação, QA vs QC, classificação no modelo PAF e visões de Garvin.

**Resumo da resposta:** A IA indicou falha no Controle de Qualidade (QC) do Validador de Conteúdo que deixou passar o arquivo corrompido, e falha de QA na falta de implantação em fases (staged deployment). Mencionou prejuízos de bilhões (custo de falha externa).

**O que fiz com isso:** Revisei os conceitos, ajustei as explicações para a linguagem da disciplina com minhas próprias palavras e preenchi a Seção 4 do README.md.

---

## Prompt 3

**Data:** 06/10/2026

**Prompt:**

Gere 5 afirmações específicas sobre a causa técnica do bug do CSAgent.sys e a política de deploy da CrowdStrike para eu checar contra o relatório oficial da CrowdStrike (RCA).

**Resumo da resposta:** A IA listou afirmações sobre o erro de ponteiro/acesso à memória inválida no driver `CSAgent.sys`, falha no Content Validator no ambiente de QA e a implantação simultânea global em vez de implantação por fases.

**O que fiz com isso:** Montei a tabela da Seção 6 do README.md, conferindo cada afirmação com o relatório oficial da CrowdStrike e da Microsoft.

---

## Balanço final

- **Total de prompts registrados:** 3
- **Prompt que mais ajudou e por quê:** Prompt 3, pois me permitiu confrontar diretamente os termos técnicos de kernel do Windows com a documentação oficial.
- **Prompt que gerou a resposta mais problemática e por quê:** Prompt 1, pois a IA inicialmente alegou que se tratava de um "ataque hacker" ou "vírus", confundindo uma falha interna de atualização com um incidente de segurança cibernética externa.
- **Se eu fizesse de novo, perguntaria à IA de outra forma assim:** Pediria diretamente a análise da falha focando nas camadas do driver de modo kernel do Windows (Kernel-mode driver).
