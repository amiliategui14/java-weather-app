# 🌦️ Java Weather App

Aplicação desenvolvida em Java que consulta informações meteorológicas em tempo real utilizando a WeatherAPI.

O usuário informa o nome de uma cidade e o sistema retorna os dados climáticos atuais, como temperatura, sensação térmica, umidade, velocidade do vento e pressão atmosférica.

---

## 📷 Funcionalidades

- Buscar clima de qualquer cidade.
- Exibir temperatura atual.
- Exibir sensação térmica.
- Exibir condição do tempo.
- Exibir umidade do ar.
- Exibir velocidade do vento.
- Exibir pressão atmosférica.
- Tratar cidade inexistente.

---

## 🛠 Tecnologias utilizadas

- Java 17+
- Java HTTP Client
- JSON-Java (org.json)
- WeatherAPI
- VS Code

---

## 📂 Estrutura do projeto

```
java-weather-app/
│
├── src/
│   └── ClimaticasEmTempoReal.java
│
├── lib/
│   └── json-20230618.jar
│
├── api-key.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/java-weather-app.git
```

### 2. Obtenha uma chave da WeatherAPI

Crie uma conta gratuita em:

https://www.weatherapi.com/

Depois crie um arquivo chamado:

```
api-key.txt
```

Na raiz do projeto e coloque apenas sua chave:

```
SUA_CHAVE_AQUI
```

---

### 3. Adicione a biblioteca JSON

Baixe o arquivo `json-20230618.jar` e coloque dentro da pasta:

```
lib/
```

---

### 4. Compile

```bash
javac -cp "lib/json-20230618.jar" src/ClimaticasEmTempoReal.java
```

---

### 5. Execute

```bash
java -cp "src;lib/json-20230618.jar" ClimaticasEmTempoReal
```

---

## 💻 Exemplo

```
Digite o nome da cidade: Rio de Janeiro

Informações Meteorológicas

Cidade: Rio de Janeiro
País: Brazil

Temperatura Atual: 27.3°C
Sensação Térmica: 30.1°C
Condição do Tempo: Parcialmente nublado
Umidade: 76%
Velocidade do Vento: 18 km/h
Pressão Atmosférica: 1016 mb
```

---

## 📚 Objetivo

Este projeto foi desenvolvido para praticar:

- Consumo de APIs REST
- Requisições HTTP em Java
- Manipulação de JSON
- Entrada de dados pelo usuário
- Tratamento de exceções
- Organização de projetos Java

---

## 🚀 Melhorias futuras

- Interface gráfica com JavaFX.
- Previsão para vários dias.
- Histórico de consultas.
- Favoritos.
- Integração com banco de dados (JDBC).
- Busca automática por localização.

---

## 👩‍💻 Desenvolvido por

**Rafaela Amiliategui**

GitHub: https://github.com/amiliategui14
