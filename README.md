# ripsum
Random word generator based on the Lorem Ipsum text.

> Who cares if it doesn't make sense? It's all Latin to me anyway.


## Build Instructions

### Using yarn

```
yarn
yarn compile
```

### Using npm

```
npm install
npm run compile
```

The resulting executable will be located in the `build` folder.

## Usage Instructions

```
./build/ripsum <n>
```

where `<n>` is the number of words in the output text (default is 5).

## Example output

```
$ ripsum 3
odio blandit dolores (copied to clipboard)
$ ripsum 10
quis odio veniam id adipiscing tempor sadipscing duis duo assum (copied to clipboard)
$ ripsum 20
assum wisi praesent nibh eleifend duis consectetuer blandit facer dolores diam ea magna sanctus sit facilisis lorem accumsan amet eos (copied to clipboard)
```
