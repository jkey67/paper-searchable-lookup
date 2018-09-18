# Paper searchable lookup

Paper searchable lookup web component for Polymer 2 apps

## Installation

The element can be installed using bower
```
    bower install jkey67/paper-searchable-lookup
```
If you want to save it in bower.json file, remember to add flag `--save`
```
    bower install jkey67/paper-searchable-lookup --save
```

## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-searchable-lookup.html">
    <style>
        paper-searchable-lookup {
          height: 200px;
	        overflow:hidden;
        }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-searchable-lookup lookup-values='["List item 1", "List item 2", "List item 3", "List item 4", "List item 5"]'></paper-searchable-lookup>
<paper-searchable-lookup lookup-values='[{ "id": 1, "name": "Name1" }, { "id": 2, "name": "Name2" }, { "id": 3, "name": "Name3" }, { "id": 4, "name": "Name4" }, { "id": 5, "name": "Name5" }]' value-field="id" display-field="name" limit-to-lookup-values></paper-searchable-lookup>

```

## License

This project is licensed under the terms of the MIT license.