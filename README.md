<div align="center">
  <h1>Plugins</h1>
  <p>The repository that hosts all the plugins for Aplós.</p>
</div>

> [!NOTE]
> Check the list of available plugins on [the website](https://aplos.dev/plugins/).

## Adding a Plugin

To add a plugin, simply add the stylesheet to the `plugins` folder of this repository and import it in the `index.scss` file.

An example of an plugin:

```scss
.plugin-name {
    h1 {
        color: red;
    }
}
```

It's important to add the plugin's styles inside the class name of the plugin, to avoid conflicts with other plugins and the main stylesheet of the theme.

## Packaging

The content of this repository is automatically packaged and published to NPM through GitHub Packages. The package is published under the `@aplosdev/plugins` scope. The package is installed by the theme's main package.
