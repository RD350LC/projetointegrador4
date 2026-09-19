Documentação Projeto integrador 4 Univesp

_Por iniciativa colaborativa foi criado uma imagem docker com o motor do jupyter notebook e Rsudio. 
que facilita a execução de codigos e scripts necessarios para a execucão do trabalho de analise em escala em qualquer maquina de qualquer aluno que tiver instalado 
o docker na maquina, bastanto apenas rodar um comando no prompt especificando as portas a senha e o nome da imagem a ser executado da imagem .

Requesitos para rodar o motor do Jupyter e Rstudio : 'Ter instalado na maquina o docker '

docker run -e PASSWORD='3x3mpl0d3s3nh4' -p 8787:8787 -p 8888:8888 nomedaimagemcomomotor/v1 #(exemplo do caminho da imagem baixado via dockerhub)
no campo password coloque a senha que desejar . Para alternar entre o jupyter notebook e o Rstudio so e necessario alterar no seu navegador entre a porta 8787 para 8888