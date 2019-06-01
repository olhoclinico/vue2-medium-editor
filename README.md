# Vue2 Medium Editor

Vue2 component for Medium Editor wrapper with https://github.com/yabwe/medium-editor
But all plugins are re-writing in Vue.js

[Demo](https://olhoclinico.github.io/vue2-medium-editor/)

ps. a demo work for all features except upload photo because i doesn't deploy a serverside.

## Features
- Medium like editor
- Image uploader and description
    - Image width configable width for normal / expand / full screen sizing
- Embed Gist

## Usage

### Installation

```
yarn add https://github.com/olhoclinico/vue2-medium-editor
```

### Usage

add to global component

```
import Vue from 'vue'
import MediumEditor from 'vue2-content-editor'

Vue.component('medium-editor', MediumEditor)
```

usage

```
<medium-editor :content='content' :options='options' />

<script>
export default {
    data() {
        return {
            content: "",
            options: {
            }
        }
    }
}
</script>
```

Don't forget to include css file in your project
```
medium-editor/dist/css/medium-editor.css
vue2-medium-editor/src/themes/default.css
```



## Configuration



## License

MIT: https://github.com/olhoclinico/vue2-medium-editor/blob/master/LICENSE
