### Prerequisites

You need to install [kingraph](https://github.com/rstacruz/kingraph).

```
npm install -g rstacruz/kingraph
```

### Generate svg file (default)

```
kingraph .\Stammbaum.yml > Stammbaum.svg
```

### Generate dot file

```
kingraph .\Stammbaum.yml -F dot > Stammbaum.dot
```