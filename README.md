## Usage
Install the configs with
```sh
npm install --save-dev @andjsrk/tsconfig
```
then update `extends` field on your `tsconfig.json`:
```json
{
	"extends": "@andjsrk/tsconfig/base",
	// ...
}
```
That's all.

## Available configs
- [`base`](./base/tsconfig.json)

## Notes
- The configs assumes your project is ESM-based.
- All compiler options are recommended to not override, unless otherwise marked with `// overridable`.
