# Node-modules
Publishing the node modules
How to publish my node module:
1. Make a common folder next to client and server
2. Write down the code and make sure to export
3. Make account in npmjs.org and in vs code use npm login and login into account
4. Make changes in package.json such as: 
	"name": "@100xabhash/common"
5. Make changes in tsconfig.json such as: 
	"rootDir": "src",
	"outDir": "dist",
	"declearation": true
6. use npm public --access=public
