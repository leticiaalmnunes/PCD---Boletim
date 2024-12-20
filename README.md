![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)
<h1 align='center'> Projeto final PCD - Boletim inteligente </h1>

## Colaboradores
[<img src="https://avatars.githubusercontent.com/u/172425100?v=4" width=115>](https://github.com/jojomolinetes)
[<img src="https://avatars.githubusercontent.com/u/172425156?v=4" width=115>](https://github.com/leticiaalmnunes)
[<img src="https://avatars.githubusercontent.com/u/172424981?v=4" width=115>](https://github.com/ClaraLelis)
[<img src="https://avatars.githubusercontent.com/u/172425104?v=4" width=115>](https://github.com/ThomasHannemann)

* Joana de Medeiros Oliveira Hulse Molinete, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Letícia Almeida Nunes, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Maria Clara Macêdo Lelis, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Thomas Wolff Hannemann, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais

## ÍNDICE
* [Colaboradores](#colaboradores)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
  - [Objetivo Principal](#objetivo-principal)
* [Demonstração da Aplicação](#demonstração-da-aplicação)
  - [Professor](#professor)
  - [Aluno](#aluno)
* [Informações técnicas](#informações-técnicas)
* [Conclusão](#conclusão)
* [Contribuições](#contribuições)
* [Agradecimentos](#agradecimentos)
* [Referências](#referências)

## Descrição do Projeto
Trabalho final do primeiro período do curso de Bacharelado em Ciência e Tecnologia da turma 2024 da _Ilum - Escola de Ciência (CNPEM)_ referente à disciplina 'Práticas em Ciências de Dados', ministrada pelo Professor Leandro Nascimento Lemos.<br>
Indo além do boletim tradicional, esse código funciona como uma biblioteca que fornece estatísticas e gráficos sobre os desempenhos individuais e das turma. Por motivos didáticos, o código pré-estabelece um sistema de avaliação fixo e precisa de um dicionário prévio para ser rodado.

### Objetivo principal
O projeto tem como objetivo principal criar funções que facilitem o acesso, disponibilização e análise das notas das disciplinas do curso, realizando a mediação entre professores e alunos. 
<br>
Procuramos criar funções que seriam utilizadas em um espaço onde seja possível que os professores insiram as notas das provas e atividades para os alunos de forma manual e o programa funcione de forma a retornar para o próprio professor a maior e menor nota na sua disciplina, a média de toda a turma, a mediana, o desvio padrão da média e um gráfico com a distribuição das notas e conceito para cada prova.
<br>
Para os alunos o programa retorna todas as notas de cada matéria, as médias de cada disciplina com conceito, posição no ranking da turma (por matéria e geral), menor e maior nota da turma, nota mediana da turma e um aviso caso precise realizar a recuperação de alguma matéria.

## Demonstração da Aplicação
### Professor
![d1cf599c-aa3f-4108-b084-b590da9fdbac](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/f53b048b-e5aa-4527-adcc-1798b752762e)
<br>
![ba1b564a-03d2-4d8c-aab6-0384d799b164](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/f94987c3-a6e2-471e-bf3e-8802894fea1f)
<br><br>

### Aluno
![image](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/3f3a3ef7-6644-4505-b551-aa21e71b8391)
![image](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/6a96a98c-24c5-4fcc-9566-ad2725cd5c1e)
<br><br>

## Informações técnicas
* Linguagem de programação
  - Python 3.9
* Software
  - Jupyter Notebook
* Bibliotecas
  - BoxPlot 0.1.1
  - Collections 0.1.6
  - Matplotlib 3.9.0
  - Numpy 1.26.4
  - Operator 1.0.1
  - Os 2.1.4
  - Pandas 2.2.2
  - Plotly.graph_objects 5.22.0
  - Statistics 1.0.3.5
  - Time 0.3.0

## Conclusão
Os resultados apresentados no trabalho alcançaram de forma satisfatória os objetivos traçados inicialmente para o algoritmo, tornando o processo de recebimento e controle de nota muito mais fácil e visual, tanto para os estudantes quanto para os docentes. Apesar de ser um projeto puramente didático cuja interface para a devida aplicação ainda precisaria ser pensada, a funcionalidade e execução foram adequadas e pertinentes, cumprindo com o propósito do grupo e da disciplina.<br>

## Contribuições
HANNEMANN, Thomas: Responsável pela leitura e estruturação dos dados de saída (gráficos), elaboração dos trechos do código referentes ao retorno do aluno e tratamento dos dados.
<br><br>
LELIS, Maria: Responsável pela estruturação dos dados de saída (interface e arquivos), elaboração dos trechos do código referentes ao retorno do aluno, pesquisas para o aprimoramento das funções e realização dos testes. 
<br><br>
MOLINETE, Joana: Responsável pela estruturação dos dados de entrada, elaboração dos trechos do código referentes ao retorno do professor (gráficos), documentação (introdução, objetivos e conclusão) e slides.
<br><br>
NUNES, Letícia: Líder da equipe, idealizadora do projeto, responsável pela estruturação dos dicionários, padronização das funções, elaboração dos trechos do código referentes ao retorno do professor e documentação.
<br><br>

## Agradecimentos
Agradecemos ao professor Leandro Nascimento Lemos pela orientação durante todo o decorrer do semestre na disciplina de Práticas em Ciências de Dados. Ao Duanny Onorio, pela disponibilização do seu tempo até mesmo fora do expediente para sanar nossas dúvidas, dar dicas e corrigir nossos códigos. Aos nossos colegas e amigos Rômulo Emanuel Cruz e Raquel de Godoy Vianna que também auxiliaram na correção de alguns erros.

## Referências do README
Alura. Como escrever um bom README. 2023. Disponível em: https://www.alura.com.br/artigos/escrever-bom-readme. Acesso em: 25 jun. 2024.
<br><br>
ChatGPT. ChatGPT. 2024. Disponível em: <https://chatgpt.com/>. Acesso em: 25 jun. 2024.
<br><br>
Lohhans. Exemplo de um bom README. 2023. Disponível em: https://gist.github.com/lohhans/f8da0b147550df3f96914d3797e9fb89. Acesso em: 25 jun. 2024.
<br><br>
Rocketseat. Como fazer um bom README. 2023. Disponível em: https://blog.rocketseat.com.br/como-fazer-um-bom-readme/. Acesso em: 25 jun. 2024.
<br><br>
Stack Overflow. Como escrever em um arquivo txt em Python?. 2020. Disponível em: https://pt.stackoverflow.com/questions/464675/como-escrever-em-um-arquivo-txt-em-python. Acesso em: 25 jun. 2024.
<br><br>
YouTube. Como fazer um bom README. 2023. Disponível em: https://youtu.be/ZWj8o692qGY?si=PBVFkb1a_aHU3K_p. Acesso em: 25 jun. 2024. ​
<br><br>

_Projeto concluído dia 25 de junho de 2024._
