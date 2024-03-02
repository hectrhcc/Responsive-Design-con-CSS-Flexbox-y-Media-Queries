# Frontend Mentor - Solución del componente de código QR

Esta es una solución para el [desafío del componente de código QR en Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Los desafíos de Frontend Mentor te ayudan a mejorar tus habilidades de codificación mediante la construcción de proyectos realistas.


## Tabla de contenidos

- [Visión General](#visión-general)
  - [Pantallazo](#pantallazo)
  - [Hipervinculos](#hipervinculos)
- [Mi proceso](#mi-proceso)
  - [Construido con](#construido-con)
  - [Lo que aprendí](#lo-que-aprendi)
  - [Desarrollo continuo](#desarrollo-continuo)
  - [Recursos útiles](#recursos-útiles)
- [Autor](#autor)
- [Reconocimientos](#reconocimientos)


## Visión General

### Pantallazo

![](screenshot.png)


### Hipervinculos

- URL solucion: [https://github.com/hectrhcc/Responsive-Design-con-CSS-Flexbox-y-Media-Queries](https://github.com/hectrhcc/Responsive-Design-con-CSS-Flexbox-y-Media-Queries)
- URL del sitio en vivo: [https://responsive-design-con-css-flexbox-y-media-queries.vercel.app](https://responsive-design-con-css-flexbox-y-media-queries.vercel.app)

## Mi proceso

### Construido con

- HTML5 semántico
- CSS para estilizar la apariencia 
- Flexbox para el diseño de la disposición de los elementos en el contenedor
- Unidades de medida como porcentajes, pixeles y em para definir tamaños y posiciones de elementos
- Media queries para el responsive design 


### Lo que Aprendi

Poner limites en el tamaño de los componentes, ayuda a bastante para evitar la desconfiguración con el redimensionado.

```css
.contenedor { 
  min-width: 200px; 
  max-width: 300px; 
}
```

Usar unidades de medida apropiadas es importante para un diseño coherente y adaptable.  porcentajes y em para definir tamaños y posiciones de elementos. 

```css
.contenedor { 
 transform: translateY(50%); 
}
```

Usar media querys con un rango en vez de las media query tradicionales, me refiero a usar con operadores como en los lenguajes de programación. 

```css
@media (width> 375px) {
  /*regla de css que corresponda*/
}

 @media ( width >= 1440px) {
 /*regla de css que corresponda*/
}
```

### Desarrollo continuo

Me gustarias seguir practicando realizar páginas con responsive-desings ya que encontré varias técnicas útiles que deseo seguir aprendiendo,perfeccionando y refinando.


### Recursos útiles

- [Media Query nivel 4](https://filisantillan.com/bits/media-query-ranges/) - esto me ayudo a hacer media query usando operadores. Queda mas claro de esa forma y prefiero utilizarlas asi.


## Autor

- Website - [hector](https://www.encontruction.com)
- Frontend Mentor - [@hectrhcc](https://www.frontendmentor.io/profile/hectrhcc)


## Reconocimientos

Trabaje solo pero corregí algunos errores con ChatGPT 3.5 sobre todo con el tema de los valores de transformación basados en unidades relativas. 
