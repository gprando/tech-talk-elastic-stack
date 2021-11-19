# Talk sobre elastic stack

> Para exemplo foi utilizado o template de elk -> https://github.com/codeedu/elastic-stack-template

## Baixar dataset e descompactar

```bash
# download via curl
curl https://data.brasil.io/dataset/covid19/caso_full.csv.gz -o ./logstash/csv/caso_full.csv.gz

# descompactar
gunzip ./logstash/csv/caso_full.csv.gz
```