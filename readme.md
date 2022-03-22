# Read me
## Install
Add the package in your *devDependencies*

````
"eslint-config-waya-tech": "git@github.com:wayatech/eslint-config-waya-tech.git"
````

## Configure
In your _.eslintrc.json_ file : extend from one or many

```
{
  "extends": "waya-tech/default-config"
}
```

```
{
  "extends": [
    "waya-tech/default-config"
  ],
}
```

```
{
  "extends": [
    "waya-tech/default-config",
    "waya-tech/angular-config"
  ],
}
```

## Available configs

- waya-tech/default-config
- waya-tech/angular-config
