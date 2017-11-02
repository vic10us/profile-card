[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/vic10us/profile-icon)

# \<profile-card\>

Google like profile card dialog using vic10us/card-icon.

<!--
```
<custom-element-demo height="400px">
  <template>
    <link rel="import" href="profile-card.html">
    <profile-card popout-direction="left" profile='{"name":"Neo Doe","email":"ndoe@blueorredpill.com"}'>
        <span slot="disclaimer">This account is managed by ACME Toys identity.</span>
        <a href="#">More info</a>
    </profile-card>
  </template>
</custom-element-demo>
```
-->
```html
<profile-card popout-direction="left" profile='{"name":"Neo Doe","email":"ndoe@blueorredpill.com"}'>
    <span slot="disclaimer">This account is managed by ACME Toys identity.</span>
    <a href="#">More info</a>
</profile-card>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
