# Galeria dinâmica para apresentação de trabalhos
Galeria dinâmica para visualização de trabalhos da área da tecnologia da informação.

1. Clone o respositório
2. Crie o arquivo JSON dentro da raiz com o nome ***dados.json*** contendo a seguinte estrutura:
```json
[
  {
    "trabalhos": [
      { 
        "titulo": "Galeria dinâmica",
        "descricao": "Galeria para exibição de projetos dinâmica através da leitura dos dados de um arquivo JSON",
        "linguagens": "HTML;CSS;JavaScript;Bootstrap;JQuey;galleria.js",
        "autores": "Marco Antoni;Outro autor",
        "imagens": ["teste.png", "IMG_20120427_145213.jpg", "teste.png"]
      }
    ]
  }
]
```
  - linguagens: string separada por ";". Será exibido na tela detalhes.
  - autores: string separada por ";". Será exibido na tela detalhes.
  - imagens: array que contém o nome das imagens que serão exibidas na tela detalhes. Por padrão as imagens devem estar dentro da pasta ```images```
3. Suba um servidor HTTP, depois acesse o endereço [http://127.0.0.1:8000](http://127.0.0.1:8000).
```sh
$ python -m SimpleHTTPServer
```


