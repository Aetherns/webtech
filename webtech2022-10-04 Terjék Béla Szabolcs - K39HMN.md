## ReactDOM
The *react-dom* package provides DOM-specific methods that can be used at the top level of your app and as an escape hatch to get outside the React model if you need to. The *react-dom* package also provides modules specific to client and server apps:
- [react-dom/client](https://reactjs.org/docs/react-dom-client.html)
- [react-dom/server](https://reactjs.org/docs/react-dom-server.html)

These react-dom methods are also exported, but are considered legacy:
1. `render()`
2. `hydrate()`
3. `findDOMNode()`
4. `unmountComponentAtNode()`
## Legacy Reference
Render a React element into the DOM in the supplied container and return a reference to the component (or returns null for stateless components). If the React element was previously rendered into container, this will perform an update on it and only mutate the DOM as necessary to reflect the latest React element.

\# is also important.
