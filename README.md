<div align="center">
  <h1>Boosts</h1>
  <p>The repository that hosts all the boosts for Aplós.</p>
</div>

> [!NOTE]
> Check the list of available boosts on [the website](https://aplos.dev/boosts/).

## Adding a Boost

To add a boost, simply add the stylesheet to the `boosts` folder of this repository and import it in the `index.scss` file.

An example of an boost:

```scss
.boost-name {
    h1 {
        color: red;
    }
}
```

It's important to add the boost's styles inside the class name of the boost, to avoid conflicts with other boosts and the main stylesheet of the theme.
