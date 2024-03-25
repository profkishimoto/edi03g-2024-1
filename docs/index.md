# UPM CC - Estrutura de Dados I 03G (2024.1)

***Copyright &copy; 2024 André Kishimoto. Todos os direitos reservados.***

## INFORMAÇÕES GERAIS

> **Universidade Presbiteriana Mackenzie**<br>
> **FCI** – Faculdade de Computação e Informática<br>
> **Ciência da Computação**<br>
> Disciplina: **Estrutura de Dados I** (3ª etapa)<br>
> Professores: **André Kishimoto** (teoria) e **Leonardo Massayuki Takuno** (laboratório)

> **1º semestre 2024**<br>
> **segunda-feira**, **09:20** às **11:00** (2hs/aula) - 03G11 (**prédio 31 - sala 401**)<br>
> **sexta-feira**, **07:30** às **09:10** (2hs/aula) - 03G (**prédio 33 - sala 102**)

### Calendário Escolar

**Calendário Escolar**, **Regulamento Acadêmico** e outras informações: <a href="https://www.mackenzie.br/universidade/processos-academicos-para-coordenadoria-geral-de-relacionamento-e-atendimento/informacoes-ao-aluno/calendario-escolar" target="_blank">CLIQUE AQUI</a>

### Plano de ensino

**Plano de ensino** disponível no link a seguir:
[Plano de ensino (pdf)](conteudo/plano-de-ensino/CC_3G_Plano_de_ensino_EstruturadeDadosI_2024_1.pdf)

### Como entrar em contato com o professor?

- **Moodle**: envie mensagem direta.
- **E-mail**: <a href="mailto:andre.kishimoto@mackenzie.br">andre.kishimoto@mackenzie.br</a>


## DATAS IMPORTANTES

**Observação**: Datas planejadas e sujeitas a alterações.

- **P1**: 05/04/2024
- **P2**: 24/05/2024
- **SUB**: 07/06/2024
- **PF**: 14/06/2024


## EXERCÍCIOS E AVALIAÇÕES

**Atenção!** As entregas das atividades devem ser realizadas pelo Moodle!


## ÍNDICE DE AULAS

- [Semana 1: Apresentação da disciplina e introdução Java](#-semana-1-0902-)
- [Semana 2: Tipos de dados](#-semana-2-1602-)
- [Semana 3: TAD Pilha sequencial/estática](#-semana-3-2302-)
- [Semana 4: TAD Pilha sequencial/estática](#-semana-4-0103-)
- [Semana 5: TAD Fila sequencial/estática](#-semana-5-0803-)
- [Semana 6: TAD Fila dupla sequencial/estática](#-semana-6-1503-)
- [Semana 7: Revisão do conteúdo para a prova P1](#-semana-7-2203-)
- [Semana 8: Feriado](#-semana-8-2903-)


## ■■■■■ Semana 1 (09/02) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- Apresentar o plano de ensino.
- Explicar critérios de avaliação, frequência e aprovação.
- Apresentar a disciplina.

### Arquivos

- [Apresentação (pdf)](conteudo/semana-1/Apresentação.pdf)
- [Configuração da máquina para desenvolvimento Java (pdf)](conteudo/semana-1/EDI%20-%20Configuração%20da%20máquina%20para%20desenvolvimento%20Java%20-%20v1.2.pdf)
- [Programação de Computadores (versão "Java 101") (pdf)](conteudo/semana-1/Java101.pdf)
- [Programação de Computadores (resumo "Java 101") (pdf)](conteudo/semana-1/Java101-resumo.pdf)

### Ferramentas

- <a href="https://jdk.java.net/21" target="_blank">JDK 21</a> - link direto para Windows: [openjdk-21.0.2_windows-x64_bin.zip](https://download.java.net/java/GA/jdk21.0.2/f2283984656d49d69e91c558476027ac/13/GPL/openjdk-21.0.2_windows-x64_bin.zip)
- <a href="https://www.eclipse.org/downloads/packages/release/2023-12/r/eclipse-ide-java-developers" target="_blank">Eclipse IDE for Java Developers 2023-12</a> - link direto para Windows: [eclipse-java-2023-12-R-win32-x86_64.zip](https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2023-12/R/eclipse-java-2023-12-R-win32-x86_64.zip)

### Referências e recursos

- ORACLE. **Java Documentation**. Disponível em <a href="https://docs.oracle.com/en/java/" target="_blank">https://docs.oracle.com/en/java/</a>.
- KISHIMOTO, A. **Configuração da máquina para desenvolvimento Java**. Disponível [aqui](conteudo/semana-1/EDI%20-%20Configuração%20da%20máquina%20para%20desenvolvimento%20Java%20-%20v1.2.pdf).


## ■■■■■ Semana 2 (16/02) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- Conceituar tipos de dados (primitivos, estruturados e abstratos).

### Arquivos

- [Tipos de Dados (pdf)](conteudo/semana-2/TiposDeDados.pdf)

### Referências e recursos

- GOODRICH, M. T.; TAMASSIA, R. **Estruturas de dados e algoritmos em Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 1 (Cartilha de Java)
- HORSTMANN, C. S.; CORNELL, G. **Core Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=pearson" target="_blank">Biblioteca Virtual Universitária 3.0</a>.
  - Capítulo 3 (Estruturas de programação fundamentais no Java)
  - Capítulo 4 (Objetos e classes)


## ■■■■■ Semana 3 (23/02) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- TAD Pilha sequencial/estática.

### Arquivos

- [Mini-zine sobre pilha (stack) (pdf)](conteudo/semana-3/minizine_pilha_ak.pdf)

### Referências e recursos

- GOODRICH, M. T.; TAMASSIA, R. **Estruturas de dados e algoritmos em Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 5, seção 5.1 (Pilhas)
- CELES, W.; CERQUEIRA, R.; RANGEL, J. L. **Introdução a Estruturas de Dados com técnicas em programação em C, 2ª edição**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 15, seção 15.1 (Pilhas)


## ■■■■■ Semana 4 (01/03) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- TAD Pilha sequencial/estática.

### Arquivos

- [Problemas de pilha (pdf)](conteudo/semana-4/EDI-2024.1%20-%20Problemas%20de%20pilha.pdf)

### Referências e recursos

- GOODRICH, M. T.; TAMASSIA, R. **Estruturas de dados e algoritmos em Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 5, seção 5.1 (Pilhas)
- CELES, W.; CERQUEIRA, R.; RANGEL, J. L. **Introdução a Estruturas de Dados com técnicas em programação em C, 2ª edição**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 15, seção 15.1 (Pilhas)


## ■■■■■ Semana 5 (08/03) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- TAD Fila sequencial/estática.

### Arquivos

- [Mini-zine sobre fila (queue) (pdf)](conteudo/semana-5/minizine_fila_ak.pdf)

### Referências e recursos

- GOODRICH, M. T.; TAMASSIA, R. **Estruturas de dados e algoritmos em Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 5, seção 5.2 (Filas)
- CELES, W.; CERQUEIRA, R.; RANGEL, J. L. **Introdução a Estruturas de Dados com técnicas em programação em C, 2ª edição**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 15, seção 15.2 (Filas)


## ■■■■■ Semana 6 (15/03) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- TAD Fila dupla sequencial/estática.

### Arquivos

- [TAD Fila dupla (pdf)](conteudo/semana-6/Deque.pdf)

### Referências e recursos

- GOODRICH, M. T.; TAMASSIA, R. **Estruturas de dados e algoritmos em Java**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 5, seção 5.3 (Filas com dois finais)
- CELES, W.; CERQUEIRA, R.; RANGEL, J. L. **Introdução a Estruturas de Dados com técnicas em programação em C, 2ª edição**. Disponível na <a href="https://web3.mackenzie.br/biblioteca/access?libType=minhabiblioteca" target="_blank">Minha Biblioteca</a>.
  - Capítulo 15, seção 15.3 (Fila dupla)


## ■■■■■ Semana 7 (22/03) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- Revisão do conteúdo para a prova P1.

### Arquivos

- [Exercícios de revisão/treino para a prova P1 (pdf)](conteudo/semana-7/EDI-2024.1%20-%20Exercícios%20de%20revisão%20P1.pdf)
- [Implementação de pilha com deque - Exemplo Java criado em aula (zip)](conteudo/semana-7/StackcomDeque-20240322-03G.zip)

### Referências e recursos

- Ver semanas anteriores.


## ■■■■■ Semana 8 (29/03) ■■■■■

[Índice de aulas ⤴](#índice-de-aulas)

### Objetivos da semana

- Feriado. Bom descanso!

