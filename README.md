# Minicurso de Geração de Colunas

Material de associados ao curso "Implementação de geração de colunas usando CPLEX em linguagem C/C++"
Universidade de São Paulo.

### Preliminares:

Para quem deseja inicialmente ter uma noção básica da técnica de geração de colunas, origem e aplicações, nós recomendamos a leitura do tutorial do Professor Doutor José Manuel Valério de Carvalho que pode ser encontrado em: https://goo.gl/gvrocN.

Para compilar e executar os códigos apresentados, será necessário um computador com um compilador C/C++ e alguma versão do software CPLEX instalada.

Os usuários de Windows, deverão usar alguma interface que faça a ligação das bibliotecas do CPLEX na compilação do código (Visual Studio, Code::Blocks ...).

Para os usuários de Linux, disponibilizamos um arquivo de compilação (makefile). Assumimos que o caminho de instalação do CPLEX é o padrão e utilizamos a versão 12.6 do software (o que pode ser facilmente alterado como documentado no arquivo).

### Material:

Os seguintes arquivos estão disponíveis neste repositório 

Apresentacao.pdf - contêm  os slides do curso.

framework.cpp - código do  framework implementado durante o curso com comentários adicionais.

pdl.zip - resolução do problema de dimensionamento de lotes via geração de colunas (utilizando o framework).

pcu.zip - resolução do problema de corte unidimensional via geração de colunas (utilizando o framework).

---

No link https://goo.gl/G5CQvY é possível a estrutura com as classes e métodos do CPLEX. 



### Autores: 
Landir Saviniec e Luiz Henrique Cherri
