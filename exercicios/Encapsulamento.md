# Exercícios sobre Encapsulamento (e Arrays)

Vamos criar um aplicativo para reproduzir músicas. Suponha que estamos criando o Spotify.
Primeiro, crie uma classe Musica com os seguintes atributos: **nome, artista, letra, gênero (use Enum), ano de lançamento, duração, número de vezes que foi reproduzida**.
Em seguida, crie a classe Spotify.
Spotify deve ter um array de Músicas (não preciso dizer que esse array deve estar encapsulado, né?).
O construtor sem argumentos de Spotify inicializa o array com tamanho 10.
Crie um construtor com argumentos para Spotify que permita inicializar o array com um tamanho específico.
Crie uma função que te permita:
- adicionar uma música no Spotify;
- saber quantas músicas existem no seu Spotify;
- remover uma música pelo nome da música;
- listar todas as músicas de um artista;
- listar todas as músicas lançadas em um ano específico;
- listar todas as músicas de um gênero;
- retornar a música de maior duração;
- retornar a música de menor duração;
- reproduzir uma música no Spotify;
- saber quantas vezes uma determinada música foi reproduzida;
- retornar o gênero mais popular;
- listar todas as músicas de um gênero.

Por fim, crie um main, adicione uma série de músicas de diferentes artistas e gêneros, e teste cada um de seus métodos.