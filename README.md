# Tools

## Ruff

For Python projects, [Ruff](https://docs.astral.sh/ruff/) should be used with the corresponding ruff.toml file in this repository

## Biome

For Javascript and Typescript projects [Biome](https://biomejs.dev/) should be used with the corresponding biome.json file in this directory

# General styling

## lower camel case

Where possible use lower camel case for variable names, such as:

    variableName = 10

## Type definitions

Furthemore where possible use type definitions, this helps make your code a lot more readable:

    variableName: int = 10
    def main(argument: int) -> int:
        return (variableName + 10)
    main(variableName)

## 4 spaces

Use four spaces to indent code (you can set your code editor to make tabs 4 spaces)
