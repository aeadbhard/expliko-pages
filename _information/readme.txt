Para que se respete el markdown del contenido dentro de una div:
================================================================
Poner lo siguiente antes de la div:

{::options parse_block_html="true" /}
<div>**Contenido**</div>

o también:

<div markdown="1">**Contenido**</div> 