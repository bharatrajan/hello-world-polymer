# &lt;hello-world&gt;

> A Web Component example using [Polymer](http://www.polymer-project.org/).
>
> Looking for a boilerplate? Check [polymer-boilerplate](https://github.com/webcomponents/polymer-boilerplate).

## Demo

[Check it live!](http://webcomponents.github.io/hello-world-polymer)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install hello-world-polymer --save
```

Or [download as ZIP](https://github.com/webcomponents/hello-world-polymer/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/hello-world-polymer/dist/hello-world.html">
    ```

3. Start using it!

    ```html
    <hello-world></hello-world>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

3. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

4. To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

5. To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/hello-world-polymer/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
