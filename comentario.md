### Comentarios Generales

Rebe, lo primero que quiero hacer es felicitarte por un excelente trabajo. Tu portfolio quedó muy bello. Me encanta ver cómo adaptaste el modelo de Ada a tu propia personalidad, la elección de colores, el agregado de cositas como background-image para hacerlo más impactante y atractivo. 

Una de las cosas a las que más importancia le damos es el reponsive, y ese aspecto en particular quedó perfecto. No puedo encontrar una sola resolución en donde tu web no se vea fantástica. Esto nunca es casualidad: revela que pusiste mucho trabajo aquí, atención al detalle, empeño y mucho esfuerzo invertido. Espero que te sientas muy orgullosa por haber hecho esta web: yo sin dudas me siento así al verla. 

Con respecto a tu código HTML, está muy prolijo, ordenado y fácil de seguir, con algunos detalles que te dejo comentados en el archivo. Tu CSS tiene algunas desprolijidades. No es poco habitual ver cosas asi:

```css 
.texto-presentacion { text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
   

}
```

Es importante que no pongas espacios de mas, y que dejes los saltos de linea correspondientes asi tu CSS se ve ordenado. Te aseguro que simplifica mucho la lectura. Tomá en cuenta que podés bajarte linters a VSCode para formatear el CSS con un clic: "CSS Formatter" es el que yo uso y recomiendo, pero hay muchísimos. 

En ambos, HTML y CSS hay algunos detalles que te comento en los archivos para que tengas en cuenta. Se nota que te esforzaste por hacer tu código reutilizable, algo que sin dudas ayuda a lo bien que se ve visualmente (por ejemplo, por la simetría entre los dos tipos de tarjetas) y a lo claro que es el código.

Veo que no usaste las etiquetas h1, h2, h3 en el orden correcto. Eso puede afectar a tu web. Toda pagina web debe tener una (y solo una) etiqueta h1 que identifique al texto más importante. Los siguientes titulos deben organizarse por jerarquia: los h2, los h3 (aqui no hay problema en que haya varios). No deberiamos escribir h4 si no hay antes h1, h2, h3. En el caso de este portfolio: tu nombre deberia ser un h1, y los titulos "Mis proyectos" y "Mis conocimientos" deberian ser h2. 

Sí te comento que noto algo de repetición entre los estilos para tablet y mobile. Recordá que si escribimos por ejemplo
```
@media (max-width: 900px) {
```

esos estilos se aplicaran tanto en tablet como en mobile. En tu caso, yo recomendaria tres media queries:
- una con max-width 900px, para todos los estilos comunes a tablet y mobile, 
- una de max-width 900px y min-width 600px para tablet, 
- una de min-width 600px para celular. 

También toma en cuenta que, por convención y buenas prácticas, las media queries se ordenan de mayor a menor. 

Tengo que mencionar lo bien ordenado de tu proyecto en github, y lo prolija que fuiste commit a commit agregando los cambios de a poco y describiendolos bien en tus mensajes. (Aunque veo que aprendiste por las malas que nunca hay que decir "esta es la versión final" cuando de código se trata... siempre aparece algo nuevo!!). Tu README tambien es excelente. 

Dejo algunos comentarios a lo largo de tu código de todo lo que me parezca necesario mejorar. 

Es mi trabajo ser detallista y quisquillosa a la hora de corregir, como verás en los comentarios de los distintos archivos. No es mi intención comentarte cada detalle porque sí: tu trabajo es fantástico. Mi tarea es comentarte todo lo que vea para que sea más fantástico aún. 


### Nota final: 9

Nota desagregada: 
✅ Estructura correcta de documento HTML.
✅ Respeta la consigna.
✅ Respeta el diseño dado.
✅ Responsive funciona correctamente.
✔️ Código bien indentado ---> con observaciones
✅ Comentarios que permiten mejorar la legibilidad del código.
✔️ Uso correcto de etiquetas semánticas --> con observaciones
✔️ Buenos nombres de clases ---> con observaciones
✅ Reutilización de estilos.
✔️ Código CSS ordenado ---> con observaciones
✅ Commits con mensajes adecuados.

