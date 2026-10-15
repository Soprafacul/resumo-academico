# Etapa 6 Redação do artigo

## Solicitação

Escreva a primeira versão completa do artigo seguindo a estrutura abaixo.

Considerando INTRODUÇÃO, METODOLOGIA, REVISÃO DA LITERATURA, SÍNTESE CRÍTICA, CONSIDERAÇÕES FINAIS E RESUMO, a escrita deve ter entre 600 a 700 palavras.

## Título

GitHub Copilot no desenvolvimento de software: benefícios, limitações e revisão humana

**Autores:** José Kailon Teixeira da Silva; Carlos Henrique Nunes Ferreira Barbosa.  
**Curso:** Análise e Desenvolvimento de Sistemas.  
**Disciplina:** Design Profissional.  
**Professora:** Isabella Luiza dos Santos Souza.  
**Data:** 15/10/2026.

## Palavras-chave

GitHub Copilot; desenvolvimento de software; revisão de código.

## Introdução

A assistência por inteligência artificial à programação suscita questões sobre como avaliar sugestões de código e incorporá-las ao trabalho profissional. Os estudos de Vaithilingam, Zhang e Glassman (2022) e Barke, James e Polikarpova (2023) examinam essa interação, enquanto Pearce et al. (2022) investigam vulnerabilidades nas saídas do GitHub Copilot. Para estudantes de Análise e Desenvolvimento de Sistemas, o tema permite discutir critérios de qualidade na atuação profissional. Pergunta-se quais benefícios e limitações esses estudos identificam e quais implicações apresentam para a revisão humana. O objetivo é analisar tais benefícios e limitações na escrita e validação de código.

## Metodologia

Realizou-se uma revisão bibliográfica narrativa, de natureza teórica e abordagem qualitativa, em 15 de outubro de 2026. A busca exploratória na web utilizou nomes dos autores, títulos e termos como “GitHub Copilot”, “usability”, “security” e “code-generating models”. Consultaram-se textos completos disponibilizados por Harvard, UC San Diego e arXiv, com identificação das publicações ACM e IEEE pelos respectivos DOI. Foram selecionados intencionalmente três estudos empíricos, publicados entre 2022 e 2023, dentro do intervalo permitido de 2021 a 2026. A triagem considerou aderência ao problema, método identificável e acesso ao texto completo; materiais promocionais e duplicatas não integraram o corpus. A análise comparou métodos, resultados e limitações em dois eixos. Não se pretendeu realizar busca sistemática ou exaustiva.

## Revisão da literatura

### Usabilidade e apoio à programação

Vaithilingam, Zhang e Glassman (2022) compararam Copilot e IntelliSense em tarefas Python com 24 participantes. A preferência por Copilot não correspondeu a diferenças estatisticamente significativas no tempo ou no sucesso das tarefas; compreender e corrigir sugestões também gerou dificuldades. Barke, James e Polikarpova (2023), observando 20 participantes em quatro linguagens, distinguiram aceleração de tarefas conhecidas e exploração de soluções desconhecidas. Os estudos convergem quanto ao apoio inicial, mas empregam métodos diferentes: comparação de condições e construção qualitativa de uma teoria de interação. Assim, identificar um modo de aceleração não equivale a demonstrar aumento universal de produtividade.

### Segurança e validação do código

Pearce et al. (2022) avaliaram 1.689 programas gerados em 89 cenários relacionados a vulnerabilidades, utilizando análise automatizada e inspeção manual. Aproximadamente 40% apresentaram vulnerabilidades no experimento. Esse percentual descreve cenários selecionados, não todo código produzido pela ferramenta. Diferentemente dos estudos de interação, a unidade analisada foi o programa gerado. A comparação sugere distinguir compreensão da sugestão, correção funcional e segurança: uma impressão favorável de uso não estabelece qualidade em todas essas dimensões. Como implicação da revisão, testes funcionais e verificações de segurança devem complementar a avaliação humana.

## Síntese crítica

A leitura conjunta indica que a utilidade do assistente precisa ser avaliada junto ao esforço de validação. Preferência declarada, padrões de interação e ocorrência de vulnerabilidades são evidências distintas; agregá-las em uma única medida seria inadequado. As amostras pequenas dos estudos com usuários, os cenários delimitados de segurança e as versões antigas restringem generalizações. Também permanece, neste corpus, uma lacuna sobre efeitos prolongados em equipes profissionais. A divergência entre satisfação e desempenho recomenda atenção ao resultado verificado, não apenas à percepção de facilidade. Como proposta desta revisão, a validação deve ser planejada desde a definição dos requisitos, com critérios explícitos de aceitação. O interesse profissional está na solução adequada ao problema, não no volume de código produzido.

## Considerações finais

Os estudos selecionados apontam apoio para iniciar e desenvolver soluções, acompanhado de dificuldades de compreensão e riscos no código sugerido. A revisão humana permanece necessária para decidir se uma sugestão atende aos requisitos. Para a formação profissional, propõe-se praticar leitura crítica, testes e justificativa das decisões técnicas. Estudos futuros devem acompanhar equipes durante projetos completos, registrando retrabalho e defeitos. Também seria útil distinguir tarefas familiares e desconhecidas para avaliar o esforço de revisão em diferentes situações. As conclusões se limitam ao corpus analisado e não caracterizam automaticamente versões atuais do Copilot.

## Resumo

Esta revisão narrativa analisa benefícios e limitações do GitHub Copilot com base em três estudos de 2022 e 2023. A síntese qualitativa relaciona usabilidade e segurança, identificando apoio à programação, dificuldades de validação e limites de generalização. Conclui-se que a assistência requer avaliação humana e verificação técnica das sugestões.

## Referências

BARKE, Shraddha; JAMES, Michael B.; POLIKARPOVA, Nadia. Grounded Copilot: How Programmers Interact with Code-Generating Models. Proceedings of the ACM on Programming Languages, v. 7, n. OOPSLA1, art. 78, 27 p., 2023. DOI: https://doi.org/10.1145/3586030.

PEARCE, Hammond; AHMAD, Baleegh; TAN, Benjamin; DOLAN-GAVITT, Brendan; KARRI, Ramesh. Asleep at the Keyboard? Assessing the Security of GitHub Copilot’s Code Contributions. In: 2022 IEEE Symposium on Security and Privacy (SP). IEEE, 2022. p. 754-768. DOI: https://doi.org/10.1109/SP46214.2022.9833571.

VAITHILINGAM, Priyan; ZHANG, Tianyi; GLASSMAN, Elena. Expectation vs. Experience: Evaluating the Usability of Code Generation Tools Powered by Large Language Models. In: CHI Conference on Human Factors in Computing Systems Extended Abstracts. New York: ACM, 2022. 7 p. DOI: https://doi.org/10.1145/3491101.3519665.

## Checklist

- [x] A introdução termina com o objetivo.
- [x] A metodologia descreve o processo realmente realizado.
- [x] A revisão compara os artigos.
- [x] A conclusão responde ao problema.
- [x] O resumo representa o texto completo.

**Controle de extensão:** 653 palavras no corpo das seis partes exigidas, por separação por espaços. Os títulos, os metadados, as palavras-chave, as referências e este checklist não integram a contagem.

## Orientações de preenchimento preservadas

- Título: claro e coerente com o tema.
- Introdução: apresente contexto, foco, problema ou lacuna, justificativa e objetivo.
- Metodologia: informe o tipo de revisão, bases, estratégias de busca, período, critérios, triagem e forma de análise.
- Revisão da literatura: compare estudos, resultados, métodos e limitações.
- Síntese crítica: apresente tendências, convergências, divergências e lacunas.
- Considerações finais: responda ao problema, interprete os achados, destaque avanços e limitações e indique implicações futuras específicas.
- Resumo: escreva por último; contexto breve, objetivo, método, principais achados e conclusão.
- Referências: liste apenas as fontes citadas, conforme o padrão solicitado.
