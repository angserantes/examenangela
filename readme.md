#examen Ángela

Abrimos Laragon para generar la estructura del repositorio y lo vinculamos a GitHUb mediante gitinit
Damos forma a los html en la zona de metadatos
Vinculamos css, foundawesome
Declaramos  <header-component></header-component> y <footer-component></footer-component> y enlazamos sus respectivos js en la parte final del body

Al declarar lo indicado arriba nos permite trabajar en js los diferentes estilos del header y el footer y definir así un estilo personalizado

registramos el elemento con customElements.define('header-component', Header) en el header.js

Colocamos los h1 y los p en los htmls