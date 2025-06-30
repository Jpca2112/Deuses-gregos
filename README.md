# Deuses-gregos
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deuses Gregos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Principais Deuses</h1>

  <div class="video-container">
    <iframe width="560" height="315" src="<iframe width="560" height="315" src="<iframe width="560" height="315" src="https://www.youtube.com/embed/IaINCqS-dik?si=DYaRXotYeSND5r_K" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>" 
            </iframe>
  </div>

  <p class="descricao-video">Explicação da mitologia grega!
  </p>

  <div class="galeria">
    <div class="zeus">
      <img src="" alt="zeus">
      <p>o deus dos deuses</p>
    </div>
    <div class="hades">
      <img src="" alt="hades">
      <p>o deus do submundo</p>
    </div>
    <div class="poseidon">
      <img src="" alt="poseidon">
      <p>o deus dos mares</p>
    </div>
    <div class="hera">
      <img src="" alt="hera">
      <p>a deusa das mulheres e do casamento</p>
    </div>
    <div class="apolo">
      <img src="" alt="apolo">
      <p>o deus do sol</p>
    </div>
  </div>
</body>
</html>
CSS
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
body {
  background-color: green;
  color: purple;
  font-family: Arial, sans-serif;
  margin: 20px;
}

h1 {
  text-align: center;
}

.video-container {
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

.descricao-video {
  text-align: center;
  font-size: 18px;
  margin-bottom: 40px;
}

.galeria {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  position: absolute;
  bottom: 20px;
  left: 20px;
}

.item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.item img {
  margin-right: 10px;
  border: 2px solid purple;
}
