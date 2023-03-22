# Docker Example

```sh
npm install
```

## Remote:

In one terminal run:
```sh
cd remote && npm run build:watch
```

In another run:
```sh
cd remote && npm run preview
```

## Local:

```sh
cd local && npm run dev
```

*Note:*
```txt
Doing that we are going to need to reload the page every time we update the remote
```


## Lerna preview mode
We can also use lerna to run from the workspace both repos on preview mode:
```sh
npm run build && npm run preview
```