# Projeto: Vinheria Agnello - Loja de Vinhos

## Sobre o projeto

A Vinheria Agnello é uma empresa familiar localizada em São Paulo, com mais de 15 anos de tradição no comércio de vinhos nacionais e internacionais.

A empresa se destaca pelo atendimento personalizado e pelo conhecimento especializado de sua equipe, que auxilia os clientes na escolha de vinhos, apresentando características das uvas, regiões produtoras e sugestões de harmonização.

Com os desafios enfrentados durante a pandemia, surgiu a necessidade de expandir os negócios para o ambiente digital. O projeto busca apresentar a história da vinheria, seus produtos e informações sobre o mundo dos vinhos, além de facilitar a comunicação com os clientes.

## Objetivo

Desenvolver um site institucional que apresente a Vinheria Agnello, sua história, equipe, clientes e produtos, valorizando a tradição da empresa e a experiência de atendimento personalizado.

## Estrutura do projeto

### Página Inicial
Apresenta a Vinheria Agnello, sua história sua trajetória no comércio de vinhos. Também destaca a equipe e oferece acesso às demais páginas.

### Página Sobre os Clientes
Apresenta o perfil dos consumidores da vinheria, desde apreciadores experientes até iniciantes no mundo dos vinhos, contendo um vídeo especial para iniciantes.

### Página do Catálogo de Vinhos
Apresenta informações sobre os tipos de vinhos, suas características e imagens, auxiliando os visitantes na escolha de opções para diferentes ocasiões.

### Página Sobre os Vinhos
A página apresenta informações sobre os vinhos, explica como é conservado e ajuda o visitante a compreender melhor esse universo e suas curiosidades. Para saber mais sobre as curiosidades do mundo dos vinhos, disponibilizamos no site um [link](https://vinicolauvva.com.br/blog/curiosidades-sobre-vinhos/?srsltid=AU7gw4UOsqYOA241CpULjOQr0GE0mSJ8M2m4p6zqAmAvs-qjAYcDO9uP) que direciona você a um conteúdo com informações e curiosidades sobre o tema.

### Página de Contato
Disponibiliza um formulário para que os visitantes preencham seus dados, selecionem o assunto e escrevam uma mensagem para a vinheria.

## Tecnologias utilizadas
<img
  align="left" 
  alt="HTML" 
  title="HTML"
  width="50px" 
  style="padding-right: 10px;" 
  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-plain-wordmark.svg" 
/>
<img
  align="left" 
  alt="CSS" 
  title="CSS"
  width="50px" 
  style="padding-right: 10px;" 
  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-plain-wordmark.svg" 
/>
<br>
<br>
## Integrante
- Nome do integrante: Luiza de Freitas Benevides

## Efeitos Visuais
O projeto Vinheria Agnello utiliza recursos de CSS para melhorar a experiência visual e a interação dos usuários com as páginas, mantendo uma identidade visual elegante, baseada em tons de vermelho, branco e cinza.

1. Personalização da seleção de texto (::selection)
Ao selecionar um trecho de texto na página, o fundo fica vermelho-escuro (rgb(136, 3, 3)) e a cor das letras passa para um tom claro (#f7f2f2).

2. Elementos decorativos nos títulos (::before e ::after)
Os títulos com a classe tituloPrincipal recebem duas bolinhas decorativas, uma de cada lado. 

3. Letra capitular na história (::first-letter)
O primeiro caractere dos parágrafos da seção de história é destacado com uma fonte cursiva, tamanho de 60px e a família tipográfica Italianno. A propriedade float: left permite que o restante do texto contorne a letra.

4. Destaque alternado na lista da equipe (:nth-child(odd))
Os itens ímpares da lista de integrantes recebem um fundo cinza-claro (#e7e3e3).

5. Interação com os nomes da equipe (:hover e transition)
Os títulos dos integrantes, definidos pela classe listaEquipe, mudam para cinza (#797676) quando o usuário passa o cursor sobre eles.

6. Mudança de cor dos links (:hover)
Os links relacionados aos vinhos e à seção sobre a vinheria mudam de vermelho-escuro para um vermelho mais vivo quando recebem o cursor.

7. Destaque dos campos do formulário (:focus)
Os campos de texto, e-mail, seleção e área de texto recebem uma borda vermelha quando estão em foco.

8. Efeito interativo no botão do formulário (:hover e transition)
O botão identificado pelo id="button" aumenta de tamanho ao passar o cursor, utilizando transform: scale(1.2). Além disso, o fundo muda de vermelho para branco, o texto passa para vermelho e uma borda vermelha aparece. A transição de 0,4 segundo torna a interação mais suave.

9. Mudança de cor ao clicar em links (:active)
Efeito que altera a cor do link enquanto o usuário está clicando nele como o seletor :active

10. Animação de entrada do cabeçalho (@keyframes headerTransicao)
O elemento com a classe headerSuave aparece gradualmente e se desloca horizontalmente até sua posição original.

11. Animação de entrada do conteúdo (@keyframes conteudoTransicao)
O conteúdo identificado pela classe conteudoSuave começa com transparência e um deslocamento de 30 pixels para a esquerda ao longo de 0,7 segundo

12. Animação contínua das imagens dos vinhos (@keyframes revelarVinho)
As imagens da tabela de vinhos aumentam e diminuem de tamanho continuamente, variando entre scale(0.8) e scale(1.15). Ao passar o cursor sobre uma imagem, a propriedade animation-play-state: paused pausa a animação no ponto em que ela se encontra.

13. Animação de rotação do vídeo (@keyframes rotacionarVideo)
O vídeo identificado pela classe videoVinhos aparece girando de -180 graus até 0 grau, enquanto aumenta de metade do tamanho até sua escala original.

14.Animação nos links de navegação
Foi adicionada uma linha decorativa vermelha abaixo dos links do menu de navegação. Ao passar o cursor sobre um link (:hover), a linha aumenta suavemente de largura, criando um efeito visual de destaque.

## Site publicado

[Acesse o site da Vinheria Agnello](https://luiiiq.github.io/vinheriaAgnelloEfeitos/)

Projeto acadêmico desenvolvido como parte das atividades da matéra de Front-End Design.
