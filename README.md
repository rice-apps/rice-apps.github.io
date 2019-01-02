# RiceApps Documentation Guidelines
 

## Setup
1. Download Docsify CLI

```
npm i docsify-cli -g
```

2. Git clone this repo
```
git clone https://github.com/rice-apps/riceapps.git
```
3. To run locally at http://localhost:3000: 
```
docsify serve docs
```

---

## Documentation Structure

If you need more pages, you can simply create more markdown files in your docsify directory. If you create a file named `guide.md`, then it is accessible via `/#/guide`.

For example, the directory structure is as follows:

```text
.
└── docs
    ├── README.md
    ├── guide.md
    └── zh-cn
        ├── README.md
        └── guide.md
```

Matching routes

```text
docs/README.md        => http://domain.com
docs/guide.md         => http://domain.com/guide
docs/zh-cn/README.md  => http://domain.com/zh-cn/
docs/zh-cn/guide.md   => http://domain.com/zh-cn/guide
```