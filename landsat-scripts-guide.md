## Input download
### googleapi
1. Baixa essa [planilha](https://storage.googleapis.com/gcp-public-data-landsat/index.csv.gz) da [google cloud](https://console.cloud.google.com/storage/browser/gcp-public-data-landsat;tab=objects?_ga=2.201958481.1981055894.1666204687-247717271.1665359034&pli=1&prefix=&forceOnObjectsSortingFiltering=false)
1. Os dados dessa cloud vem da [NASA](https://landsat.gsfc.nasa.gov/) em conjunto da [USGS](https://landsatlook.usgs.gov/explore)

### usgapi
1. Uma requisição é montada e os dados são baixados do site da [USGS EarthExplorer](https://earthexplorer.usgs.gov)
    - Exemplo: https://earthexplorer.usgs.gov/download/external/options/LANDSAT_TM_C1/LT52150651985107CUB00/INVSVC/
    - OBS: é preciso ter conta para baixar a imagem

## Preprocessing
### default
- Pega os dados do /inputdownload e executa um script em R

### legacy
- Pega uns dados no repositório de thiago (?)
- Pega os dados do /inputdownload e executa um script em R


## Processing
### SBK-Sebal
- Processa dos dados de dados.csv

### SBK-Tseb
- Processa dos dados de dados.csv

### UFCG-Sebal
- Processa dos dados de dados.csv
