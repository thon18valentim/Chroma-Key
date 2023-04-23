# Chroma Key

Chroma Key de imagens desenvolvido em python, utilizando bibliotecas como opencv, matplotlib e numpy.

## Orientações
Para testar o algoritmo criado, faça o upload de uma imagem no notebook e passe o nome do arquivo para 
a variável "arquivo_nome".

```python Codigo abaixo
arquivo_nome = 'rainha'
img = cv2.imread(f'{arquivo_nome}.bmp')
```
Vale ressaltar que o código está esperando arquivos no formato bmp.

Para o background, o arquivo obrigatoriamente deve se chamar "background".
