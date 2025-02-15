# CommonMethods

## [fabric](fabric.html).CommonMethods Source:

* [fabric.js](fabric.js.html), [line 528](fabric.js.html#line528)

### Methods

#### [(static)\_setOptions(optionsopt)](#._setOptions)

Sets object's properties from options

##### Parameters:
|Name|Type|Attributes|Description| |
|`options`|Object|optional|Options object|

Source:

* [fabric.js](fabric.js.html), [line 537](fabric.js.html#line537)

#### [(static)get(property)&rarr; {\*}](#.get)

Basic getter

##### Parameters:
|Name|Type|Description| |
|`property`|String|Property name|

Source:

* [fabric.js](fabric.js.html), [line 618](fabric.js.html#line618)

##### Returns:

value of a property

Type

\*

#### [(static)set(key, value)&rarr; {[fabric.Object](fabric.Object.html)}](#.set)

Sets property to a given value. When changing position/dimension -related properties (left, top, scale, angle, etc.) \`set\` does not update position of object's borders/controls. If you need to update those, call \`setCoords()\`.

##### Parameters:
|Name|Type|Description| |
|`key`|String | Object|Property name or object (if object, iterate over the object properties)|
|`value`|Object | function|Property value (if function, the value is passed into it and its return value is used as a new one)|

Source:

* [fabric.js](fabric.js.html), [line 585](fabric.js.html#line585)

##### Returns:

thisArg

Type

[fabric.Object](fabric.Object.html)

#### [(static)toggle(property)&rarr; {[fabric.Object](fabric.Object.html)}](#.toggle)

Toggles specified property from \`true\` to \`false\` or from \`false\` to \`true\`

##### Parameters:
|Name|Type|Description| |
|`property`|String|Property to toggle|

Source:

* [fabric.js](fabric.js.html), [line 605](fabric.js.html#line605)

##### Returns:

thisArg

Type

[fabric.Object](fabric.Object.html)
labelHide inherited properties and method from the page/label  
Documentation generated by [JSDoc 3.6.7](https://github.com/jsdoc3/jsdoc) on Sun Feb 06 2022 00:57:17 GMT+0100 (Central European Standard Time)