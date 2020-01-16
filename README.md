# VS Code ES7 React/Redux/JS snippets

This extension provides you JavaScript and React/Redux snippets in ES7 with Babel plugin features for [VS Code](https://code.visualstudio.com/).

To install the extension: [es7-react-js-snippets on marketplace](https://marketplace.visualstudio.com/items?itemName=woodreamz.es7-react-js-snippets).

GitHub link: [vscode-react-snippets](https://github.com/woodreamz/vscode-react-snippets).

This is a fork of [vscode-react-snippets original](https://github.com/dsznajder/vscode-es7-javascript-react-snippets).

## Search command

You can search through snippets with `ES7 snippet search` command which can be run with `CMD + Shift + P` or just use `CMD + Shift + R` keybinding.

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)

## Snippets info

Every space inside `{ }` and `( )` means that this is pushed into next line :)
`$` represent each step after `tab`.

## Basic Methods

|  Prefix | Method                                              |
| ------: | --------------------------------------------------- |
|  `imp→` | `import moduleName from 'module'`                   |
|  `imn→` | `import 'module'`                                   |
|  `imd→` | `import { destructuredModule } from 'module'`       |
|  `ime→` | `import * as alias from 'module'`                   |
|  `ima→` | `import { originalName as aliasName} from 'module'` |
| `imsc→` | `import styled from 'styled-components'`            |
|  `exp→` | `export default moduleName`                         |
|  `exd→` | `export { destructuredModule } from 'module'`       |
|  `exa→` | `export { originalName as aliasName} from 'module'` |
|  `enf→` | `export const functionName = (params) => { }`       |
|  `edf→` | `export default (params) => { }`                    |
|  `met→` | `methodName = (params) => { }`                      |
|  `fre→` | `arrayName.forEach(element => { }`                  |
|  `fof→` | `for(let itemName of objectName { }`                |
|  `fin→` | `for(let itemName in objectName { }`                |
| `anfn→` | `(params) => { }`                                   |
|  `nfn→` | `const functionName = (params) => { }`              |
|  `dob→` | `const {propName} = objectToDescruct`               |
|  `dar→` | `const [propName] = arrayToDescruct`                |
|  `sti→` | `setInterval(() => { }, intervalTime`               |
|  `sto→` | `setTimeout(() => { }, delayTime`                   |
| `prom→` | `return new Promise((resolve, reject) => { }`       |
| `cmmb→` | `comment block`                                     |
|   `cp→` | `const { } = this.props`                            |
|   `cs→` | `const { } = this.state`                            |

## ESLint

| Prefix | Method                 |
| -----: | ---------------------- |
| `eld→` | `/* eslint-disable */` |

## React

|      Prefix | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
|      `imr→` | `import React from 'react'`                                                         |
|     `imrd→` | `import ReactDOM from 'react-dom'`                                                  |
|     `imrc→` | `import React, { Component } from 'react'`                                          |
|    `imrcp→` | `import React, { Component } from 'react' & import PropTypes from 'prop-types'`     |
|    `imrpc→` | `import React, { PureComponent } from 'react'`                                      |
|   `imrpcp→` | `import React, { PureComponent } from 'react' & import PropTypes from 'prop-types'` |
|     `imrm→` | `import React, { memo } from 'react'`                                               |
|    `imrmp→` | `import React, { memo } from 'react' & import PropTypes from 'prop-types'`          |
|     `impt→` | `import PropTypes from 'prop-types'`                                                |
|     `imrr→` | `import { BrowserRouter as Router, Route, Link } from 'react-router-dom'`           |
|    `redux→` | `import { connect } from 'react-redux'`                                             |
|   `rconst→` | `constructor(props) with this.state`                                                |
|    `rconc→` | `constructor(props, context) with this.state`                                       |
|      `est→` | `this.state = { }`                                                                  |
|      `cwm→` | `componentWillMount = () => { }` DEPRECATED!!!                                      |
|      `cdm→` | `componentDidMount = () => { }`                                                     |
|      `cwr→` | `componentWillReceiveProps = (nextProps) => { }` DEPRECATED!!!                      |
|      `scu→` | `shouldComponentUpdate = (nextProps, nextState) => { }`                             |
|     `cwup→` | `componentWillUpdate = (nextProps, nextState) => { }` DEPRECATED!!!                 |
|     `cdup→` | `componentDidUpdate = (prevProps, prevState) => { }`                                |
|     `cwun→` | `componentWillUnmount = () => { }`                                                  |
|    `gdsfp→` | `static getDerivedStateFromProps(nextProps, prevState) { }`                         |
|     `gsbu→` | `getSnapshotBeforeUpdate = (prevProps, prevState) => { }`                           |
|      `ren→` | `render() { return( ) }`                                                            |
|      `sst→` | `this.setState({ })`                                                                |
|      `ssf→` | `this.setState((state, props) => return { })`                                       |
|    `props→` | `this.props.propName`                                                               |
|    `state→` | `this.state.stateName`                                                              |
| `rcontext→` | `const ${1:contextName} = React.createContext()`                                    |
|     `cref→` | `this.${1:refName}Ref = React.createRef()`                                          |
|     `fref→` | `const ref = React.createRef()`                                                     |
|      `bnd→` | `this.methodName = this.methodName.bind(this)`                                      |

## React Hooks

- All hooks from [official docs](https://reactjs.org/docs/hooks-reference.html) are added with hook name prefix.

|                 Prefix | Method                                                              |
| ---------------------: | ------------------------------------------------------------------- |
|            `useState→` | `const [state, setState] = useState(initialState);`                 |
|           `useEffect→` | ``                                                                  |
|          `useContext→` | `const context = useContext(contextValue)`                          |
|          `useReducer→` | `const [state, dispatch] = useReducer(reducer, initialState, init)` |
|         `useCallback→` | ``                                                                  |
|             `useMemo→` | ``                                                                  |
|              `useRef→` | ``                                                                  |
| `useImperativeHandle→` | ``                                                                  |
|       `useDebugValue→` | `useDebugValue(value)`                                              |
|     `useLayoutEffect→` | ``                                                                  |

## Redux

|           Prefix | Method                       |
| ---------------: | ---------------------------- |
|      `rxaction→` | `redux action template`      |
|       `rxconst→` | `export const $1 = '$1'`     |
|     `rxreducer→` | `redux reducer template`     |
|      `rxselect→` | `redux selector template`    |
| `rxuseSelector→` | `redux useSelector template` |
| `rxuseDispatch→` | `redux useDispatch template` |
|    `rxuseStore→` | `redux useStore template`    |

## PropTypes

|    Prefix | Method                                   |
| --------: | ---------------------------------------- |
|    `pta→` | `PropTypes.shape([])`                    |
|   `ptar→` | `PropTypes.shape([]).isRequired`         |
|    `ptb→` | `PropTypes.bool`                         |
|   `ptbr→` | `PropTypes.bool.isRequired`              |
|    `ptf→` | `PropTypes.func`                         |
|   `ptfr→` | `PropTypes.func.isRequired`              |
|    `ptn→` | `PropTypes.number`                       |
|   `ptnr→` | `PropTypes.number.isRequired`            |
|    `pto→` | `PropTypes.shape({})`                    |
|   `ptor→` | `PropTypes.shape({}).isRequired`         |
|    `pts→` | `PropTypes.string`                       |
|   `ptsr→` | `PropTypes.string.isRequired`            |
|   `ptnd→` | `PropTypes.node`                         |
|  `ptndr→` | `PropTypes.node.isRequired`              |
|   `ptel→` | `PropTypes.element`                      |
|  `ptelr→` | `PropTypes.element.isRequired`           |
|    `pti→` | `PropTypes.instanceOf(name)`             |
|   `ptir→` | `PropTypes.instanceOf(name).isRequired`  |
|    `pte→` | `PropTypes.oneOf([name])`                |
|   `pter→` | `PropTypes.oneOf([name]).isRequired`     |
|   `ptet→` | `PropTypes.oneOfType([name])`            |
|  `ptetr→` | `PropTypes.oneOfType([name]).isRequired` |
|   `ptao→` | `PropTypes.arrayOf(name)`                |
|  `ptaor→` | `PropTypes.arrayOf(name).isRequired`     |
|   `ptoo→` | `PropTypes.objectOf(name)`               |
|  `ptoor→` | `PropTypes.objectOf(name).isRequired`    |
|   `ptsh→` | `PropTypes.shape({ })`                   |
|  `ptshr→` | `PropTypes.shape({ }).isRequired`        |
|  `ptany→` | `PropTypes.any`                          |
| `ptypes→` | `const propTypes = {};`                  |
| `dtypes→` | `const defaultProps = {};`               |

## Console

| Prefix | Method                              |
| -----: | ----------------------------------- |
| `clg→` | `console.log(object)`               |
| `clo→` | `console.log("object", object)`     |
| `ctm→` | `console.time("timeId")`            |
| `cte→` | `console.timeEnd("timeId")`         |
| `cas→` | `console.assert(expression,object)` |
| `ccl→` | `console.clear()`                   |
| `cco→` | `console.count(label)`              |
| `cdi→` | `console.dir`                       |
| `cer→` | `console.error(object)`             |
| `cgr→` | `console.group(label)`              |
| `cge→` | `console.groupEnd()`                |
| `ctr→` | `console.trace(object)`             |
| `cwa→` | `console.warn`                      |
| `cin→` | `console.info`                      |

## React Components

### `rcc`

```javascript
import React from 'react';
import styled from 'styled-components';
import PropTypes from 'prop-types';

// #region constants

// #endregion

// #region styled-components

// #endregion

// #region functions

// #endregion

// #region component
const propTypes = {};

const defaultProps = {};

/**
 * 
 */
class FileName extends React.Component {
  constructor(props) {
    super(props);

    this.state = {
    };
  }

  render() {
    return <div>$2</div>;
  }
}

FileName.propTypes = propTypes;
FileName.defaultProps = defaultProps;
// #endregion

export default FileName;
```

### `rpc`

```javascript
import React from 'react';
import styled from 'styled-components';
import PropTypes from 'prop-types';

// #region constants

// #endregion

// #region styled-components

// #endregion

// #region functions

// #endregion

// #region component
const propTypes = {};

const defaultProps = {};

/**
 * 
 */
class FileName extends React.PureComponent {
  constructor(props) {
    super(props);

    this.state = {
    };
  }

  render() {
    return <div>$2</div>;
  }
}

FileName.propTypes = propTypes;
FileName.defaultProps = defaultProps;
// #endregion

export default FileName;
```

### `rfc`

```javascript
import React from 'react';
import styled from 'styled-components';
import PropTypes from 'prop-types';

// #region constants

// #endregion

// #region styled-components

// #endregion

// #region functions

// #endregion

// #region component
const propTypes = {};

const defaultProps = {};

/**
 * 
 */
const FileName = () => {
  return <div>$0</div>;
}

FileName.propTypes = propTypes;
FileName.defaultProps = defaultProps;
// #endregion

export default FileName;
```

### `reduxmap`

```javascript
// #region redux HOC
const mapStateToProps = (state) => ({
  {$1}: {$2:selector}(state),
});

const actionCreators = {
  {$3}Action: {$3},
};
// //#endregion

connect(
      mapStateToProps,
      actionCreators
    )(Component);
```

## Others

### `cmmb`

```JS
/**
 * $1
 */
```

### `desc`

```javascript
describe('$1', () => {
  $2;
});
```

### `test`

```javascript
test('should $1', () => {
  $2;
});
```

### `tit`

```javascript
it('should $1', () => {
  $2;
});
```

### `stest`

```javascript
import React from 'react';
import { fireEvent } from '@testing-library/react';
import { render } from '../../../../../tests/testUtils';
import { ${1:ComponentName} } from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}

  it('render', () => {
    const { container, getByText } = render(<${1:ComponentName} {...defaultProps} />)
    getByText('');
  });
});
```

### `shtest`

```javascript
import { renderHook } from '@testing-library/react-hooks';
import ${1:HookName} from '../${1:HookName}'

describe('<${1:HookName} />', () => {
  it('Should ', () => {
    const { result } = renderHook(() => ${1:HookName}());
  });
});
```

### `jmock`

```javascript
jest.mock('${1:moduleName}', () => ({
  __esModule: true,
  default: jest
    .fn(() => '')
    .mockImplementationOnce(() => ('mockedReturn'))
    .mockReturnValueOnce('mockedValue'),
}));
```

### `hocredux`

```javascript
import React from 'react'
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

export const mapStateToProps = state => ({

})

export const mapDispatchToProps = {

}

export const ${1:hocComponentName} = (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />

  hocComponent.propTypes = {
  }

  return hocComponent
}

export default WrapperComponent => connect(mapStateToProps, mapDispatchToProps)(${1:hocComponentName}(WrapperComponent))
```

### `hoc`

```javascript
import React from 'react';
import PropTypes from 'prop-types';

const withSomething = (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />;
  hocComponent.wrappedComponent = WrappedComponent;
  hocComponent.propTypes = {};

  return hocComponent;
};

export default withSomething;
```
