## Introdução ao Wordpress e o Elementor

---

## Quem sou eu?

+++

### Gustavo T. B. Tamanaka
#### Engenheiro Mecânico - UFSCar
#### Desenvolvedor Web e Embarcados.

---

## Wordpress

+++

O Wordpress é uma tecnologia desenvolvida para a criação de blogs que rapidamente se tornou popular para os mais diversos tipos de sites. Atualmente, acredita-se que 80% dos sites disponíveis na internet são feitos nessa plataforma.
---
## Themes

+++

Os *themes* em suma alteram diretamente a aparência do site, como a cor da barra, como a informação vai ser diagramada, quais as paletas de cores, etc.

---

## Elementor

+++
```
    <div style="padding:8px 16px; box-shadow: 0 0 10px 1px lightgrey; background-color:white;color:black">
        <h2>Titulo do card</h2>
        <p>Esse é o conteudo do card</p> 
    </div>
```
+++

Resultado:
<div style="padding:8px 16px; box-shadow: 0 0 10px 1px lightgrey;background-color:white;color:black">
    <h2>Titulo do card</h2>
    <p>Esse é o conteudo do card</p> 
</div>

---
## Theme Compatível
+++

**Busca** Which Themes Work Best with Elementor?

+++
### Customizando o tema

```
.navbar{
	background-color:#2c2c2c
}
.navbar.navbar-transparent{
	background-color:#2c2c2c;
		background-color:rgba(0,0,0,0);
}
.navbar button.navbar-toggle, .navbar, .navbar-default .navbar-nav>.active>a {
	color:white
}
.navbar-default .navbar-nav>.active>a, .navbar-default .navbar-nav>.active>a:hover, .navbar-default .navbar-nav>.active>a:focus{
	background-color:rgba(0,0,0,0.2);
}
```