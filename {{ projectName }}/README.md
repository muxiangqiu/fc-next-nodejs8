
# {{ projectName }}

## 准备

1. 安装 node

```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.5/install.sh | bash
nvm install 8
```

## 安装依赖

```bash
npm install
```

## 本地运行 Nextjs

```bash
npm run dev
```


## 编译 Nextjs

```bash
npm run build
```

## 本地运行函数

```bash
npm run start
```

## 部署函数到云端
部署函数的时候需要用到 AK 等下信息，可以通过 fun config 来配置，如果配置过请忽略，部署函数命令如下：

```bash
npm run deploy
```