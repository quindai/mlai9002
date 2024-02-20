# Azure Vision Studio

Ao abrir o Azure Vision Studio no link https://portal.vision.cognitive.azure.com/ somos apresentados à tela de boas vindas com os modelos prontos para serem testados.

| Portal Vision Studio                            | 
| ----------------------------------- |
| ![Best Model](outputs/vision1.jpeg) |


Rodei uma série de testes com os modelos disponíveis no Vision Studio e os resultados são bem impressionantes, mas, ainda há dificuldade em detetar poster de animação com fotografia de um humano ou desenho animado.
Levanta algumas questões preocupantes de segurança se for usar algum desses modelos em produção, mas dá para brincar :)

## Banco de Imagens de Entrada
Descrição breve das imagens usadas nos testes. 

Todas as imagens estão disponíveis na pasta [`inputs`](https://github.com/quindai/mlai9002/tree/main/inputs). 
| avengers-ca.jpg  | randy-qquant.jpeg (me)  | avengers.jpg  |  mib.jpg  |  bob-marley.jpg  | 
| ----------------------------------- | ----------------------------------- | ----------------------------------- | ----------------------------------- | ----------------------------------- |
| <img src="inputs/avengers-ca.jpg" alt="Avengers Anime" width="150vw"/> | <img src="inputs/randy-qquant.jpeg" alt="Randy Qquant (Me)" width="150vw"/> | <img src="inputs/avengers.jpg" alt="Avengers" width="150vw"/> | <img src="inputs/mib.jpg" alt="MIB" width="150vw"/> | <img src="inputs/bob-marley.jpg" alt="Bob Marley" width="150vw"/> |

## Resultados Obtidos no Vision Studio
### avengers-ca
| Add captions to images  | Add dense captions to images 1 | Add dense captions to images 2  | 
| ----------------------------------- | ----------------------------------- | ----------------------------------- |
| <img src="outputs/avengers-ca-addcaption.jpeg" alt="Avengers Anime" width="350vw"/> | <img src="outputs/avengers-ca-addcaption-dense.jpeg" alt="Randy Qquant (Me)" width="350vw"/> | <img src="outputs/avengers-ca-addcaption-dense1.jpeg" alt="Avengers" width="350vw"/> | 

### randy-qquant
| Extract common tags from images  | Add dense captions to images 1 |
| ----------------------------------- | ----------------------------------- | 
| <img src="outputs/randy-qquant-extract.jpeg" alt="Avengers Anime" width="350vw"/> | <img src="outputs/randy-qquant-addcaption-dense.jpeg" alt="Randy Qquant (Me)" width="350vw"/> |
