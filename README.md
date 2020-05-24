# TypeScript enums for keycode constants

## Installation
 Install types-keycode
```
npm install --save-dev github:mg-kg/types-keycode#master
```

Add **keycode** to compilerOptions of **tsconfig.json** file
```
{  
	...
	"compilerOptions": 
	{
		"types" : ["keycode"]
	}
}
```

## Usage

```
console.log(KeyCode.Enter);
```