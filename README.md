# nuvem-semana1-guilherme-frank

## Links
- Repositorio: https://github.com/Guilherme60HZ/nuvem-semana2-guilherme-frank/blob/main/
- Site (GitHub Pages): https://guilherme60hz.github.io/nuvem-semana2-guilherme-frank/

## O que foi feito Semana1-atividade 1
- Criei index.html, style.css e script.js pelo navegador
- Ativei GitHub Pages (main / root)

## Dificuldades
- Não tive dificuldades, porque isso já foi ensinado anteriormente por outros professores.

##Oque foi feito Semana2-atividade 2

##Foi implementado o consumo de API com fetch:

##GET na API de clima (Open-Meteo)

##JSONPlaceholder

##Tratamento de erro com try/catch

Tinha aparecido um erro 404 no console, mas ao atualizar a pagina ele não apareceu mais.

<img width="984" height="679" alt="image" src="https://github.com/user-attachments/assets/e396f38f-7de1-4a11-b905-1cbcccae0d28" />

##Oque foi feito Semana2-atividade 3

### O que foi feito
- Implementado consumo de API usando fetch(feito na atividade anterior)
- Requisição GET para API de clima(feito na atividade anterior)
- Requisição POST simulada usando JSONPlaceholder(feito na atividade anterior)
- Busca de clima por cidade usando geocoding + forecast
- Salvando última cidade no localStorage

### APIs usadas
- Open Meteo Geocoding API
- Open Meteo Forecast API
- JSONPlaceholder

### Teste
Após recarregar a pagina algumas vezes e buscar pela cidade, o site faz duas requisições:
1. Geocoding para converter a cidade em latitude e longitude
2. Forecast para buscar o clima atual usando essas coordenadas
