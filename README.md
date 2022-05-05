# Instagram Clone

Este repositório é um fork do projeto desenvolvido pela [SpruceGabriela](https://github.com/SpruceGabriela) em sua aula sobre flexbox ministrada para a [Dio](https://www.dio.me/) onde foi feito a tela de login do Instagram de forma totalmente responsiva.

## O que eu fiz
* Implementei a tela inicial da versão web do Instagram e para isso eu fiz:
  * Incluí um ícone na aba do navegador através do HTML.
    ```html
      <link rel="icon" href="./assets/img/ig-icon.jpg">
    ```
  * Utilizei JQuery para criar um slider na seção dos stories

   ![image](https://user-images.githubusercontent.com/83733139/166851706-e83b70b7-879b-4b59-8669-df57b2d31fc4.png)

  
  * Estruturei a página com HTML semântico.
    ```html
      <header class="header">
            <img src="./assets/img/instagram-logo.png" class="ig-logo" alt="instagram logo">
            <input type="text" class="search-input" placeholder="Pesquisar">
            <nav class="navbar">...
    ```
  * Organizei os elementos da página com flexbox.
  * Usei media queries para ajustar a página a diferentes tamanhos de telas.
    ```css
      @media screen and (max-width: 600px) {
    .header{
        width: 100vw;
        display:flex;
        flex-shrink: 0;
    }
    ```

### Resultado
![image](https://user-images.githubusercontent.com/83733139/166850472-46a6d623-2165-4337-b3a3-2cfb7e69f749.png)

### Link



## Agradecimentos
- Gabriela Pinheiro
- Dio
