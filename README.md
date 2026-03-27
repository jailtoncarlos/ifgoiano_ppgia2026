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

### 1º Período

| Disciplina | Código | Carga Horária | Diretório |
|------------|--------|--------------|-----------|
| Fundamentos de IA | 12548 | 30h | [`fundamentos_de_ia/`](fundamentos_de_ia/) |
| Fundamentos Matemáticos para IA | 12547 | 40h | [`fundamentos_matematicos_para_ia/`](fundamentos_matematicos_para_ia/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1n5pa18fdXSTUgncYUDPCEVijopPi7uml?usp=sharing) |

### 2º Período

| Disciplina | Código | Carga Horária | Diretório |
|------------|--------|--------------|-----------|
| Ética em IA | 12550 | 10h | [`etica_em_ia/`](etica_em_ia/) |
| IA em Imagens | 12556 | 40h | [`ia_em_imagens/`](ia_em_imagens/) |

### 3º Período

| Disciplina | Código | Carga Horária | Diretório |
|------------|--------|--------------|-----------|
| IA em Dados Tabulares Corporativos | 12555 | 40h | [`ia_dados_tabulares_corporativos/`](ia_dados_tabulares_corporativos/) |
| Linguagens e Ferramentas de Programação para IA | 12549 | 40h | [`linguagens_ferramentas_programacao_ia/`](linguagens_ferramentas_programacao_ia/) |
| Pré-Processamento de Dados | 12551 | 40h | [`pre_processamento_de_dados/`](pre_processamento_de_dados/) |
| Tópicos em Aprendizado de Máquina | 12552 | 40h | [`topicos_aprendizado_maquina/`](topicos_aprendizado_maquina/) |

### 4º Período

| Disciplina | Código | Carga Horária | Diretório |
|------------|--------|--------------|-----------|
| Metodologia de Projeto de Aplicação de IA | 12554 | 10h | [`metodologia_projeto_ia/`](metodologia_projeto_ia/) |
| Projeto de Aplicação de IA | 12557 | 30h | [`projeto_aplicacao_ia/`](projeto_aplicacao_ia/) |
| Tópicos em Redes Neurais Profundas | 12553 | 40h | [`topicos_redes_neurais_profundas/`](topicos_redes_neurais_profundas/) |

**Carga horária total: 360h**

## Estrutura do Repositório

```
ifgoiano_ppgia2026/
├── docker-compose.yml              # Container Jupyter para rodar os notebooks
├── Dockerfile
├── fundamentos_matematicos_para_ia/
│   ├── images/                      # Imagens usadas nos notebooks
│   ├── Aula01_Convolucao_Pratica.ipynb
│   └── ...
├── fundamentos_de_ia/
├── ...
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
