# bzip2

> Um compressor de arquivos que utiliza o algoritmo Burrows–Wheeler.
> Mais informações: <https://manned.org/bzip2>.

- Compactar um arquivo:

`bzip2 {{arquivo}}`

- Descompactar um arquivo:

`bzip2 -d {{arquivo_compactado.bz2}}`

- Descompactar um arquivo exibindo o conteúdo no terminal:

`bzip2 -dc {{arquivo_compactado.bz2}}`

- Testar a integridade de cada arquivo dentro do arquivo compactado:

`bzip2 --test {{caminho/para/arquivo_compactado.bz2}}`

- Exibir a taxa de compressão para cada arquivo processado com informações detalhadas:

`bzip2 --verbose {{caminho/para/arquivos_compactados.bz2}}`

- Descompactar um arquivo sobrescrevendo arquivos existentes:

`bzip2 --force {{caminho/para/arquivo_compactado.bz2}}`

- Exibir ajuda:

`bzip2 -h`
