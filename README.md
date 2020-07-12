## JavaScript Snippet Pack for Visual Studio Code

Download this extension from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items/akamud.vscode-javascript-snippet-pack)

## Sponsors

[![](https://alt-images.codestream.com/codestream_logo_ali_javascriptsnippet.png)](https://sponsorlink.codestream.com/?utm_source=vscmarket&utm_campaign=ali_javascriptsnippet&utm_medium=banner "Try CodeStream")  
Request and perform code reviews from inside your IDE. Review any code, even if it's a work-in-progress that hasn't been committed yet, and use jump-to-definition, your favorite keybindings, and other IDE tools.  
[Try it free](https://sponsorlink.codestream.com/?utm_source=vscmarket&utm_campaign=ali_javascriptsnippet&utm_medium=banner "Try CodeStream")

## Usage

-----------------------------------------

A snippet pack to make you more productive working with JavaScript.
Based on [Visual Studio extension](https://github.com/madskristensen/JavaScriptSnippetPack) by [Mads Kristensen](https://github.com/madskristensen), which is based on [Atom snippets](https://atom.io/packages/javascript-snippets).

This extension ships a bunch of useful code snippets for the JavaScript and TypeScript editors.

Here's the full list of all the snippets:

## Console

### [cd] console.dir

```javascript
console.dir(${1});
```

### [ce] console.error

```javascript
console.error(${1});
```

### [ci] console.info

```javascript
console.info(${1});
```

### [cl] console.log

```javascript
console.log(${1});
```

### [cw] console.warn

```javascript
console.warn(${1});
```

### [de] debugger

```javascript
debugger;
```

## DOM

### [ae] addEventListener

```javascript
${1:document}.addEventListener('${2:load}', function(e) {
	${3:// body}
});
```

### [ac] appendChild

```javascript
${1:document}.appendChild(${2:elem});
```

### [rc] removeChild

```javascript
${1:document}.removeChild(${2:elem});
```

### [cel] createElement

```javascript
${1:document}.createElement(${2:elem});
```

### [cdf] createDocumentFragment

```javascript
${1:document}.createDocumentFragment();
```

### [ca] classList.add

```javascript
${1:document}.classList.add('${2:class}');
```

### [ct] classList.toggle

```javascript
${1:document}.classList.toggle('${2:class}');
```

### [cr] classList.remove

```javascript
${1:document}.classList.remove('${2:class}');
```

### [gi] getElementById

```javascript
${1:document}.getElementById('${2:id}');
```

### [gc] getElementsByClassName

```javascript
${1:document}.getElementsByClassName('${2:class}');
```

### [gt] getElementsByTagName

```javascript
${1:document}.getElementsByTagName('${2:tag}');
```

### [ga] getAttribute

```javascript
${1:document}.getAttribute('${2:attr}');
```

### [sa] setAttribute

```javascript
${1:document}.setAttribute('${2:attr}', ${3:value});
```

### [ra] removeAttribute

```javascript
${1:document}.removeAttribute('${2:attr}');
```

### [ih] innerHTML

```javascript
${1:document}.innerHTML = '${2:elem}';
```

### [tc] textContent

```javascript
${1:document}.textContent = '${2:content}';
```

### [qs] querySelector

```javascript
${1:document}.querySelector('${2:selector}');
```

### [qsa] querySelectorAll

```javascript
${1:document}.querySelectorAll('${2:selector}');
```

## Loop

### [fe] forEach

```javascript
${1:array}.forEach(function(item) {
	${2:// body}
});
```

## Function

### [fn] function

```javascript
function ${1:methodName} (${2:arguments}) {
	${3:// body}
}
```

### [afn] anonymous function

```javascript
function(${1:arguments}) {
	${2:// body}
}
```

### [pr] prototype

```javascript
${1:object}.prototype.${2:method} = function(${3:arguments}) {
	${4:// body}
}
```

### [iife] immediately-invoked function expression

```javascript
(function(${1:window}, ${2:document}) {
	${3:// body}
})(${1:window}, ${2:document});
```

### [call] function call

```javascript
${1:method}.call(${2:context}, ${3:arguments})
```

### [apply] function apply

```javascript
${1:method}.apply(${2:context}, [${3:arguments}])
```

### [ofn] function as a property of an object

```javascript
${1:functionName}: function(${2:arguments}) {
	${3:// body}
}
```

## JSON

### [jp] JSON.parse

```javascript
JSON.parse(${1:obj});
```

### [js] JSON.stringify

```javascript
JSON.stringify(${1:obj});
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	${0:// body}
}, ${1:1000});
```

### [st] setTimeout

```javascript
setTimeout(function() {
	${0:// body}
}, ${1:1000});
```

## Misc

### [us] use strict

```javascript
'use strict';
```

### [al] alert

```javascript
alert('${1:msg}');
```

### [co] confirm

```javascript
confirm('${1:msg}');
```

### [pm] prompt

```javascript
prompt('${1:msg}');
```

## License
[MIT License](https://raw.githubusercontent.com/akamud/vscode-javascript-snippet-pack/master/LICENSE)
