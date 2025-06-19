# Biome Config

This is a common repository for our biome configuration.


## Usage

Install the package at the top level of the project.

```sh
pnpm add @angellist/biome-config
````

Add a `biome.json` file to the root of the project and configure it to extend the shared one:
```json
{
  "extends": ["@angellist/biome-config"],
}
```
