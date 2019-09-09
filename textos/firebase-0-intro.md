O Google tomou uma decisão de que todos os aplicativos móveis devem migrar para Firebase Analytics. Estão descontinuando o Google Analytics para estes dispositivos. E agora? O Firebase é uma plataforma de serviços e APIs bastante completa, rápida e poderosa. Fácil entender os motivos do Google.

O Firebase Analytics, FA, adota uma série de conceitos diferentes do Google Analytics, GA, como sessão, estrutura de eventos e dimensões customizadas, para ficar nos principais.

As sessões de um site e de um aplicativo móvel são bastante diferentes, em especial pelo tipo de uso dos celulares e tablets. É muito comum termos usos curtos, rápidos, menos imersivos, que continuam depois de um tempo fora. Aquela olhadinha no aplicativo de mensagem, por exemplo.

Não temos as estruturas de eventos do GA de categoria, ação e rótulo, e isso parece confuso para quem já está acostumado. No entanto, nos dá muito mais liberdade para podermos configurar os eventos como quisermos: o Firebase permite criar eventos e parâmetros customizados, não temos mais só um tipo, além do enhanced ecommerce. Os parâmetros podem ser vistos como dimensões customizadas.

Um dos maiores problemas do novo sistema é o ambiente de relatório, seja na integração com o GA ou no console próprio do FA. Temos a impressão de que ainda está em desenvolvimento. Não conseguimos fazer um drill down de eventos, isto é, não conseguimos selecionar todos os eventos que tiveram um valor de parâmetro específico, depois um outro valor para outro parâmetro. É muito limitado para fazer análises de descobrimento. Para quem está acostumado com o as ferramentas do Google, o FA se aproxima mais de um Data Studio.

Quando fazemos a integração do FA com o GA, agora temos acesso ao menu Análise, em que podemos montar relatórios com os eventos do FA, inclusive aninhar os parâmetros com uma hierarquia e ter algo parecido com um drill down de eventos. Já é um grande passo para quem, ao migrar para o FA, só acessava os dados usando a integração com o Big Query.

Para testar e validar os eventos, diferentemente do GA, no FA podemos filtrar apenas um dispositivo específico e ver em tempo real os eventos coletados neste dispositivo, que deve estar com o modo de debug ativado. Podemos ativar o modo de debug do Firebase para qualquer aplicativo Android, mas no caso do iOS precisamos de uma versão do aplicativo gerada especificamente com opção de debug do Firebase.

No final de Julho de 2019 o Google anunciou uma nova maneira de integrar os dados dos aplicativos móveis, com a propriedade Aplicativos e Web, unificando os dados de canais diferentes.

Como vimos, o Google está terminando o sistema do Firebase Analytics em produção. Não que sejam ruins, as mudanças vêm para melhorar o que já tínhamos, mas talvez a forma como foi feita a transição tenha sido um pouco acelerada.
