### CIRCUMFLEX
>Proyecto destinado a la venta de ropa urbana online.

----
### Herramientas utlizadas
- HTML 
- CSS
- SASS 
- SEO basico

####HTML code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="CIRCUMFLEX was created in September 2022, in a small bedroom in Rosario, Argentina by a boy wanting to create something different. After working for a company that sold clothes without emotion that did not convey my way of being, I began to create this movement that transmits my values and what I am passionate about, rap and street underground.">
    <meta name="author" content="Etienne Valle">
    <meta name="copyright" content="CIRCUMFLEX">
    <meta property="og: title" content="CIRCUMFLEX">
    <meta property="og: description" content="Marca de ropa urbana CIRCUMFLEX">
    <meta property="og: image" content="">
    <meta property="og: url" content="">
    <meta property="og: locate" content="es_ES">
    <title>CIRCUMFLEX | "We are here to stay"</title>
    <link rel="stylesheet" href="./css/estilos.css">
    <link rel="shortcut icon" href="./assets/img/pasamontañas-circumflex.jpg" type="image/x-icon">
</head>
```

####CSS code

```css
.hover {
  width: 0%;
  height: 100%;
  background-color: rgba(56, 53, 53, 0.568);
  position: absolute;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  transition: 0.4s all;
}
.hover p {
  color: aliceblue;
  text-shadow: 1px 1px 1px black;
  font-size: 2.5em;
  text-transform: uppercase;
}

.grid-carrusel {
  display: flex;
  margin: 60px;
  gap: 20px;
}
.grid-carrusel img {
  width: 100%;
  height: 100%;
}
```
####SCSS code

```scss
.grid-shop {
	display: grid;
	grid-template-columns: auto auto auto auto;
	background-color: #FFF9F4;
	justify-content: center;
	align-items: center;
	margin: 20px;
	gap: 20px;
	img {
		width: 100%;
		height: 100%;
		max-width: 90%;
	}
}
.categoria-shop {
	text-align: center;
	overflow: hidden;
	position: relative;
	margin: 1.5%;
	img {
		object-fit: cover;
	}
	p {
		margin-top: 5%;
		font-size: small;
		font-weight: 800;
	}
}
```

![](https://img.freepik.com/foto-gratis/codificacion-programas-informaticos-pantalla_53876-138060.jpg?w=740&t=st=1674127054~exp=1674127654~hmac=9bf7ff8fbf27c467c25c628cc7af10bb82c2a4e1544634964b0baec9018463d8(https://pandao.github.io/editor.md/examples/images/4.jpg )
