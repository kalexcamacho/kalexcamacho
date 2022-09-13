# MUI Button Widget

Next, you can find the correct way to set up the widget with three main props, and, other style option props.

## Abailable Props

The properties that can be in the button widget are the following:

- `propType`: A string with the type of button required (i.e "button" | "submit" | "reset").
- `propFunctionHandler`: A function with the wanted actions after clicking the button.
- `propText`: A string with the text that you want to display on the button.
- `propVariant`: A string with the required button variant (i.e "text" | "contained" | "outlined").
- `propColor`: A string with the name of the desired color palette for the button (i.e "inherit" | "primary" | "secondary" | "success" | "error" | "info" | "warning")
- `propSize`: A string with the desired size reference for the button (i.e "small" | "medium" | "large").
- `propDisabled`: A boolean value that determines the availability of the button.

All these items must be passed like a props of the widget:

```js
let clickButtonHandler = (e: any) => {
  e.preventDefault();
  console.log("Hi, here clickButtonHandler")
};
<ButtonWidget
  propType="button"
  propFunctionHandler={clickButtonHandler}
  propText="Button"
  propVariant="contained"
  propColor="primary"
  propSize="medium"
  propDisabled={false}
/>;
```


### Hola 😄

Me llamo Kevin Camacho. Me gustan los videojuegoos y el ultimate freesbe, soy desarrollador web BackEnd enfocado principalmente en crear soluciones tecnológicas que sean realmente útiles, asegurando el correcto funcionamiento de las aplicaciones. 

<img src="https://user-images.githubusercontent.com/97989061/164719491-d844a091-c763-4dc8-b220-f7256989adeb.png" align="right" width=450px></img>

- 💻 Manejo tecnologías como: NodeJs, Express, APIs (REST), SQL, MySQL, Sequelize, Git, GitHub, Javascript, HTML5, CSS y React.
- 🤓 Estoy trabajando en el desarrollo de principio a fin de un proyecto de e-commerce que permite al usuario registrado y conectado agregar, editar, eliminar y listar productos. Además, se incluyó la posibilidad de crear, editar y eliminar usuarios, utilizando nodejs, express, proceso de CRUD, bases de datos y dashboard en React.
- 🧠 Estoy aprendiendo constantemente nuevas tecnologías para desarrollar mis proyectos.
- 🎮 Nickname: kalexcamacho 
- ⚡ Fun fact: Me gusta aprender y probar cosas nuevas, actualmente estoy incursionando en el mundo del streamming de videojuegos :) 

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=kalexcamacho&hide=stars&show_icons=true&theme=tokyonight&border_radius=10px&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
