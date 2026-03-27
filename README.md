# PPGIA - Especialização em Inteligência Artificial Aplicada a Dados Corporativos

**IFGoiano - Campus Urutaí** | Código: 0180614

Repositório com materiais de estudo, notebooks e projetos desenvolvidos durante a Pós-Graduação *Lato Sensu* em **Inteligência Artificial Aplicada a Dados Corporativos** do Instituto Federal Goiano - Campus Urutaí.

## Links

| Recurso | Link |
|---------|------|
| Projeto Pedagógico (PPC) | [PPC_especializacao_em_IA.pdf](https://suap.ifgoiano.edu.br/media/documentos/arquivos/PPC_especializacao_em_IA.pdf) |
| Portal Acadêmico (SUAP) | [suap.ifgoiano.edu.br](https://suap.ifgoiano.edu.br/) |
| Ambiente EAD | [Moodle IFGoiano](https://ead.ifgoiano.edu.br/) |

## Grade Curricular

### [1º Período](periodo_1/) — 70h

| Disciplina | Código | CH | Diretório | Colab |
|------------|--------|:--:|-----------|-------|
| Fundamentos de IA | 12548 | 30h | [`fundamentos_de_ia/`](periodo_1/fundamentos_de_ia/) | |
| Fundamentos Matemáticos para IA | 12547 | 40h | [`fundamentos_matematicos_para_ia/`](periodo_1/fundamentos_matematicos_para_ia/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1n5pa18fdXSTUgncYUDPCEVijopPi7uml?usp=sharing) |

### [2º Período](periodo_2/) — 50h

| Disciplina | Código | CH | Diretório | Colab |
|------------|--------|:--:|-----------|-------|
| Ética em IA | 12550 | 10h | [`etica_em_ia/`](periodo_2/etica_em_ia/) | |
| IA em Imagens | 12556 | 40h | [`ia_em_imagens/`](periodo_2/ia_em_imagens/) | |

### [3º Período](periodo_3/) — 160h

| Disciplina | Código | CH | Diretório | Colab |
|------------|--------|:--:|-----------|-------|
| IA em Dados Tabulares Corporativos | 12555 | 40h | [`ia_dados_tabulares_corporativos/`](periodo_3/ia_dados_tabulares_corporativos/) | |
| Linguagens e Ferramentas de Programação para IA | 12549 | 40h | [`linguagens_ferramentas_programacao_ia/`](periodo_3/linguagens_ferramentas_programacao_ia/) | |
| Pré-Processamento de Dados | 12551 | 40h | [`pre_processamento_de_dados/`](periodo_3/pre_processamento_de_dados/) | |
| Tópicos em Aprendizado de Máquina | 12552 | 40h | [`topicos_aprendizado_maquina/`](periodo_3/topicos_aprendizado_maquina/) | |

### [4º Período](periodo_4/) — 80h

| Disciplina | Código | CH | Diretório | Colab |
|------------|--------|:--:|-----------|-------|
| Metodologia de Projeto de Aplicação de IA | 12554 | 10h | [`metodologia_projeto_ia/`](periodo_4/metodologia_projeto_ia/) | |
| Projeto de Aplicação de IA | 12557 | 30h | [`projeto_aplicacao_ia/`](periodo_4/projeto_aplicacao_ia/) | |
| Tópicos em Redes Neurais Profundas | 12553 | 40h | [`topicos_redes_neurais_profundas/`](periodo_4/topicos_redes_neurais_profundas/) | |

**Carga horária total: 360h**

## Estrutura do Repositório

```
ifgoiano_ppgia2026/
├── docker-compose.yml
├── Dockerfile
├── periodo_1/
│   ├── fundamentos_de_ia/
│   └── fundamentos_matematicos_para_ia/
│       ├── images/
│       └── Aula01_Convolucao_Pratica.ipynb
├── periodo_2/
│   ├── etica_em_ia/
│   └── ia_em_imagens/
├── periodo_3/
│   ├── ia_dados_tabulares_corporativos/
│   ├── linguagens_ferramentas_programacao_ia/
│   ├── pre_processamento_de_dados/
│   └── topicos_aprendizado_maquina/
├── periodo_4/
│   ├── metodologia_projeto_ia/
│   ├── projeto_aplicacao_ia/
│   └── topicos_redes_neurais_profundas/
└── README.md
```

## Ambiente de Desenvolvimento

### Pré-requisitos
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Git](https://git-scm.com/)

### Executar os notebooks

```bash
# Clonar o repositório
git clone https://github.com/jailtoncarlos/ifgoiano_ppgia2026.git
cd ifgoiano_ppgia2026

# Subir o container com Jupyter Notebook
docker compose up -d

# Acessar no navegador
# http://localhost:8889
```

### Parar o container

```bash
docker compose down
```

## Autor

**Jailton Carlos de Paiva**
Aluno da Especialização em IA Aplicada a Dados Corporativos - Turma 2026
