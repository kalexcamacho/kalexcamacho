# Bar Chart Component

Next, you can find the correct way to set up the component and graph a bar chart based on three principal props, data, style options, and the data key.

## Data

In this prop is necessary to pass all data in an array, with an object for every single data of each bar, then, save it in a constant with the name "data", next you have an example:

```js
const data = [
  {
    name: 'Page A',
    uv: 4000,
    pv: 2400,
    amt: 2400,
  },
  {
    name: 'Page B',
    uv: 3000,
    pv: 1398,
    amt: 2210,
  },
  {
    name: 'Page C',
    uv: 2000,
    pv: 9800,
    amt: 2290,
  },
  {
    name: 'Page D',
    uv: 2780,
    pv: 3908,
    amt: 2000,
  },
  {
    name: 'Page E',
    uv: 1890,
    pv: 4800,
    amt: 2181,
  },
  {
    name: 'Page F',
    uv: 2390,
    pv: 3800,
    amt: 2500,
  },
  {
    name: 'Page G',
    uv: 3490,
    pv: 4300,
    amt: 2100,
  }
];
```

## Options

This prop is where you can modify all the style options of the chart, next is a list with all the items and their descriptions:

### Item Descriptions

The configuration object can contain the following properties:

- `title`: A string with the name of the graph.
- `aspect`: A number that represents the scale relation between the width and height of the graph.
- `width`: A number that represents the width of the graph.
- `height`: A number that represents the height of the graph.
- `margin`: A key-value object with numbers that represents the margin of each side.
- `showVerticalGridLine`: A boolean value that determines the visualization of the vertical line on the chart grid.
- `showHorizontalGridLine`: A boolean value that determines the visualization of the horizontal line on the chart grid.
- `hideYAxis`: A boolean value that determines the concealment of the vertical axis of the chart.
- `YAxisTickCount`: A number that represents the times that the vertical axis has a mark.
- `showTooltipShadow`: A boolean value that determines the visualization of the bar tooltip shadow on the chart.
- `barTooltipShadowColor`: A string that contains the color wished for the bar tooltip shadow in hex code.
- `showLegend`: A boolean value that determines the visualization of the bar legend on the chart.
- `legendIconType`: A string that contains the name of the form of the legend icon.
- `legendAlign`: A string that contains the name of the horizontal position of the legend on the chart.
- `legendVerticalAlign`: A string that contains the name of the vertical position of the legend on the chart.
- `legendColor`: A string that contains the color wished for the legend of the chart in hex code.
- `barLabelPosition`: A string that contains the name of the vertical position of the bar label on the chart.
- `barColors`: An object with arrays that contains the color palettes for the bars.

All these items must be stored in a const with the name "options". Next, you have an example with the structure and the default values to the chart:

```js
const options ={
  title: "Bar Chart",
  aspect: 2,
  width: 500,
  height: 300,
  margin: {
    top: 5,
    right: 30,
    left: 20,
    bottom: 5,
  },
  showVerticalGridLine: false,
  showHorizontalGridLine: true,
  hideYAxis: false,
  YAxisTickCount: 4,
  showTooltipShadow: true,
  barTooltipShadowColor: "#FFFFFF",
  showLegend: true,
  legendIconType: "circle",
  legendAlign: "center",
  legendVerticalAlign: "bottom",
  legendColor: "#000000",
  barLabelPosition: "top",
  barColors : {
    darkColors: [
      "rgb(74, 144, 226)",
      "rgb(74, 74, 74)",
      "rgb(155, 155, 155)",
      "rgb(255, 75, 75)",
      "rgb(87, 166, 2)",
      "rgb(245, 166, 35)",
      "rgb(27, 48, 68)",
      "rgb(248, 248, 248)",
      "rgb(255, 255, 255)"
    ],
    ligthColors: [
      "rgba(74, 144, 226, 0.5)",
      "rgba(74, 74, 74, 0.5)",
      "rgba(155, 155, 155, 0.5)",
      "rgba(255, 75, 75, 0.5)",
      "rgba(87, 166, 2, 0.5)",
      "rgba(245, 166, 35, 0.5)",
      "rgba(27, 48, 68, 0.5)",
      "rgba(248, 248, 248, 0.5)",
      "rgba(255, 255, 255, 0.5)"
    ]
  }
}
```
## Datakey

This prop is where you can specify what data you will use in each axis of the chart, based on the info that you passed in the first prop (data), next you have an example:

```js
const graphDataKey ={
  xAxis: "name",
  bar: "uv"
}
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
