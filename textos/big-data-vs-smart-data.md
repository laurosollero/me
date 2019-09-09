# Big Data vs Smart Data

Imagine o cenário: site grande, alcance nacional, área logada, dados pessoais; um sistema de auto-tagging, coletando tudo quanto é interação dos usuários e mandando para o Google Analytics. Nada absurdo. Se o contrato com uma agência de Inteligência/Performance termina, contrata outra. Nesse meio tempo (com sorte) percebe-se que dados pessoais estão sendo enviados para o Google Analytics pois alguém implementou alguma coisa errada. Logo, temos: Google, Agência 1 e Agência 2 com acesso a dados sensíveis, pessoais, PII, sem que o usuário saiba. LGPD está na esquina. Pesadelo anunciado.

Inicialmente se pensava que não conseguiríamos coletar todos os dados de todos os usuários. Depois disseram que informação nunca seria demais. Agora vemos que sim, pode ser um grande problema.

Além de um passivo jurídico que pode custar milhões, temos o custo de coletar esses dados, custo em dinheiro para um sistema como o Google Analytics, que tem um limite de hits por mês (e alguns degraus com o GA360), além de um  possível custo em performance de coletar os dados. Temos o custo de armazenamento, que é pequeno para um site com pouco acesso mas rapidamente explode quando falamos de muitos milhões de hits por mês. Temos o custo de mão de obra e tempo de uma equipe para organizar só o que será útil e com mais precisão para ser analisado. E, por fim, mas não menos problemático, temos os riscos de vazamento de alguma informação pessoal e, com a LGPD, teremos que ter controle de quem tem acesso a qual informação, onde estão guardadas, processos de limpar tudo sob demanda do usuário…

<img src="https://raw.githubusercontent.com/laurosollero/sobre/master/textos/smart-x-big.png" class="centered" alt="Elemento gráfico comparando os custos entre 'Como Pensam Que Big Data é' x 'Como Realmente Big Data É' x 'Smart Data'" />

Chegamos em Smart Data. Definido por coletar apenas as informações que nos serão úteis: mais barato, mais rápido de trabalhar e analisar, não traz nada escondido ou mesmo duvidoso quanto à segurança de informação e privacidade dos usuários. Dá mais trabalho para montar e organizar o sistema inicialmente mas no médio prazo, não no longo, esse tempo, trabalho e custo inicial rapidamente se tornam na melhor opção.

A solução estava na nossa cara o tempo todo! Não colete mais do que você precisa, não peça para o usuário mais do que o necessário, seu eu do futuro não quer essa dor de cabeça.
