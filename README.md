# Como votou sua vizinhança?

Notebooks com adaptação do método desenvolvido pelo jornal Estadão, publicado na matéria "Como votou sua vizinhança":<br>
https://www.estadao.com.br/infograficos/politica,como-votou-sua-vizinhanca-explore-o-mapa-mais-detalhado-das-eleicoes,935858

Material original disponível em:<br>
https://github.com/estadao/como-votou-sua-vizinhanca

A partir de um conjunto de endereços, são gerados os pontos georreferenciados (por meio da API do Google Maps). Então são gerados os contornos/polígonos utilizando o diagrama de Voronoi.

![imagem](https://github.com/vinicius-macario/como-votou/blob/ca8ebf4edd757fee47a454ad21e48f21e465262a/georreferenciamento.png)

Os notebooks foram desenvolvidos para o Google Colab.

Para acessar os arquivos diretamente no Google Drive:<br>
https://drive.google.com/drive/folders/1k64B61NTR3evFQPSyR0PxF7Rim3leymQ?usp=share_link


A estrutura de pastas necessária é a seguinte:
geodata\ <br>
geodata\geocode<br>
geodata\shp_municipio-ibge<br>
geodata\voronois\ <br>
geodata\voronois\clipados<br>
geodata\voronois\final<br>
geodata\voronois\merge<br>
geodata\voronois\pontos-cidade<br>
geodata\voronois\pre-clip<br>
locais\ <br>
votos\ <br>
votos\01_boletim-urna-original<br>
votos\02_boletim-urna-ajustado<br>
votos\03_votos_consolidado<br>
votos\04_votos_final<br>
