# renamer

Aplicacao para renomear e mover automaticamente series e filmes para o 
diretorio desejado;

## Configuracoes:

A configuracao e realizada a partir do arquivo config.json
presente na mesma pasta da aplicacao:

{
    "tvshow_regexp": "",
    "movie_regexp": "",
    "tvshow_path": "",
    "movie_path": "",
    "ignored_ext": [],
    "min_size": 0
}

### tvshow_regex
REGEXP para definir se o arquivo e uma serie de tv e para renomea-lo


### movie_regex
REGEXP para definir se o arquivo e um filme e para renomea-lo


### tvshow_path
Pasta destino para os arquivos de series de TV


### movie_path
Pasta destino para os arquivos de filmes


### ignored_ext
Lista de extensoes ignoradas e que serao excluidas pela aplicacao


### min_size
Tamanho minimo dos arquivos que serao movidos. Arquivos menores serao 
excluidos
