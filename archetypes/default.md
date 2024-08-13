+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
[params]
    titulo = '{{ replace .File.ContentBaseName "-" " " | title }}'
    capa = 'default-img.png'
    alt = 'Capa {{ replace .File.ContentBaseName "-" " " | title }}'
    descricao = '...'
+++
