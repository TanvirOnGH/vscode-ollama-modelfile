# About

Experimental syntax highlighting VSCode extension for [Ollama](https://github.com/jmorganca/ollama) [Modelfile](https://github.com/jmorganca/ollama/blob/main/docs/modelfile.md).

## What is Ollama Modelfile?

A Modelfile is the blueprint to create and share models with Ollama. Read more about it [here](https://github.com/jmorganca/ollama/blob/main/docs/modelfile.md) and look at some examples [here](https://github.com/jmorganca/ollama/tree/main/examples).

## Note

- Ollama's Modelfile syntax is in development.
- Instructions can be in any order.
- The `Modelfile` is not case sensitive.

## Todo

- Different color for modelfile specific template variables: `{{  }}`:
  - Different color for template variables: `{{- if .<variable> }}`, `{{ .System }}`, `{{ .Prompt }}` and `{{- end }}`.
  - Matching colors for template variables: `{{- if .<variable> }}`/~~`{{ if and .<variable1> .<variable2> }}`~~ and `{{- end }}`.
  -  ~~Different color for single condition: `{{- if .<variable> }}`.~~
  - ~~Different color for dual conditions: `{{ if and .<variable1> .<variable2> }}`.~~
  - Different color for parameter arguments: `<parameter>` and `<parametervalue>`.
  - Different color for integers and floats in `<parametervalue>`.