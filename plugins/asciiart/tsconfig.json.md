{
  "extends": "../../tsconfig.base",
  "compilerOptions": {
    "composite": true,
    "outDir": "build",
    "tsBuildInfoFile": "build/.tsbuildinfo",
    "emitDeclarationOnly": true,
    "types": ["@cloudflare/workers-types"]
  },
  "include": ["src/**/*.ts"],
  "references": [{ "path": "../../packages/chatgpt-plugin/tsconfig.json" }]
}
