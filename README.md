# node-clean

We can remove `node_modules` directory on project directories.


## Clone to

We can not remove node modules directory if there node project is child in nested directory structure.

```
{Your projects directory}
├── node-clean
│   ├── README.md (This document)
│   └── clean.sh
└── {project directory}...
```


## Execute

```
sh clean.sh
```
