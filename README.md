# state-token
JAX-REST implementation of this draft to manage state token.

http://tools.ietf.org/html/draft-goland-state-token-00

The library may be imported into your JAX-RS project and it will automatically honor the if-state-match headers if present. The library will include a Servlet Filter against all the requests in your app.
