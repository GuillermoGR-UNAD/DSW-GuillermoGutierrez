<h2><strong>Estructura b&aacute;sica de html5 (etiquetas, atributos y valores)</strong></h2>
<p>Objetivo: Comprender todo lo relacionado con HTML5&nbsp;(HyperText Markup Language, versi&oacute;n 5) identificar sus nuevas caracteristicas al momento de trabajar con este lenguaje.<strong><br /> </strong></p>
<p><a href="#mozTocId909723">La sintaxis y la estructura en html5</a></p>
<ol>
<li><a href="#mozTocId516347">LA SINTAXIS HTML5</a>
<ol>
<li><a href="#mozTocId132515">&nbsp;EL DOCTYPE</a></li>
<li><a href="#mozTocId748542">&nbsp;EL DOCUMENTO HTML</a></li>
<li><a href="#mozTocId282611">&nbsp;LA CODIFICACI&Oacute;N DE LOS CARACTERES</a></li>
<li><a href="#mozTocId620698">LOS SCRIPTS</a></li>
<li><a href="#mozTocId995255">LOS ESTILOS CSS</a></li>
<li><a href="#mozTocId987846">&nbsp;LA SINTAXIS DE LOS ELEMENTOS</a></li>
</ol>
</li>
<li><a href="#mozTocId89118">LOS ELEMENTOS DE LA ESTRUCTURA EN HTML5</a>
<ol>
<li><a href="#mozTocId67942">&nbsp;EL ELEMENTO &lt;HEADER&gt;</a></li>
<li><a href="#mozTocId854190">&nbsp;EL ELEMENTO &lt;FOOTER&gt;</a></li>
<li><a href="#mozTocId343482">&nbsp;EL ELEMENTO &lt;NAV&gt;</a></li>
<li><a href="#mozTocId560756">&nbsp;EL ELEMENTO &lt;SECTION&gt;</a></li>
<li><a href="#mozTocId602817">&nbsp;EL ELEMENTO &lt;ARTICLE&gt;</a></li>
<li><a href="#mozTocId978440">&nbsp;EL ELEMENTO &lt;ASIDE&gt;</a></li>
<li><a href="#mozTocId272578">&nbsp;LOS &lt;DIV&gt;</a></li>
</ol>
</li>
<li><a href="#mozTocId929114">EJEMPLOS DE ESTRUCTURA EN HTML5</a>
<ol>
<li><a href="#mozTocId991449">ESTRUCTURA SIMPLE</a></li>
<li><a href="#mozTocId743946">ESTRUCTURA UN POCO MAS COMPLEJA</a></li>
<li><a href="#mozTocId177073">ESTRUCTURA DE UN ART&Iacute;CULO</a></li>
</ol>
</li>
</ol>
<p>&nbsp;</p>
<p><strong>Objetivo especifico 1: Entender la diferencia entre HTML4 y HTML5</strong></p>
<p>&nbsp;</p>
<p><iframe src="//www.youtube.com/embed/WSFT4OQF_mA" width="560" height="314" allowfullscreen="allowfullscreen"></iframe></p>
<p>&nbsp;</p>
<h3 style="font-style: inherit;">La sintaxis y la estructura en html5</h3>
<p style="font-style: inherit; font-weight: inherit;">En HTML4, el elemento principal para estructurar las p&aacute;ginas web era la famosa caja &lt;div&gt;. Con el elemento &lt;div&gt; es posible crear zonas de visualizaci&oacute;n de forma rectangular que identificamos con un id o una clase para luego darle formato con CSS.</p>
<p style="font-style: inherit; font-weight: inherit;">El problema de los &lt;div&gt;, y esta es una de las cosas que pretende solucionar HTML5, es que se distinguen unos de otros gracias a ese id o esa clase.</p>
<p style="font-style: inherit; font-weight: inherit;">Por esta raz&oacute;n, las cajas &lt;div&gt; no son sem&aacute;nticas. Muchas veces no nos aportan ning&uacute;n dato sobre su contenido.</p>
<p style="font-style: inherit; font-weight: inherit;">En HTML5 se ha hecho especial hincapi&eacute; tambi&eacute;n en la simplicidad.</p>
<p style="font-style: inherit; font-weight: inherit;">HTML5 establece una serie de nuevos elementos y atributos que reflejan el uso t&iacute;pico de los sitios web modernos. Algunos de ellos son t&eacute;cnicamente similares a las etiquetas&nbsp;&lt;div&gt;&nbsp;y&nbsp;&lt;span&gt;, pero tienen un significado sem&aacute;ntico, como por ejemplo&nbsp;&lt;nav&gt;&nbsp;(bloque de navegaci&oacute;n del sitio web) y&nbsp;&lt;footer&gt;.</p>
<p>Este es un ejemplo de un emulador programado sobre HTML5: https://supermarioemulator.com/mario.php</p>
<p><br /> <br /><strong>Objetivo especifico 2: Cuales son las etiquetas, atributos y valores.</strong></p>
<p>LA SINTAXIS HTML5</p>
<p style="font-weight: 400;"><strong><strong style="font-style: inherit;">En HTML5 destaca sobretodo la simplicidad y la permisividad.</strong></strong></p>
<h3 style="font-weight: 500;">&nbsp;EL DOCTYPE</h3>
<p style="font-weight: 400;">La primera l&iacute;nea de un documento corresponde a la DTD (Document Type Declaration) o declaraci&oacute;n de tipo de documento y sirve para indicar que versi&oacute;n de lenguaje HTML se ha usado al escribirlo.</p>
<p style="font-weight: 400;">En HTML5 esta declaraci&oacute;n no puede ser m&aacute;s sencilla:</p>
<p>&lt;!DOCTYPE html&gt;</p>
<p style="font-weight: 400;">Y ya esta, no necesitas nada m&aacute;s.</p>
<h3 style="font-weight: 500;">&nbsp;EL DOCUMENTO HTML</h3>
<p style="font-weight: 400;">En una p&aacute;gina web, el elemento &lt;html&gt; indica el inicio del contenido HTML. En HTML s&oacute;lo necesitas indicar el lenguaje de la pagina. Por ejemplo:</p>
<p>&lt;html lang=es&gt;</p>
<h3 style="font-weight: 500;">&nbsp;LA CODIFICACI&Oacute;N DE LOS CARACTERES</h3>
<p style="font-weight: 400;">Es frecuente indicar qu&eacute; codificaci&oacute;n de caracteres se ha usado en una p&aacute;gina web. Con HTML5 se simplifica con lo indispensable para que los navegadores puedan gestionarla correctamente.</p>
<p>&lt;meta charset="UTF-8" /&gt;</p>
<h3 style="font-weight: 500;">LOS SCRIPTS</h3>
<p style="font-weight: 400;">Una vez m&aacute;s, se ha simplificado la declaraci&oacute;n de scripts de la siguiente forma:</p>
<p>&lt;script src="unscript.js"&gt;&lt;/script&gt;</p>
<p style="font-weight: 400;">Esto es debido a que ahora se da por sentado que los scripts estan escritos en Javascript.</p>
<h3 style="font-weight: 500;">LOS ESTILOS CSS</h3>
<p style="font-weight: 400;">Seguimos con la simplificaci&oacute;n. Ahora para la declaraci&oacute;n de los estilos te bastar&aacute; con:</p>
<p>&lt;link href="tuhojadeestilos.css" rel="stylesheet" /&gt;</p>
<h3 style="font-weight: 500;">&nbsp;LA SINTAXIS DE LOS ELEMENTOS</h3>
<p style="font-weight: 400;">Las comillas en HTML5 pasan a ser facultativas para los valores de los atributos. Puedes escribirlos con comillas dobles, comillas simples o sin ellas. Estas tres sintaxis ser&iacute;an correctas:</p>
<p>&lt;div class="tuestilo"&gt; &lt;div class='tuestilo'&gt; &lt;div class=tuestilo&gt;</p>
<p style="font-weight: 400;">En los elementos HTML con una sola etiqueta de apertura como por ejemplo br o img ya no es necesario indicar el cierre del elemento usando /. Por ejemplo:</p>
<p>&lt;img src="tuimagen.jpg"&gt;</p>
<p style="font-weight: 400;">HTML5 permite el uso de may&uacute;sculas y min&uacute;sculas indistintamente en la sintaxis de los elementos y atributos. De este modo, podr&iacute;as declarar un script as&iacute;:</p>
<p>&lt;SCRIPT src="TuJavascript.js"&gt;&lt;/script&gt;</p>
<p style="font-weight: 400;">Como puedes ver, HTML5 es muy permisivo a la hora de escribir c&oacute;digo. Ofrece una gran flexibilidad y muy pocas restricciones. Lo cual, tambi&eacute;n puede ser un problema. Imagina un c&oacute;digo en el que hayan trabajado dos o tres desarrolladores, con la permisividad de HTML5, si cada uno ha escrito el c&oacute;digo a su manera, lo que tu veas al final, puede resultar un aut&eacute;ntico caos.</p>
<p style="font-weight: 400;">Es por eso, que te recomiendo seguir unas&nbsp;sencillas pautas que te har&aacute;n la vida mas f&aacute;cil a ti y a otros desarrolladores que trabajen sobre tu c&oacute;digo.</p>
<ul style="font-weight: 400;">
<li style="font-style: inherit; font-weight: inherit;">Usa s&oacute;lo min&uacute;sculas</li>
<li style="font-style: inherit; font-weight: inherit;">Usa siempre comillas para los valores de los atributos</li>
<li style="font-style: inherit; font-weight: inherit;">Cierra con / las etiquetas con una sola etiqueta de apertura.</li>
<li style="font-style: inherit; font-weight: inherit;">Cierra los elementos aunque su etiqueta sea facultativa.</li>
<li style="font-style: inherit; font-weight: inherit;">Utiliza el sangrado para que el c&oacute;digo sea mas legible.</li>
</ul>
<h2 style="font-weight: 500;">LOS ELEMENTOS DE LA ESTRUCTURA EN HTML5</h2>
<p style="font-weight: 400;"><strong><strong style="font-style: inherit;">Con la llegada de HTML5 han llegado nuevos elementos de estructura para mejorar la sem&aacute;ntica.</strong></strong>&nbsp;Esto es, dotar a estos elementos de un significado.</p>
<p style="font-weight: 400;">&iquest;Cu&aacute;les son esos elementos? No te preocupes, los vemos a continuaci&oacute;n.</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;HEADER&gt;</h3>
<p style="font-weight: 400;">El nuevo elemento&nbsp;<strong><strong style="font-style: inherit;">&lt;header&gt;</strong></strong>&nbsp;se utiliza para definir una zona de visualizaci&oacute;n para las cabeceras. Puedes definir cabeceras tanto a nivel de p&aacute;gina como de una zona determinada (un art&iacute;culo, un men&uacute;, etc&hellip;)</p>
<p style="font-weight: 400;">De este modo, puedes tener una cabecera para toda la p&aacute;gina que ser&iacute;a la t&iacute;pica cabecera en la parte alta de la pagina con un logo, un menu, etc&hellip; O puedes tener una cabecera para una zona determinada como por ejemplo un art&iacute;culo, en el que la cabecera podr&iacute;a incluir el t&iacute;tulo, el autor y la fecha.</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;FOOTER&gt;</h3>
<p style="font-weight: 400;">Funciona de un modo muy parecido al &lt;header&gt;. Del mismo modo, podr&aacute;s determinar un&nbsp;<strong><strong style="font-style: inherit;">&lt;footer&gt;</strong></strong>&nbsp;para toda la p&aacute;gina o utilizarlo en diferentes secciones de la web como por ejemplo un sidebar o un art&iacute;culo.</p>
<p style="font-weight: 400;">A nivel de p&aacute;gina ser&iacute;a la t&iacute;pica zona en la parte baja de la web, donde se suelen incluir datos de contacto, enlaces, etc&hellip; A nivel de zonas, y siguiendo con el ejemplo anterior, en el&nbsp;<strong><strong style="font-style: inherit;">&lt;footer&gt;</strong></strong>&nbsp;de un art&iacute;culo podr&iacute;as incluir por ejemplo la categor&iacute;a a la que pertenece ese art&iacute;culo o el autor si no lo has puesto en el &lt;header&gt;</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;NAV&gt;</h3>
<p style="font-weight: 400;">Como su nombre ya deja intuir, el elemento&nbsp;<strong><strong style="font-style: inherit;">&lt;nav&gt;</strong></strong>&nbsp;sirve para definir una zona de navegaci&oacute;n con v&iacute;nculos. Lo que vendr&iacute;a a ser un men&uacute; de toda la vida. Este elemento esta pensado para la navegaci&oacute;n principal de la web y para definir v&iacute;nculos entre las diferentes p&aacute;ginas.</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;SECTION&gt;</h3>
<p style="font-weight: 400;">La funci&oacute;n del elemento&nbsp;<strong><strong style="font-style: inherit;">&lt;section&gt;</strong></strong>&nbsp;es agrupar elementos relacionados entre s&iacute;. De este modo, podr&aacute;s por ejemplo, agrupar dentro de un mismo elemento un contenido con su t&iacute;tulo y su pie de p&aacute;gina.</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;ARTICLE&gt;</h3>
<p style="font-weight: 400;">El&nbsp;<strong><strong style="font-style: inherit;">&lt;article&gt;</strong></strong>&nbsp;sirve para definir&nbsp;un contenido aut&oacute;nomo e independiente, que pueda ser usado en otra parte de la web sin que por ello pierda su significado.</p>
<p style="font-weight: 400;">A modo de ejemplo, usar&iacute;as el elemento &lt;art&iacute;cle&gt; para un art&iacute;culo de un blog, como este que estas leyendo ahora mismo, o una noticia de un peri&oacute;dico o incluso un comentario de un blog.</p>
<h3 style="font-weight: 500;">&nbsp;EL ELEMENTO &lt;ASIDE&gt;</h3>
<p style="font-weight: 400;">La funci&oacute;n del elemento&nbsp;<strong><strong style="font-style: inherit;">&lt;aside&gt;</strong></strong>&nbsp;es mostrar un contenido relacionado al contenido al cu&aacute;l esta vinculado. Puede tratarse de sidebars, zonas de widgets, complementos sobre un art&iacute;culo, etc&hellip;</p>
<p style="font-weight: 400;">En la mayor&iacute;a de los casos un&nbsp;<strong><strong style="font-style: inherit;">&lt;aside&gt;</strong></strong>&nbsp;se ubicar&aacute; en un lateral del contenido con el que est&aacute;n relacionados. Pero recuerda que no tiene porque ser as&iacute;. La finalidad de las nuevas etiquetas es dotar de sem&aacute;ntica al contenido de una web, para la ubicaci&oacute;n de los elementos debes usar CSS.</p>
<h3 style="font-weight: 500;">&nbsp;LOS &lt;DIV&gt;</h3>
<p style="font-weight: 400;">Por supuesto, la llegada de HTML5, no significa que tengas que erradicar las cajas &lt;div&gt;. Todav&iacute;a puedes usarlas y&nbsp;<strong><strong style="font-style: inherit;">aun tienen su utilidad</strong></strong>.</p>
<p style="font-weight: 400;">Si deseas ampliar esta informaci&oacute;n o profundizar mas en alguno de los elementos, te recomiendo que leas la recomendaci&oacute;n del 28 de Octubre de 2014 de la&nbsp;<span style="font-style: inherit; font-weight: inherit;">W3C</span>.</p>
<p style="font-weight: 400;">Y por supuesto, no te preocupes si todo esto te ha sonado un poco a chino.</p>
<p style="font-weight: 400;">Ahora veremos algunos ejemplos de utilizaci&oacute;n de estos elementos estructurales para que entiendas un poco mejor el uso de cada uno de ellos.</p>
<p>Objetivo especifico 3: Estructura en HTML5.</p>
<h2 style="font-weight: 500;">EJEMPLOS DE ESTRUCTURA EN HTML5</h2>
<h3 style="font-weight: 500;">ESTRUCTURA SIMPLE</h3>
<p><img src="https://webdesdecero.com/wp-content/uploads/2015/03/estructura-simple-html5-904x1024.png" alt="SIMPLE" width="904" height="1024" /></p>
<p style="font-weight: 400;">En este primer ejemplo tendr&iacute;as un &lt;header&gt; con los elementos del encabezado de la pagina como el logo o el eslogan de la web.</p>
<p style="font-weight: 400;">En la secci&oacute;n &lt;nav&gt; tendr&iacute;as el men&uacute; con los v&iacute;nculos que permiten navegar por la web.</p>
<p style="font-weight: 400;">Dos secciones &lt;article&gt; que evidentemente ser&aacute;n los art&iacute;culos de la web.</p>
<p style="font-weight: 400;">Y terminas con un &lt;footer&gt; que podr&iacute;a contener por ejemplo el copyright y los avisos legales con sus v&iacute;nculos.</p>
<h3 style="font-weight: 500;">ESTRUCTURA UN POCO MAS COMPLEJA</h3>
<p><img src="https://webdesdecero.com/wp-content/uploads/2015/03/estructura-compleja-HTML5-904x1024.png" alt="COMPLEJA" width="904" height="1024" /></p>
<p style="font-weight: 400;">En este segundo ejemplo, tendr&iacute;amos&nbsp;un &lt;header&gt; como en el anterior.</p>
<p style="font-weight: 400;">Debajo del &lt;header&gt;&nbsp;aparece el primer cambio. Un &lt;nav&gt; horizontal que contendr&iacute;a el men&uacute; principal de la web con los v&iacute;nculos a las diferentes p&aacute;ginas.</p>
<p style="font-weight: 400;">A la izquierda, otro elemento &lt;nav&gt; con el men&uacute; secundario que contendr&iacute;a v&iacute;nculos directamente relacionados con el contenido de esa p&aacute;gina.</p>
<p style="font-weight: 400;">El contenido principal, en el centro, con dos elementos &lt;section&gt; para distinguir dos tipos de contenido diferentes. Cada &lt;section&gt; contiene un &lt;header&gt; para el t&iacute;tulo, un &lt;article&gt; con el contenido textual y un &lt;footer&gt; con la informaci&oacute;n de la categor&iacute;a y el autor, por ejemplo.</p>
<p style="font-weight: 400;">A la derecha, un elemento &lt;aside&gt; que podr&iacute;a mostrar otra informaci&oacute;n relacionada con el contenido como por ejemplo contenidos relacionados.</p>
<p style="font-weight: 400;">Termina la estructura nuevamente con un &lt;footer&gt; t&iacute;pico donde podr&iacute;a aparecer, como no, el copyright y los avisos legales con sus v&iacute;nculos.</p>
<h2 style="font-weight: 500;">ESTRUCTURA DE UN ART&Iacute;CULO</h2>
<p><img src="https://webdesdecero.com/wp-content/uploads/2015/03/estructura-art%C3%ADculo-HTML5-1024x997.png" alt="ARTICULO" width="1024" height="997" /></p>
<p style="font-weight: 400;">En este &uacute;ltimo ejemplo, vemos una posible estructura para un art&iacute;culo.</p>
<p style="font-weight: 400;">El art&iacute;culo, evidentemente, lo definiremos con un elemento &lt;article&gt;.</p>
<p style="font-weight: 400;">Ya dentro del art&iacute;culo, primero encontrar&iacute;amos un &lt;header&gt; con un &lt;h1&gt; para el t&iacute;tulo del art&iacute;culo.</p>
<p style="font-weight: 400;">Seguimos con el contenido textual, dentro de dos elementos &lt;p&gt;.</p>
<p style="font-weight: 400;">Y terminamos con un elemento &lt;footer&gt; donde podr&iacute;amos definir la categor&iacute;a, la fecha y el autor.</p>
<p style="font-weight: 400;">Como has podido ver, los nuevos elementos de HTML5, adem&aacute;s de hacer el c&oacute;digo m&aacute;s sem&aacute;ntico, tambi&eacute;n te permitir&aacute;n entender mucho mejor un c&oacute;digo ya escrito con menos esfuerzo. Ordenar y clasificar mucho mejor el contenido de tu web tambi&eacute;n ser&aacute; mucho m&aacute;s sencillo.</p>
<p>&nbsp;</p>
<p>Bibliografia:</p>
<p>La sintaxis y la estructura en html5, tomado de: https://webdesdecero.com/tutorial-html5-la-sintaxis-y-la-estructura/</p>
<p>HTML5 Wikipedia, tomado de : https://es.wikipedia.org/wiki/HTML5</p>
<p>Elaboro: Guillermo Gutierrez Riascos - UNAD sep-2020</p>
<p>&nbsp;</p>
