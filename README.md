#  BluaDiagnostics — Sprint 2

**Care Plus | Blua Digital Health Assistant**

---

##  Integrantes

| Nome | RM |
|------|----|
| Miguel Fontes Costa | RM566761 |
| Gabriel de Paula Gil | RM567286 |
| Thiago Garcia | RM568107 |
| Pedro César Branco | RM567971 |
| Diego Leite Asprino | RM561662 |

---

##  O que está no código

O arquivo `BluaDiagnostics_Sprint2.ipynb` contém tudo em um único notebook com 10 células:

| Célula | Conteúdo |
|--------|----------|
| 1 | Instalação automática de dependências |
| 2 | Configuração segura da API Key (via `getpass`, sem expor no código) |
| 3 | Base de conhecimento clínica Care Plus (6 documentos) |
| 4 | Pipeline RAG — FAISS + Sentence Transformers (chunking + embeddings + retrieval) |
| 5 | 5 Tools via function calling: histórico do paciente, cobertura do plano, agendamento de teleconsulta, sinais vitais e escalada humana |
| 6 | 3 Agentes (Triagem, Prescrição, Escalada) + Supervisor + Guardrails (red flag, jailbreak, out-of-scope) |
| 7 | 5 cenários de teste prontos (happy path, red flag, jailbreak, fora do escopo) |
| 8 | Suite de evals automatizada com 9 casos — gera `evals/sprint2_results.json` |
| 9 | Interface de chat interativa com widgets visuais |
| 10 | Gera `requirements.txt`, `.env.example` e `.gitignore` |

**Paciente demo:** Maria Silva, 34 anos, hipertensão, Losartana 50mg, última consulta 03/2026 — Dr. João.

---

##  Como executar

### 1. Instale o Python
Baixe em **python.org/downloads** (versão 3.10 ou superior).
Na instalação, marque a opção **"Add Python to PATH"**.

### 2. Instale o Jupyter
Abra o terminal e execute:
```bash
pip install jupyter
```

### 3. Abra o notebook
```bash
jupyter notebook BluaDiagnostics_Sprint2.ipynb
```

### 4. Execute as células em ordem
Clique no botão  de cada célula, começando pela Célula 1.
Aguarde cada uma terminar antes de passar para a próxima.

### 5. Insira sua API Key
Na Célula 2, um campo de texto vai aparecer — cole sua chave Anthropic (`sk-ant-...`) e pressione Enter. Ela não ficará visível na tela.

>  Nunca coloque a API Key diretamente no código ou commite o arquivo `.env` no GitHub.

---

##  API KEY

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

