# editore.js bold plugin [![npm version](https://badge.fury.io/js/editore-bold-plugin.svg)](http://badge.fury.io/js/editore-bold-plugin)

#### install
Available on npm: `npm install editore-bold-plugin` or [directly download](https://github.com/evandroeisinger/editore-bold-plugin.js/raw/master/src/editore-bold-plugin.js)

#### basic usage
It's easy to use! Load [editor.js](https://github.com/evandroeisinger/editore.js) into your application, instantiate it and register the new **edition** plugin.

```javascript
var editor = new Editor(document.getElementById('editor')),
    BoldPlugin;

// Global
BoldPlugin = window.EditoreBoldPlugin;
// CommonJS
BoldPlugin = require('editore-bold-plugin');

// then register!
editor.registerEditionComponent(BoldPlugin);
```
---
#### support
- chrome: ?
- firefox: ?
- safari: ?
- internet explore: ?


---
#### contribute
Everyone can contribute! Finding bugs, creating issues, improving editor it self or creating components.
Every contribution will be welcomed! :santa: 

**Fork it** -> **Branch it** -> **Test it** -> **Push it** -> **Pull Request it** :gem:  
