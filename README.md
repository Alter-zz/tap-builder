# tap-builder

```
tap-builder/
  ├── apps/
  │   ├── web/        # 前端项目，之前的 frontend-core
  │   ├── server/
  │   ├── node-agent/      # 后端节点管理项目
  │   └── console/     # 后端控制台项目 可
  ├── plugins/             # 插件目录
  │   ├── plugin-auth/
  │   ├── plugin-database/
  │   ├── plugin-analytics/
  │   └── plugin-...
  ├── packages/            # 其他共享包和库
  │   ├── shared-utils/
  │   └── ui-components/
  ├── package.json
  └── turbo.json
```
atoms
	按照模块分
		home/index.ts
components

hooks
	按模块分
		home/index.ts
pages

services
	API 按模块分
		home/index.ts
utils
	constants.ts 常量
