# uvv-site-refugiadas
Esse repositório é de um trabalho universitário de um site para refugiadas

## Descrição doq eu terá no site:

### ANTEÇÃO: Os botões ENTRAR e CADASTRE estarão inutilizáveis, pelo fato de que o objetivo desse trabalho era apenas uma única página, tirando esses dois botões o resto estaráfuncionando.

### CSS
*: Nessa parte, todas as letras serão com um tipo padrão de fonte(importada) e organizadas em uma forma de caixa

body: Nessa parte estará como a cor do site ficará, e nesse caso foi usado um degradê de duas cores

header: Nessa parte ficará responsável como o cabeçalho da página ficará, ou seja, a sua posição no site e onde casa objeto ficará

header .logo: Aqui irá colocar expecificação para a LOGO do site para ela esta em determinada cor e tamanho diferente dos outros itens pertecentes ao cabeçalho

header ul: como eu utilizei o <ul></ul> para ficar mais fácil de por os botões, essa parte ficará responsável para modificá-la

header li: Aqui ficara as expecificações do tamanho dos botões do cabeçalho do site, pois eu usei o "<li></li>" para separar cada um deles

header ul li a: Nessa parte estará a cor dos botões do cabeçalho e o tamanho desses botões

header ul li a:hover, header ul li a.active: ambos terão a mesma caracteristica, que é como o botão se comportará apó o mouse passar por cima dele, e o .active mostrará onde o usuário está no site

section: nessa parte eu coloquei 2 elementos, uma imagem de fundo e uma frase, e depois a personalizei

#text: nessa parte estará responsável para modificar a frase que está na frente da imagem principal do site

.avaliação: nessa parte estará responsável para o gerenciamento das estrelas qeu estão disponivel no site
como o tamanho dela, a cor, se ela estará vazia por dentro ou cheia.


### JS


addEventListener: é a maneira de registrar uma espera de evento como especificada, e é usada para colocar o texto(text) com o efeito de subida
e posteriormente sair do site de maneira sutil quando você usa o scroll do mouse de maneira vertical.
 
apartir de linha 10, estará responsável pelo sistema das estrelas, ou seja, ele ficará responsável em deixar quantas estrelas ficarão completadas de acordo com o click do mouse do usuário, 
fazendo assim, quando o usuário clicar em uma das estreals ela ficará naquela forma até ele clicar em outra.

a ultima linha "console.log(e.target.getAttribute('data-avaliacao'));" ficará responsável por registrar no console do site a validação que o usuário deu para o site, qeu futuramente pode se aplicado em um banco de dados

### RESPONSIVIDADE

a responsividade estará no CSS na linha 141 realizando a seguinte cláusula: quando o site ficar menor que 600px de largura, ele entrará nesse modelo.

foi feito a responsividade em apenas uma parte, pois o objetivo do trabalho era mostrar caso o aluno saberia modificar o site para torná-lo responsivel.



