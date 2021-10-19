# Safari iframe sandboxed event issue

To run:

1. `npm install --global http-server`
2. `http-server .`
3. Open `http://localhost:8080`
4. Open dev tools
5. Try clicking `link`

**bug**
`example.com` opens in the iframe. Instead we expect the outer event listern to receive the click event.