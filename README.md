# Producao de Ovos no Brasil

## Objetivo do Projeto

Este projeto tem como objetivo analisar a produção de ovos no Brasil ao longo dos anos, utilizando dados do IBGE via API Sidra. A análise inclui:

- Tendências de produção.
- Variação percentual trimestral.
- Representação gráfica das séries temporais.

## Requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- Python 3.8+
- Bibliotecas necessárias:
  ```bash
  pip install -r requirements.txt
  ```

## Como Usar

1. Execute o script principal:
   ```bash
   python main.py
   ```
2. O código irá:
   - Conectar ocm os dados do IBGE/Sidra.
   - Processar e limpar os dados.
   - Gerar gráficos para análise.


## Documentação do SIDRA

Aqui: http://api.sidra.ibge.gov.br/home/ajuda

## Documentação do sidrapy
Aqui: https://sidrapy.readthedocs.io


## Exemplos de Gráficos

### 1. Produção de Ovos para Consumo no Brasil (2012-2024)

A primeira análise realizada foi a visualização da produção trimestral de ovos para consumo no Brasil de 2012 a 2024.

![Serie_Temporal](https://github.com/user-attachments/assets/a45ca878-64ac-46af-a642-01a3c4404c6b)


Essa série temporal mostra o crescimento contínuo da produção de ovos ao longo dos anos, com algumas flutuações sazonais. O aumento da produção pode estar relacionado à maior demanda por ovos devido a mudanças nos hábitos alimentares e ao crescimento populacional.

### 2. Variação Percentual Trimestral da Produção
Para entender a tendência de longo prazo, aplicamos uma regressão linear aos dados históricos, permitindo visualizar a direção geral do crescimento da produção de ovos.

![Variacao_Percentual](https://github.com/user-attachments/assets/aafad65e-b104-45fd-a4c6-16aa8e7b5236)


A linha vermelha representa a tendência de longo prazo, indicando um aumento constante na produção. Embora haja oscilações nos valores trimestrais, a tendência geral é de crescimento.


### 3. Tendência de Longo Prazo

Analisamos também a variação percentual da produção de ovos entre os trimestres.

![Regressao_Linear](https://github.com/user-attachments/assets/c05c5755-9d6b-468a-a2e1-b758a929bd09)


Este gráfico destaca as oscilações na produção de ovos ao longo do tempo. Períodos com grandes variações podem indicar impactos sazonais, crises no setor ou mudanças na demanda e na oferta.

### Conclusão

A análise revela um crescimento constante na produção de ovos no Brasil, com flutuações trimestrais que podem estar ligadas a fatores sazonais ou econômicos. Com esses dados, é possível aprofundar a investigação sobre as causas das variações e prever tendências futuras, auxiliando na tomada de decisões para o setor avícola.

## Contribuição

Sinta-se à vontade para contribuir com melhorias! Abra uma issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a MIT License.

