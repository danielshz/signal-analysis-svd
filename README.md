# 📈 Processamento de sinais com SVD

Este repositório contém o código e exemplos referentes à decomposição em valores singulares (SVD) aplicada no processamento de sinais.

## 📡 Sinais

O processamento de sinais envolve o tratamento e a análise de dados observados que representam algum fenômeno, geralmente ao longo do tempo. Nesse contexto, alguns exemplos de sinais incluem:

- Áudios
- Imagens
- Vídeos
- Redes sem fio
- Fenômenos físicos

## 🎯 Objetivo

Este projeto tem como objetivo aplicar a **Decomposição em Valores Singulares (SVD)** para:

- **Remover ruídos** de sinais
- **Comprimir** dados (áudios, imagens, vídeos)
- **Reduzir a dimensionalidade** de sinais para facilitar a análise

## ❓ Por que processar sinais?

Em diversos cenários do mundo real, os diferentes sinais medidos podem conter ruídos e interrupções. Dessa forma, o processamento de sinais permite:

- Identificar objetos em imagens e vídeos
- Remover ruídos de áudios
- Comprimir áudios, imagens e vídeos para reduzir armazenamento e melhorar a eficiência

## ⚙️ Como funciona o processamento de sinais com SVD?

1. **Sampling**: Como sinais são contínuos, realizamos uma amostragem, dividindo-os em intervalos regulares de tempo. Quanto menor o intervalo, mais precisa será a representação do sinal.
2. **Estruturação matricial**: Os valores amostrados de diferentes sinais são agrupados em uma matriz.
3. **Aplicação do SVD**: A decomposição SVD é aplicada à matriz, separando os componentes essenciais do sinal e eliminando os ruídos.

## 🛠️ Técnicas utilizadas

- **Decomposição SVD** para compressão e remoção de ruído
- **Análise de valores singulares** para identificar a importância de diferentes componentes em um sinal
- **Redução de dimensionalidade** para avaliar padrões e propriedades dos sinais analisados

### 📊 Casos analisados

- Sinais com diferentes níveis de ruído
- Comparação de valores singulares para diferentes sinais
- Reconstrução de sinais com e sem ruído

## 🏆 Resultados

A aplicação da técnica SVD se mostrou eficaz para remoção de ruído e compressão de sinais em alguns cenários, conforme mostrado nos exemplos contidos neste repositório.

## Autores

- [Daniel Arruda](https://github.com/danielshz)
- [Manoel Silva](https://github.com/manoelmms)
- [Pedro Jorge](https://github.com/pedro-jorge)
