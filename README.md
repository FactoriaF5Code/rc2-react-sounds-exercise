# React Sounds

Además de la construcción de una página a partir de componentes, React cuenta con sus propios mecanismos para manejar eventos del navegador.

## Setup

Para comenzar, una vez abierto este proyecto con Visual Studio Code, utiliza el terminal para crear la plantilla de proyecto de React dentro de la misma carpeta, haciendo:

```
npm init vite
```

Selecciona `React` y `Javascript`

## Objetivo

Implementa una página con 6 botones correspondientes a las 6 notas de una guitarra (afinación estándar). Cada botón debe tener asociada la nota correspondiente ( [E] [A] [D] [G] [B] [E] ) de modo que cuando lo pulsemos suene esa nota.


## Restricciones

- Debes usar React para este proyecto (ver Setup)
- No se permite usar el DOM (`document`) ni el navegador (`window`). Todo debe de hacerse usando React y su DOM virtual


## Consejos

- Investiga cómo se usa `onClick` con los componentes de React
- la clase `Audio` en Javascript permite reproducir sonidos
- Existen librerías que puedes añadir a tu proyecto para reproducir sonidos desde componentes React. Es decisión tuya usarlas o no. Lee [este artículo](https://theshubhagrwl.medium.com/you-might-not-need-a-sound-library-for-react-a265870dabda) para más información