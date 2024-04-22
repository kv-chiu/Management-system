# Management-system

## Initial project

### 1. Create a web project

```shell
pnpm create next-app
```

> [!NOTE]
> Possible error:
> ```shell
> npm ERR! code CERT_HAS_EXPIRED
> npm ERR! errno CERT_HAS_EXPIRED
> npm ERR! request to xxx failed, reason: certificate has expired
>
> npm ERR! A complete log of this run can be found in: xxx
> ```
> Solution:
> ```shell
> pnpm config set registry https://registry.npmmirror.com
> npm install -g pnpm
> ```
