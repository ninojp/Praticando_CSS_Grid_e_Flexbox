# Praticando CSS: Grid e Flexbox

## Aula 01 - Hello Flex!

### Aula 01 - Apresentação - Video 1

Nesta aula do curso "Praticando CSS com Grid e Flexbox", os instrutores Beatriz e Luan apresentam o conteúdo do curso. Eles explicam que o curso é voltado para aqueles que desejam aprender a utilizar o Flexbox e o Grid para dispor elementos em uma página HTML. O projeto Culturama será desenvolvido ao longo do curso, com foco em três telas principais: mobile, tablets e desktops. Durante o curso, serão abordados elementos como cabeçalho, seção de banner, categorias, destaques, próximos eventos, coloque na sua agenda e rodapé. É importante ter realizado os cursos indicados como pré-requisitos para ter uma base sólida e poder aplicar os conhecimentos adquiridos em outros projetos.

### Aula 01 - Combo do Flex - Video 2

Nesta aula do curso "Praticando CSS: Grid e Flexbox", o instrutor Luan introduz os conceitos de Flexbox e Grid, que são tecnologias utilizadas no desenvolvimento Front-end. Ele mostra como abrir o projeto no VS Code e como criar um arquivo flex.css para organizar o cabeçalho do projeto Culturama usando o Flexbox. São aplicadas diversas propriedades do Flexbox, como display, justify-content, align-items, flex-wrap e column-gap, para criar um layout responsivo. O instrutor também menciona a extensão Live Server para visualizar o projeto no navegador.

### Aula 01 - Alinhando eixos - Video 3

Nesta aula, o Luan discute sobre a finalização do cabeçalho para celulares do projeto Culturama e a organização dos elementos para telas de tablets. Ele menciona a necessidade de alinhar a logo e o botão "Seu local" com as margens da página. O Luan mostra o código no arquivo flex.css e explica o uso da instrução @media para aplicar estilos apenas para telas de pelo menos 720 pixels de largura. Ele utiliza o "Inspecionar" do navegador para auxiliar na construção do layout. O Luan aumenta o column-gap para expandir o espaçamento entre os itens, movendo a logo para a esquerda e o botão "Seu local" para a direita. Ele conclui que 75px é um valor adequado para alinhar os elementos. O código atualizado no @media chama a classe .menu e aplica a propriedade column-gap com o valor de 75 pixels. O Luan compara o layout do Figma com o resultado obtido e conclui que o cabeçalho para telas de tablets está finalizado.

### Aula 01 - Para saber mais: propriedade gap

A propriedade gap do flexbox e grid, é utilizada para aplicar distância no sentido horizontal e vertical entre elementos em um layout, sua função é similar à propriedade margin.

column-gap  
A propriedade column-gap serve para criar uma lacuna vertical entre elementos.

row-gap  
Já a propriedade row-gapserve para criar uma lacuna horizontal entre elementos.

gap  
E caso você utilize simplesmente a propriedade gap, ela irá criar espaçamentos tanto no sentido vertical quanto horizontal.

### Aula 01 - Para saber mais: Flex e Grid - direções invertidas

Trabalhando com Linhas e Colunas
No flex, quando utilizamos a propriedade flex-direction: row, estamos organizando os elementos um ao lado do outro, trabalhando com o eixo x ou horizontal.

Já no grid, quando utilizamos a propriedade grid-template-rows estamos calculando a altura das linhas e consequentemente, modificamos o eixo y ou vertical.

O mesmo ocorre com as colunas, no flex a propriedade flex-direction: column dispõe os elementos um abaixo do outro, ou seja, no eixo y ou vertical.

E no grid, a propriedade grid-template-columns serve para criar e calcular a largura das colunas, sendo assim, estamos alterando o eixo x ou horizontal.

### Aula 01 - Container x Item - Video 4

Nesta aula, o instrutor Luan finaliza o cabeçalho do projeto Culturama, focando nas telas de desktops. Ele utiliza as propriedades do Flexbox para corrigir a ordem dos elementos e garantir que fiquem alinhados na mesma linha. Ele também utiliza a propriedade order para reordenar os elementos do cabeçalho. Além disso, Luan menciona que o Grid será utilizado para o banner na parte inferior.

### Aula 01 Conclusão - Nessa aula, você aprendeu como:

Organizar elementos com display flex;
Entendeu qual o eixo padrão dos itens flex;
Aprendeu como organizar grupos de itens na horizontal e vertical;
Diferenciar flex-item e flex-container.

## Aula 02 - Play no Grid

### Aula 02 - Display: Grid - Video 1

