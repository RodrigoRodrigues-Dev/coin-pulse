<h1 align="center">
  CoinPulse
</h1>

<p align="center">
  <img src=".github/Preview_Home.png" width="100%" />
</p>

O **CoinPulse** é um DashBoard moderno e responsivo construído com Vue.js e Vuetify. A plataforma permite que os usuários acompanhem dados de mercado de criptomoedas em tempo real, gerenciem seus ativos favoritos e visualizem gráficos detalhados para análises personalizadas.

## 💻 Visão Geral

O **CoinPulse** oferece uma experiência intuitiva e funcional para entusiastas de criptomoedas, com recursos que incluem:

- Navegação interativa por mercados de criptomoedas.
- Acompanhamento de preços e volumes em tempo real.
- Gestão de ativos favoritos com sincronização ao Firebase.
- Visualização de gráficos dinâmicos e análises visuais dos ativos.
- Interface responsiva, projetada com Vuetify para excelente usabilidade em diferentes dispositivos.

A aplicação utiliza o **Firebase** para autenticação e gerenciamento de dados do usuário, garantindo uma experiência personalizada e segura. Além disso, integra o **Pinia** para gerenciamento de estado e **Chart.js** para criação de gráficos interativos.

## ⚙️ Funcionalidades

- **Navegação por Tickers:** Visualize informações detalhadas sobre os tickers, incluindo preço, volume e pares de mercado.
- **Gerenciamento de Favoritos:** Adicione e remova tickers favoritos com sincronização automática ao Firebase.
- **Visualização Personalizada:** Gráficos interativos de barra e pizza que analisam seus ativos favoritos.
- **Autenticação de Usuário:** Login seguro com Firebase Authentication, garantindo acesso restrito a funcionalidades específicas.
- **Notificações e Atualizações:** Interface amigável para alertas e novidades do mercado.

## 🛠️ Tecnologias

As principais tecnologias utilizadas no projeto incluem:

- **Vue.js:** Framework progressivo para construção de interfaces de usuário.
- **Vuetify:** Biblioteca de componentes baseada no Material Design.
- **Pinia:** Gerenciamento de estado moderno e simples para Vue.js.
- **Firebase:** Backend como serviço, incluindo Authentication, Realtime Database e Analytics.
- **Chart.js:** Biblioteca para visualização de dados interativa e responsiva.

## 🔒 Autenticação de Usuário
Acesse funcionalidades exclusivas ao fazer login na plataforma. Usuários autenticados podem gerenciar favoritos e visualizar análises personalizadas.

<p align="center"> <img src=".github/Preview_Login.png" width="100%" /> </p>


## 🛠️ Instalação

### Requisitos

- Node.js (versão 14 ou superior)
- npm (versão 6 ou superior)

### Passos

1. **Clone o repositório:**

```sh
git clone https://github.com/RodrigoRodrigues-Dev/coin-pulse.git

cd coin-pulse
```

2. **Instale as dependências:**

```sh
npm install
```
<br>

# Variáveis de Ambiente

Para rodar localmente, copie o arquivo `.env.example` para `.env`

| Nome           | Descrição                              | Onde obter                        |
| -------------- | -------------------------------------- | --------------------------------- |
| `VITE_COIN_API_KEY`      | Chave de API utilizada para autenticar requisições à API da CoinAPI, que fornece dados de mercado de criptomoedas.  | https://docs.coinapi.io/ |
| `VITE_COINCAP_API_KEY`   | Chave de API usada para autenticação nas requisições à API da CoinCap, que também oferece dados de preços e mercado de criptoativos. | https://pro.coincap.io/api-docs |
<br>

## 📃 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
<br>
## ☎️ Contato
Desenvolvido por [Rodrigo Rodrigues](https://github.com/RodrigoRodrigues-Dev). Entre em contato por 📧 [rodrigorodriguesdevcontato@gmail.com](mailto:rodrigorodriguesdevcontato@gmail.com)
