Criador: Pedro HSR Ilhéo.
Ideia Principal: Jogo estilo RPG de turnos.

Desenvolvimento: Código original e ideias feitos por mim, parte de implementação em JS(Java Script) feita pelo ChatGPT.

Versão 1: Código ainda em desenvolvimento(definição de variáveis e planejamento de funcionamento);

Versão 2: Implementação de modos de jogo(fácil, médio, difícil) e técnicas(ataque e cura) para o jogador, junto do ajuste de estatísticas(vida, vida máxima, dano, crítico, cura e chances diversas);

Versão 3: "Finalização" do projeto em Java na parte estrutural e funcional.

Versão 4: Implementação em Java Script com ajuda do ChatGPT.

Resultado JS: Página simples, caixa de texto para mostrar o FrontEnd do código, sistema de jogo por texto, sistema de vida visual, jogabilidade auto explicativo.

Como jogar: Recomendo você utilizar um programa chamado Visual Studio Code, gratuito na Microsoft Store.
 Ao entrar no programa selecione a linguagem HTML antes de inserir o código. 
 Após isso copie e cole o código no espaço vazio.
 Agora é só selecionar a opção Run na parte superior esquerda, escolher a opção Run Withoud Debug e selecionar seu navegador padrão(Google, Edge, Firefox, etc).

Básico para jogar: 

Começar= Selecione uma dificuldade de jogo para iniciar.

Reiniciar= Recarregue a página para voltar a seleção de dificuldade.


Dificuldade: As dificuldades variam de fácil, médio e difícil, onde todas contém 3 fases.

Fases: Todas as dificuldades tem 3 fases, cada fase indica um nível de inimigo.

Fase1: Fase inicial com inimigo básico.

Fase2: O inimigo ganha mais status, tem menos chance de errar ataques, e também ganha a habilidade de esquivar de ataques(baseado em chances).

Fase3: Fica melhor em todos os aspectos.

Ações: Selecione o botão de ação que você quer executar (ATACAR ou CURAR).

Inimigo: Ele tem apenas uma ação que é o ataque, sem ataque crítico, também tem chances de errar o ataque.

Chances: As chances se aplicam apenas à:

1.Jogador: ataque crítico(muda de acordo com a dificuldade).

2.Inimigo: errar ataque(muda de acordo com a dificuldade e a fase que você está), desviar do seu ataque(ativo apenas após a 1°fase, muda de acordo com a dificuldade e a fase).
