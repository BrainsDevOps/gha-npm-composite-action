# gha-npm-composite-action
Este repositorio forma parte de los ejemplos del curso de udemy [Domina Github Actions](https://www.udemy.com/course/domina-github-actions/?referralCode=CBFBAF72C38BE758CFE1)

Esta acción de github es un ejemplo de acción personalizada compuesta.

La acción toma como parámetro la versión de node que se quiere usar para lanzar "npm ci" y "npm test"

## Inputs
* version-node: La versión de node.js sobre la que se quieren lanzar los comandos.
    * Valor por defecto: 18
