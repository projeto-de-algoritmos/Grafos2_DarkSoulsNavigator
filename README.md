# Grafos1_SongRecommendation

**Número da Lista**: 2<br>
**Conteúdo da Disciplina**: Grafos 1 e Grafos 2<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 17/0017885  | Marcos Nery Borges Júnior |

## Sobre 
Dark Souls é um jogo eletrônico do gênero RPG (Role Playing Game) que faz parte de uma das séries de jogos mais populares dentro da categoria, a série Souls. Essa série é especialmente conhecida por ter uma dificuldade acentuada. Em especial, o Dark Souls 1, tema deste deste projeto, tem essa dificuldade muito relacionada com o design do mapa. Isso porque os designers que criaram o mapa do jogo modelaram ele a partir de um labirinto, de forma que existem muitas ligações entre as diferentes áreas e não há nenhum tipo de mapa ou bússola que dentro do jogo vá te dizer para onde ir.

Essa característica do mapa faz com que muitos novos jogadores acabem indo parar em áreas de um nível de dificuldade muito superior ao nível do seu personagem, e sem saber como voltar ou se estão no lugar correto, acabam ficando travados e muitos até desistem do jogo. A ideia aqui é prover um algoritmo que calcula o caminho mais fácil para chegar ao destino que o jogador deseja, partindo do ponto onde ele está.

Mais que isso, essa ideia também será usada para indicar ao jogador qual caminho seguir para encontrar certos itens que ele deseja.

## Screenshots
### Jupyter notebook
<img style="max-width: 800px" src="notebook1.png">
<img style="max-width: 800px" src="notebook2.png">

## Instalação 
**Linguagem**: Python >= 3.8 <br>
**Ferramentas**: Jupyter Notebook <br>


O projeto foi feito através do Jupyter notebook, que reune em um só lugar todo o código e a explicação de cada uma das etapas. 
Para executar/visualizar o notebook basta instalar o jupyter notebook na sua maquina através das instruções dispostas na seção "Getting started with the classic Jupyter Notebook" [aqui](https://jupyter.org/install). [Você também pode executar o jupyter notebook através do navegador](https://mybinder.org/v2/gh/ipython/ipython-in-depth/master?filepath=binder/Index.ipynb) (não recomendado) ou utilizar o docker (opção mais fácil), seguindo as instruções mais abaixo.

Se desejar apenas visualizar o jupyter notebook, basta ver o arquivo [wherearemykeys.ipynb](https://github.com/projeto-de-algoritmos/Grafos1_SongRecommendation/blob/master/songs_recommendation.ipynb) pelo próprio GitHub.


## Instalação com Docker

Se você tiver docker na sua máquina tudo fica mais fácil. Basta executar o comando `docker-compose up` e o ambiente estará em funcionamento.
  
  * Para acessar o jupyter notebook basta ir até http://localhost:8888/ (o token de autenticação é exposto no terminal ao rodar o compose-up)


