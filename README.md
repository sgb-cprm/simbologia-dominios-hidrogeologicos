# Biblioteca de Estilos para Mapas Temáticos da SGB/CPRM para ArcGIS 10.x e QGIS 3.x: Domínios Hidrogeológicos

- Elias Bernard S. do Espirito Santo <elias.bernard@cprm.gov.br>
- Carlos Eduardo Miranda Mota <carlos.mota@cprm.gov.br>
- Flavia Renata Ferreira <flavia.ferreira@cprm.gov.br>

## Apresentação

Este produto consiste em disponibilizar as paletas de cores correspondente a biblioteca de domínios hidrogeológicos da SGB/CPRM, em versões compatíveis com os softwares ArcGIS 10.x e QGIS 3.x. Originalmente esta biblioteca foi construída sob o formato ESRI Style (.style), com posterior conversão paa QGIS Style (.xml). 

O processo de conversão para QGIS Style foi realizado através do plugin SLYR v4.0.1 Community Edition (https://north-road.com/slyr/), em uma instalação de QGIS 3.16.16 para Windows. Este produto foi testado em ambientes Windows 10 e Ubuntu Linux 20.04 LTS.

Caso seja encontrado algum erro ou inconsistência na biblioteca, pedimos a gentileza que nos reporte o problema a partir dos canais oficiais da SGB/CPRM ou via contato direto com os autores.

## Organização do Conteúdo

### Diretório `esri-style`

Este diretório contém o arquivo de estilos para o ESRI ArcGIS Desktop (.style). Originalmente, e por questões de legado, as tabelas de cores e símbolos são confeccionadas nesta plataforma.

### Diretório `qgis-xml`

Este diretório contém o arquivo de estilos para o QGIS (.xml). Como este arquivo, por enquanto, é obtido a partir de conversão dos originais em .style, também é disponibilizado o log de execução da conversão da biblioteca para o formato do QGIS.

## Instalação da Biblioteca de Estilos

Veja no arquivo README.md dos diretórios `esri-style` e `qgis-xml` as páginas de documentação para instalação das bibliotecas.

Se as bibliotecas dependerem de arquivos de fontes para renderizar os símbolos corretamente, é necessário fazer a instalação dos arquivos de fonte .OTF antes de iniciar o software de GIS/SIG.

Para instalação de fontes no Windows, [veja este link](https://support.microsoft.com/pt-br/office/adicionar-uma-fonte-b7c5f17c-4426-4b53-967f-455339c564c1).

## Disclaimer

Copyright © 2022, Serviço Geológico do Brasil/CPRM

"Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, su
subject to the following conditions"

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION

## License/Licença

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg