# Clima Hoje

Este projeto é uma aplicação web que permite buscar informações sobre o clima em qualquer localização. Utiliza a API do OpenWeatherMap para obter dados meteorológicos e exibe os resultados de forma clara e intuitiva.

## Funcionalidades

- **Busca por Localização:** Permite ao usuário buscar informações meteorológicas de qualquer local.
- **Exibição de Dados Climáticos:** Mostra a temperatura atual, velocidade do vento e um ícone representando o clima.
- **Avisos ao Usuário:** Exibe mensagens de aviso, como "Carregando..." e "Não encontramos esta localização."

## Tecnologias Utilizadas

- **HTML:** Estrutura da página.
- **CSS:** Estilização da aplicação (não incluído aqui, mas presumido).
- **JavaScript:** Lógica para buscar dados da API e atualizar a interface do usuário.
- **API do OpenWeatherMap:** Fonte de dados climáticos.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `index.html`: Contém a estrutura HTML da aplicação.
- `style.css`: Contém os estilos CSS para o relógio analógico e digital.
- `script.js`: Contém o script JavaScript que lida com a lógica de busca e exibição dos dados.

## Como Utilizar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seuusuario/clima-hoje.git
   cd clima-hoje
   ```

2. **Abra o arquivo `index.html` no seu navegador:**

   ```bash
   open index.html
   ```

3. **Busque por uma localização:**
   - Insira o nome de uma cidade ou local no campo de busca.
   - Clique no botão "Buscar" para ver as informações climáticas.


## Resumo das Tecnologias e Ferramentas Utilizadas no Código JavaScript

### Tecnologias

1. **JavaScript:** Utilizado para manipulação da DOM e requisições assíncronas.
2. **API do OpenWeatherMap:** Fonte de dados climáticos em tempo real.

### Ferramentas e Funcionalidades

1. **Manipulação de Eventos:**
2. **Manipulação da DOM:**
3. **Requisições Assíncronas:**
4. **Tratamento de Respostas da API:**
5. **Funções**

### Fluxo de Execução
1. **Submissão do Formulário:**
2. **Requisição para a API:**
3. **Atualização da Interface:**

### Exemplo de URL para a API

```javascript
let url = `https://api.openweathermap.org/data/2.5/weather?q=${encodeURI(input)}&appid=7835b0412e62d0ac87f0d3b1cc4e8a03&units=metric&lang=pt_br`;
```


## Autora

Criado por [GabzFonseca](https://www.linkedin.com/in/gabz-fonseca).

---

Este README fornece todas as informações necessárias para entender, instalar e utilizar o projeto "Clima Hoje". Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou um pull request no repositório.