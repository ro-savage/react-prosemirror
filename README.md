# react-prosemirror
A [React](https://facebook.github.io/react/) component for [ProseMirror](http://prosemirror.net/).

This is a placeholder until ProseMirror itself is stable enough to begin publishing to NPM.

- [GibHub Repo](https://github.com/tgecho/react-prosemirror)
- [Demo](http://tgecho.github.io/react-prosemirror)
- [Kudos](http://marijnhaverbeke.nl/)
- [Author](http://un.deter.red)

## Hello World

```
import ProseMirror from 'react-prosemirror'

const Hello = React.createClass({
  getInitialState() {
    return {value: 'Hello World!'}
  },
  render() {
    return <ProseMirror value={value} onChange={callback} />
  },
  onChange(value) {
    this.setState({value})
  }
})
```
