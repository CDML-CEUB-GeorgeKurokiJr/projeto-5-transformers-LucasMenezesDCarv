# Clusterização de Projetos Científicos utilizando BERTimbau, NER e Representação Híbrida

##  Descrição

Este projeto tem como objetivo realizar a **clusterização de projetos científicos em língua portuguesa** utilizando técnicas de Processamento de Linguagem Natural (PLN), combinando modelos de linguagem baseados em **BERTimbau**, técnicas de **Reconhecimento de Entidades Nomeadas (NER)** e uma **representação híbrida de texto**.

O notebook apresenta todo o fluxo de preparação e processamento dos dados até a geração das representações utilizadas na etapa de clusterização.

---

##  Objetivos

- Ler e analisar uma base de projetos científicos;
- Realizar limpeza e preparação dos dados;
- Construir um texto consolidado a partir das informações disponíveis;
- Aplicar técnicas de normalização textual;
- Gerar embeddings utilizando modelos baseados em BERTimbau;
- Utilizar NER para enriquecer a representação dos documentos;
- Produzir representações híbridas para posterior aplicação de algoritmos de clusterização.

---

##  Estrutura do Projeto

O notebook está organizado nas seguintes etapas:

1. Leitura da base de dados;
2. Inspeção inicial dos dados;
3. Limpeza e preparação das informações;
4. Construção do texto completo;
5. Normalização textual;
6. Extração de características e embeddings;
7. Representação híbrida;
8. Clusterização dos projetos científicos.

---

##  Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Transformers (Hugging Face)
- BERTimbau
- SpaCy
- Matplotlib
- Seaborn

---

##  Fluxo de Execução

```text
Leitura dos dados
        ↓
Análise exploratória
        ↓
Limpeza e pré-processamento
        ↓
Construção do texto completo
        ↓
Normalização
        ↓
Embeddings (BERTimbau)
        ↓
NER
        ↓
Representação híbrida
        ↓
Clusterização
```

---

##  Como Executar

### 1. Clonar o repositório

```bash
git clone <url-do-repositorio>
cd <nome-do-repositorio>
```

### 2. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 3. Executar o notebook

```bash
jupyter notebook projeto_completado.ipynb
```

---

##  Possíveis Aplicações

- Organização automática de projetos científicos;
- Descoberta de temas de pesquisa semelhantes;
- Recomendação de projetos relacionados;
- Análise de produção científica;
- Apoio à tomada de decisão em instituições de pesquisa.

---

##  Resultados Esperados

A utilização de embeddings gerados pelo BERTimbau juntamente com entidades nomeadas permite uma representação mais rica dos documentos, possibilitando uma clusterização mais eficiente e semanticamente coerente.

---

##  Autor

Projeto desenvolvido para fins acadêmicos na área de **Ciência de Dados, Machine Learning e Processamento de Linguagem Natural**.

**Autor:** Lucas Menezes
