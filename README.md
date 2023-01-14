# leitos_em_goias_pandemia
## Análise da variação de leitos em Goiás
- Participante: César Noronha
- Email: cesarsnoronha@gmail.com

## Arquivos nesse repositório:
- main.ipynb 
    - Esse é o principal arquivo deste github. Nele está a análise de dados, testes estatísticos, os gráficos e as conclusões do projeto.
- database/raw
    - Nessa pasta temos os arquivos .csv com os dados mês a mês para a quantidade de leitos em Goiás. Esses arquivos foram baixados do DataSUS através de uma imagem em Docker seguindo as orientações no link a seguir: https://github.com/AlertaDengue/PySUS/blob/master/README.md
    - Nessa pasta também temos o arquivo Data_processing.ipynb, nele os arquivo .csv da pasta são baixados, transformados e dataframes, processados e salvos na pasta database/processed.
- database/processed
    - Nessa pasta temos arquivos .csv ja editados e processados.
- images
    - Nessa pasta temos o arquivo image_generator.ipynb, nele utilizamos os dataframes salvos em database/processed para gerar as imagens.
    - Nessa pasta também temos os arquivos .jpg, que são as imagens geradas para a análise.


## Conclusões
- Observamos que houve um aumento na quantidade de leitos SUS e não-SUS para o estado de Goiás durante a pandemia.
- Observamos que a quantidade total de leitos no SUS é superior a quantidade de leitos na iniciativa privada para o período de tempo apresentado.
- Testamos estatisticamente a diferença entre a quantidade de leitos SUS e não-SUS durante a pandemia, e observamos que há diferença significativa Quando observamos o estado como um todo e quando observamos cidade por cidade. O mesmo resultado é observado quando testamos apenas as 20 cidades com mais leitos.
- Observamos também que temos uma correlação forte entre a quantidade de leitos SUS e de leitos não-SUS e entre a quantidade de leitos SUS e de leitos não-SUS quando observamos cidade por cidade. 
- Através da figura 3 podemos observar que há meses de aumento no números de leitos, meses de redistribuição de leitos no estado e meses de redução no números de leitos.
- Ao analisarmos os dois momentos de redução de dados em destaque na figura 4, podemos observar uma redução através do boxplot para o segundo momento na figura 5, mas não observamos uma redução para o primeiro momento. 
- Não obtivemos diferença estatística para o momento de redução no total de leitos no que aconteceu no durante a pandemia, mas pudemos observar uma diferença significativa para a redução que ocorre após a pandemia.
- Podemos observar através da figura 6 que mesmo durante o segundo momento de redução de leitos, temos também a abertura de leitos ocorrendo, ou seja, uma redeistribuição de leitos.
- Através da figura 8 podemos observar que o aumento de leitos que ocorreu durante a pandemia foi distribuído entre as cidades. E que mesmo durante esse momento temos momentos de redução de leitos e de redistribuição.


