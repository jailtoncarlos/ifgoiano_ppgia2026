# PPGIA - Especializa\u00e7\u00e3o em Intelig\u00eancia Artificial Aplicada a Dados Corporativos

**IFGoiano - Campus Uruta\u00ed** | C\u00f3digo: 0180614

Reposit\u00f3rio com materiais de estudo, notebooks e projetos desenvolvidos durante a P\u00f3s-Gradua\u00e7\u00e3o *Lato Sensu* em **Intelig\u00eancia Artificial Aplicada a Dados Corporativos** do Instituto Federal Goiano - Campus Uruta\u00ed.

## Links

| Recurso | Link |
|---------|------|
| Projeto Pedag\u00f3gico (PPC) | [PPC_especializacao_em_IA.pdf](https://suap.ifgoiano.edu.br/media/documentos/arquivos/PPC_especializacao_em_IA.pdf) |
| Portal Acad\u00eamico (SUAP) | [suap.ifgoiano.edu.br](https://suap.ifgoiano.edu.br/) |
| Ambiente EAD | [Moodle IFGoiano](https://ead.ifgoiano.edu.br/) |

## Grade Curricular

### 1\u00ba Per\u00edodo

| Disciplina | C\u00f3digo | Carga Hor\u00e1ria | Diret\u00f3rio |
|------------|--------|--------------|-----------|
| Fundamentos de IA | 12548 | 30h | [`fundamentos_de_ia/`](fundamentos_de_ia/) |
| Fundamentos Matem\u00e1ticos para IA | 12547 | 40h | [`fundamentos_matematicos_para_ia/`](fundamentos_matematicos_para_ia/) |

### 2\u00ba Per\u00edodo

| Disciplina | C\u00f3digo | Carga Hor\u00e1ria | Diret\u00f3rio |
|------------|--------|--------------|-----------|
| \u00c9tica em IA | 12550 | 10h | [`etica_em_ia/`](etica_em_ia/) |
| IA em Imagens | 12556 | 40h | [`ia_em_imagens/`](ia_em_imagens/) |

### 3\u00ba Per\u00edodo

| Disciplina | C\u00f3digo | Carga Hor\u00e1ria | Diret\u00f3rio |
|------------|--------|--------------|-----------|
| IA em Dados Tabulares Corporativos | 12555 | 40h | [`ia_dados_tabulares_corporativos/`](ia_dados_tabulares_corporativos/) |
| Linguagens e Ferramentas de Programa\u00e7\u00e3o para IA | 12549 | 40h | [`linguagens_ferramentas_programacao_ia/`](linguagens_ferramentas_programacao_ia/) |
| Pr\u00e9-Processamento de Dados | 12551 | 40h | [`pre_processamento_de_dados/`](pre_processamento_de_dados/) |
| T\u00f3picos em Aprendizado de M\u00e1quina | 12552 | 40h | [`topicos_aprendizado_maquina/`](topicos_aprendizado_maquina/) |

### 4\u00ba Per\u00edodo

| Disciplina | C\u00f3digo | Carga Hor\u00e1ria | Diret\u00f3rio |
|------------|--------|--------------|-----------|
| Metodologia de Projeto de Aplica\u00e7\u00e3o de IA | 12554 | 10h | [`metodologia_projeto_ia/`](metodologia_projeto_ia/) |
| Projeto de Aplica\u00e7\u00e3o de IA | 12557 | 30h | [`projeto_aplicacao_ia/`](projeto_aplicacao_ia/) |
| T\u00f3picos em Redes Neurais Profundas | 12553 | 40h | [`topicos_redes_neurais_profundas/`](topicos_redes_neurais_profundas/) |

**Carga hor\u00e1ria total: 360h**

## Estrutura do Reposit\u00f3rio

```
ifgoiano_ppgia2026/
\u251c\u2500\u2500 docker-compose.yml              # Container Jupyter para rodar os notebooks
\u251c\u2500\u2500 Dockerfile
\u251c\u2500\u2500 fundamentos_matematicos_para_ia/
\u2502   \u251c\u2500\u2500 images/                      # Imagens usadas nos notebooks
\u2502   \u251c\u2500\u2500 Aula01_Convolucao_Pratica.ipynb
\u2502   \u2514\u2500\u2500 ...
\u251c\u2500\u2500 fundamentos_de_ia/
\u251c\u2500\u2500 ...
\u2514\u2500\u2500 README.md
```

## Ambiente de Desenvolvimento

### Pr\u00e9-requisitos
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Git](https://git-scm.com/)

### Executar os notebooks

```bash
# Clonar o reposit\u00f3rio
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
Aluno da Especializa\u00e7\u00e3o em IA Aplicada a Dados Corporativos - Turma 2026
