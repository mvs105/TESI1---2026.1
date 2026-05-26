# TESI1 - 2026.1

Repositório da disciplina TESI I - Tópicos Especiais em Sistemas de Informação da Universidade Federal do Acre (UFAC), período 2026.1.

# Projeto - Mineração e Ciência de Dados

## Descrição do Projeto

Neste projeto, trabalharemos com foco em **Mineração de Dados** e **Ciência de Dados** aplicada ao contexto educacional.

As bases foram obtidas em plataformas públicas de dados e passarão por análise e aprovação do professor.

---

# Escolha da Base de Dados
## Bases Coletadas

### Base 1 - Microdados do Ensino Superior 2020

<!-- **Pasta:** [cadastro_de_cursos](./bases_de_dados_tesi/cadastro_de_cursos/) -->

Fonte:
- https://www.kaggle.com/datasets/mistergomes/microdados-educacao-superior-2020

Descrição:  
A base agrupa dados sobre instituições de ensino superior no Brasil, incluindo a categoria administrativa (pública ou privada), os cursos oferecidos, o número de vagas, as matrículas, as modalidades (presencial ou EAD), além de diversas outras informações.

---

### Base 2 - Microdados do ENEM 2023

<!-- **Pasta:** [enem_2023](./bases_de_dados_tesi/enem_2023) -->

Fonte:
- https://www.kaggle.com/datasets/llssatcesar/microdados-enem-2023

Descrição:  
A base compila informações detalhadas sobre candidatos do ENEM 2023, como dados demográficos (idade, sexo, cor/raça e estado civil), histórico escolar (tipo de escola e situação de conclusão do ensino médio) e desempenho no exame (nota da redação e pontuação nas áreas de conhecimento).


---
#### Outras Fontes
- https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem

  O Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira fornece os microdados do ENEM para consulta pública, pesquisa acadêmica e análise de políticas educacionais.

---

- https://emec.mec.gov.br/emec/nova

  O e-MEC centraliza e disponibiliza a base de dados oficial e unificada de todas as Instituições de Educação Superior (IES) e seus respectivos cursos no Brasil, permitindo consultar de forma confiável a regularidade institucional, a validade dos atos autorizativos e a situação legal de cursos de graduação e especialização.

---

# Caminho que podemos seguir

Nosso objetivo inicial é cruzar o perfil de desempenho dos candidatos (microdados do ENEM) e a oferta de vagas e cursos das instituições (microdados do Ensino Superior e/ou e-MEC) e, a partir dessa integração, utilizar técnicas de ciência e mineração de dados para identificar padrões entre as notas obtidas nas diferentes áreas do exame e as opções de graduação disponíveis.

# Observações

- Os datasets não foram incluídos diretamente no repositório devido ao tamanho dos arquivos.
- Para acessar as bases de dados utilizadas no projeto, utilize os links disponibilizados nas seções de cada base no README.