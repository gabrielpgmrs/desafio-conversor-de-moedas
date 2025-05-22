# 🪙 Conversor de Moedas


<div align="center">

<p align="center" dir="auto"><em>Conversor de moedas em tempo real utilizando uma API!</em> 🚀</p>
</div>

## 📋 Sobre o Projeto

Este é projeto desenvolvido como parte do desafio **Oracle Next Education (ONE)**. O projeto permite converter diferentes moedas utilizando taxas de câmbio em tempo real através da API ExchangeRate, visualizar o histórico das operações e exportar esse histórico para um arquivo JSON.

## ✨ Funcionalidades

### **Conversão de moedas:**

- Dólar (USD) → Real (BRL)
- Euro (EUR) → Real (BRL)
- Real (BRL) → Dólar (USD)
- Libra (GBP) → Euro (EUR)
- Dólar (USD) → Iene (JPY)
- Real (BRL) → Peso Argentino (ARS)

1. **Histórico completo de conversões** <br>
2. **Exportação do histórico para arquivo JSON** <br>
3. **Interface de console intuitiva e amigável** <br>
4. **Taxas de câmbio atualizadas em tempo real**

## 🛠️ Tecnologias Utilizadas

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![API REST](https://img.shields.io/badge/API%20REST-0078D4?style=for-the-badge&logo=microsoftedge&logoColor=white)

</div>

- **Java 17** - Linguagem de programação principal
- **API ExchangeRate (v6)** - Fornecimento de taxas de câmbio atualizadas
- **Biblioteca Gson** - Manipulação de dados em formato JSON
- **HttpClient do Java** - Realização de requisições HTTP para API

## 📊 Exemplo de Uso

```
┌──────────────────────────────────┐
│       CONVERSOR DE MOEDAS        │
└──────────────────────────────────┘
│ 1. Dólar (USD) → Real (BRL)      │
│ 2. Euro (EUR) → Real (BRL)       │
│ 3. Real (BRL) → Dólar (USD)      │
│ 4. Libra (GBP) → Euro (EUR)      │
│ 5. Dólar (USD) → Iene (JPY)      │
│ 6. Real (BRL) → Peso Arg. (ARS)  │
│ 7. Histórico de conversões       │
│ 0. Sair                          │
└──────────────────────────────────┘
Digite sua opção: 1

▷ Digite o valor a ser convertido:
  $ 100

▷ Consultando taxas de conversão...

┌───────────────────────────────────────┐
│          RESULTADO DA CONVERSÃO       │
└───────────────────────────────────────┘
  100.00 USD = 567.32 BRL
└───────────────────────────────────────┘
```

## 🔄 API ExchangeRate

O projeto utiliza a API ExchangeRate (v6) para obter taxas de câmbio atualizadas em tempo real.

- **Documentação**: [https://www.exchangerate-api.com/docs/pair-conversion-requests](https://www.exchangerate-api.com/docs/pair-conversion-requests)
- **Endpoint utilizado**: `https://v6.exchangerate-api.com/v6/API_KEY/pair/BASE/TARGET`


## 🙏 Agradecimentos

Oracle/Alura e ao programa Talentos do futuro pela oportunidade e desafio proposto.

<div align="center">

Desenvolvido com ❤️


</div>
