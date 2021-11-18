# Contador de caracteres

Web component para fazer a geração de nickname personalziado para jogos.

Instalação compativel com qualquer tipo de site, wordpress, cms próprio, joomla, drupal e etc.

## Instalação

Para fazer a instalação do componente siga os seguintes passos:

1 - Solicite a permissão de acesso no componente através do e-mail: contato@diegoaugusto.com

2 - Após a liberação copie e cole o script abaixo onde o componente será renderizado.

Obs: para instalação Wordpress você pode adicionar o código abaixo na opção Html Personalizado.

```html
<script
  type="text/javascript"
  defer
  src="https://cdn.jsdelivr.net/gh/vulgodizz/web-components/v1/nickname-generator/lazy.min.js"
></script>

<nickname-generator
  btn-copy-background="#A765EB"
  btn-copy-font="#FFFFFF"
  content-color="#0B0A0D"
  content-font-color="#FFFFFF"
  main-container-background="transparent"
></nickname-generator>
```
Obs: as cores do componente poderão ser personalizadas de acordo com o parâmetro passado. Por defualt ele assume as cores acima.

-   **content-color**: cor de fundo do container onde os nicknames são gerados.

-   **content-font-color**: cor da fonte dos nicknames.

-   **main-container-background**: cor de fundo do componente todo.

-   **btn-copy-background**: cor de fundo do botão de copiar.

-   **btn-copy-font**: cor da fonte do botão de copiar.

3 - Pronto, o componente já está instalado e funcionando.
