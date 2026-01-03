# Trabalho de Conclusão de Curso (TCC) - Estatística UFPR

Este repositório contém o material completo do meu Trabalho de Conclusão de Curso, requisito final para obtenção do grau de Bacharel em Estatística pela Universidade Federal do Paraná (UFPR). 

O projeto destaca-se por ter sido desenvolvido sob o paradigma da **Pesquisa Reprodutível**: todo o documento (texto, equações, cálculos e gráficos) foi gerado a partir de um único código-fonte em R Markdown.

## 📄 Tema e Objetivos


> Este trabalho avalia a robustez e a aplicabilidade de um modelo de Cadeias de Markov de Ordem Superior Simplificada para a previsão de séries temporais no contexto econômico brasileiro. Seguindo a metodologia de Ky e Tuyen (2018), o modelo foi testado em um conjunto diversificado de dados, incluindo ações do Ibovespa e indicadores macroeconômicos do SGS, através de um pipeline que envolveu a discretização de log-retornos e a otimização de hiperparâmetros (ordem e número de estados) via validação por janela deslizante. Os resultados demonstraram que o modelo é flexível, adaptando sua complexidade à dinâmica de cada série, e alcançou alta acurácia (baixo MAPE) para dados com padrões regulares e sazonais, como o consumo de energia e ações de setores defensivos. Contudo, sua performance foi inferior para séries mais voláteis e erráticas, como as de varejo e de empresas em setores cíclicos, evidenciando a limitação do modelo em cenários onde a dependência de padrões históricos é fraca. Conclui-se que o modelo é uma ferramenta robusta e útil para o contexto brasileiro, mas sua eficácia é condicionada à regularidade da série, e trabalhos futuros poderiam explorar extensões multivariadas para incorporar informações exógenas.


## 🛠️ Destaques Técnicos

Este projeto demonstra competências avançadas em:

* **Escrita Científica e Técnica:** Estruturação de argumentos, revisão bibliográfica e formalização matemática.
* **Programação Literária (Literate Programming):** Integração de código R e texto LaTeX para geração automática de relatórios.
* **Modelagem Estatística:** Aplicação rigorosa de métodos quantitativos para responder a uma pergunta de pesquisa complexa.
* **Visualização de Dados:** Criação de gráficos prontos para publicação acadêmica.

## 📂 Estrutura do Repositório

* `TCC.Rmd`: O "coração" do projeto. Código-fonte que contém tanto a narrativa textual quanto os scripts de análise.
* `TCC.pdf`: A versão final compilada do trabalho, apresentada à banca examinadora.

---
**Autor:** Luiz Henrique Barretta Francisco
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
