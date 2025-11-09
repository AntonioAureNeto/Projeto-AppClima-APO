# AppClima

Aplicativo Android para consulta de previsão do tempo com mapa e scanner QR Code.

## Funcionalidades

- **Previsão do Tempo**: Consulta condições climáticas atuais
- **Mapa**: Visualização geográfica com Google Maps
- **Scanner QR Code**: Alteração de cidade através de códigos QR
- **Interface por abas**: Navegação simples entre as funcionalidades

## Tecnologias

- **Linguagem**: Java/Kotlin
- **Min SDK**: Android 7.0 (API 24)
- **Retrofit** - Consumo da API de clima
- **Google Maps** - Integração com mapas
- **ZXing** - Scanner de QR Code
- **Material Design** - Interface moderna

## API

Utiliza a **API HG Brasil** para dados meteorológicos com os parâmetros:
- `key`: Chave da API
- `city_name`: Nome da cidade

## Como usar

1. Abra o projeto no Android Studio
2. Configure sua chave da API HG Brasil
3. Configure a chave do Google Maps no AndroidManifest.xml
4. Execute o aplicativo

## Estrutura

- **MainActivity**: Tela principal com abas
- **WeatherFragment**: Exibe previsão do tempo
- **MapFragment**: Mostra localização no mapa
- **SplashActivity**: Tela inicial do app
- **AboutActivity**: Informações sobre o aplicativo
