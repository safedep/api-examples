# 📦 Insights v2

## 📦 Usage

Add `buf` schema registry

```shell
npm config set @buf:registry https://buf.build/gen/npm/v1/
```

Install dependencies

```shell
npm install
```

Set credentials

```shell
export SAFEDEP_API_KEY=your-api-key
export SAFEDEP_TENANT_ID=your-tenant-id
```

Run the example

> **Note:** This example uses Nodejs 18.x

```shell
npx ts-node --esm index.ts
```

## Reference

- https://buf.build/safedep/api/sdks
