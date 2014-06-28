# &lt;glitch-img&gt;

A polymer component to glitch your \<img\>, wrapper for [glitch-canvas](https://github.com/snorpey/glitch-canvas).

## Demo

[Check it live!](http://www.kunjinkao.org/glitch-img)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install glitch-img --save
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/glitch-img/dist/glitch-img.html">
    ```

3. Start using it!

    ```html
    <glitch-img src="beautifulpic.jpg"></glitch-img>
    ```

## Options

Attribute     | Options     | Default          | Description
---           | ---         | ---              | ---
`src`         | *string*    | `bar`            | your \<img\> src
`seed`        | *int*       | `random integer` | integer between 0 and 99
`quality`     | *int*       | `random integer` | integer between 0 and 99
`amount`      | *int*       | `random integer` | integer between 0 and 99
`iterations`  | *int*       | `random integer` | integer

check out this awesome [jpg-glitch](http://snorpey.github.io/jpg-glitch/)
experiment to get a better understanding of the values

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
