rexlsx
======

**WIP**

> Create excel documents with React

[![NPM version](https://img.shields.io/npm/v/rexlsx.svg)](https://www.npmjs.com/package/rexlsx)
[![NPM downloads](https://img.shields.io/npm/dm/rexlsx.svg)](https://www.npmjs.com/package/rexlsx)
[![Build Status](https://travis-ci.org/d-band/rexlsx.svg?branch=master)](https://travis-ci.org/d-band/rexlsx)
[![Coverage Status](https://coveralls.io/repos/github/d-band/rexlsx/badge.svg?branch=master)](https://coveralls.io/github/d-band/rexlsx?branch=master)
[![Dependency Status](https://david-dm.org/d-band/rexlsx.svg)](https://david-dm.org/d-band/rexlsx)
[![Greenkeeper badge](https://badges.greenkeeper.io/d-band/rexlsx.svg)](https://greenkeeper.io/)

---

## Install

```bash
$ npm install rexlsx
```

## Usage

```js
import React from 'react';
import { render, Workbook, Sheet, Row, Col, Cell } from 'rexlsx';

class App extends React.Component {
  render() {
    return (
      <Workbook>
        <Sheet name="Sheet 1">
          <Row>
            <Col>
              <Cell>Hello world</Cell>
            <Col>
          </Row>
        </Sheet>
      </Workbook>
    )
  }
}

render(<App />, `${__dirname}/example.xlsx`);
```

## Todo

- [ ] Components: Workbook, Sheet, Row, Col, Cell, Style
- [ ] Add tests
- [ ] Add examples

## Report a issue

* [All issues](https://github.com/d-band/rexlsx/issues)
* [New issue](https://github.com/d-band/rexlsx/issues/new)

## Reference

- http://www.ecma-international.org/publications/standards/Ecma-376.htm
- https://github.com/d-band/better-xlsx

## License

rexlsx is available under the terms of the MIT License.
