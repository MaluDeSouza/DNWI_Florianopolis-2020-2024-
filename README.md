
# Monitoramento Costeiro - Florianópolis

Este projeto tem como objetivo o monitoramento costeiro da região de Florianópolis utilizando imagens Sentinel-2 e o cálculo do NDWI (Normalized Difference Water Index) para análise de mudanças na umidade superficial e áreas alagadas entre os anos de 2020 e 2024.

---

## Estrutura do Projeto

- `assets/`  
  Contém os dados brutos utilizados, incluindo o arquivo `BR_Municipios_2024.zip` com os municípios do Brasil.

- `code/`  
  Scripts em Google Earth Engine para carregamento, processamento e análise das imagens Sentinel-2.

- `docs/`  
  Documentação e relatórios gerados, incluindo o relatório de análise estatística do NDWI para os anos 2020 e 2024.


---

## Dados Utilizados

- Imagens Sentinel-2 SR Harmonized (`COPERNICUS/S2_SR_HARMONIZED`), filtradas por período e porcentagem de nuvens.
- Shapefile dos municípios do Brasil (arquivo em `assets/BR_Municipios_2024.zip`).

---

## Análise

Foi calculado o NDWI para os anos de 2020 e 2024, com uma média de -0.104 para 2020 e -0.112 para 2024 na região de Florianópolis. Essa variação sugere um leve aumento na presença de superfícies menos úmidas ou com menor cobertura de água, o que pode estar relacionado a mudanças ambientais locais.

---

## Como Executar

Os scripts em `code/` podem ser executados na plataforma Google Earth Engine para replicar o processamento e a geração dos mapas.

---

## Relatório

O relatório completo com a análise estatística está disponível na pasta `docs/` no arquivo [`relatorio-monitoramento-floripa.docx`](docs/relatorio-monitoramento-floripa.pdf).

---

## Contato

Caso tenha dúvidas ou queira contribuir, entre em contato pelo e-mail maludesouza2111@gmail.com

---

*Projeto desenvolvido para fins de monitoramento ambiental costeiro utilizando dados abertos de satélite.*
