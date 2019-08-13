# JS JSX Snippets

## Supported languages (file extensions)
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)

## Usage
After install this snippets add this inside your settings

```js
"editor.snippetSuggestions": "top",
```

## Snippets

## Import and export
| Trigger  | Content |
| -------: | ------- |
| `imp`   | `import name from 'module';` |
| `imn`  | `import 'module';` |
| `imd`  | `import {  } from 'module';` |
| `rqr`  | `require('package');` |
| `mde`  | `module.exports = { };` |
| `exp`  | `export default moduleName;` |

## Import package
| Trigger  | Content |
| -------: | ------- |
| `imr`   | `import React from 'react';` |
| `imrc`   | `import React, { Component } from 'react';` |
| `imrpc`   | `import React, { PureComponent } from 'react';` |
| `ipt`   | `import PropTypes from 'prop-types';` |
| `redux`   | `import { connect } from 'react-redux';` |
| `imrs`   | `import React, { useState } from 'react';` |
| `imre`   | `import React, { useEffect } from 'react';` |

## Basic methods
| Trigger  | Content |
| -------: | ------- |
| `comment`   | Comment Block |
| `clg`   | `console.log()` |

## React components
| Trigger  | Content |
| -------: | ------- |
| `rcc`   | class component skeleton |
| `rccp`  | class component skeleton with prop types after the class |
| `rcjc`  | class component skeleton without import and default export lines |
| `rpc`   | class pure component skeleton with prop types after the class |
| `rfc`   | stateless component skeleton |
| `rfcp`  | stateless component with prop types skeleton |
| `rpt`   | empty propTypes declaration |
| `rdp`   | empty defaultProps declaration |
| `con`   | class default constructor with props|
| `conc`  | class default constructor with props and context |
| `est`   | empty state object |
| `cdm`   | `componentDidMount method` |
| `scu`   | `shouldComponentUpdate method` |
| `cdup`  | `componentDidUpdate method` |
| `cwun`  | `componentWillUnmount method` |
| `gsbu`   | `getSnapshotBeforeUpdate method` |
| `gdsfp`   | `static getDerivedStateFromProps method` |
| `cdc`   | `componentDidCatch method` |
| `ren`   | `render method` |
| `sst`   | `this.setState with object as parameter` |
| `ssf`   | `this.setState with function as parameter` |
| `props` | `this.props` |
| `state` | `this.state` |
| `bnd`   | `binds the this of method inside the constructor` |
| `useState`   | useState block |
| `useEffect`   | useEffect block |
| `useContext`   | useContext block |

## Jest
| Trigger  | Content |
| -------: | ------- |
| `describe`   | describe Block |
| `test`   | test Block |
| `tit`   | it Block |


## PropTypes
| Trigger  | Content |
| -------: | ------- |
| `pta`   | `PropTypes.array,` |
| `ptar`  | `PropTypes.array.isRequired,` |
| `ptb`   | `PropTypes.bool,` |
| `ptbr`  | `PropTypes.bool.isRequired,` |
| `ptf`   | `PropTypes.func,` |
| `ptfr`  | `PropTypes.func.isRequired,` |
| `ptn`   | `PropTypes.number,` |
| `ptnr`  | `PropTypes.number.isRequired,` |
| `pto`   | `PropTypes.object.,` |
| `ptor`  | `PropTypes.object.isRequired,` |
| `pts`   | `PropTypes.string,` |
| `ptsr`  | `PropTypes.string.isRequired,` |
| `ptnd`  | `PropTypes.node,` |
| `ptndr` | `PropTypes.node.isRequired,` |
| `ptel`  | `PropTypes.element,` |
| `ptelr` | `PropTypes.element.isRequired,` |
| `pti`   | `PropTypes.instanceOf(ClassName),` |
| `ptir`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `pte`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `pter`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `ptet`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `ptetr` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `ptao`  | `PropTypes.arrayOf(PropTypes.number),` |
| `ptaor` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `ptoo`  | `PropTypes.objectOf(PropTypes.number),` |
| `ptoor` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `ptsh`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `ptshr` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |
