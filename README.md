# Setup
This just exports a config so you still need to install prettier as normal  
```bash
    npm i -D prettier @elephantventures/prettier-config
```

# Usage  
Then just reference this config in your `package.json`  
```json
 {
     "name": "blah",
     "prettier": "@elephantventures/prettier-config"
 }
```

OR create a `.prettierrc.json` and export a string
```json
"@elephantventures/prettier-config"
```

# Extend and overwrite
If you want to extend and overwrite the configuration
```JavaScript
import companyPrettierConfig from '@elephantventures/prettier-config'

export defaul {
    ...companyPrettierConfig,
    semi: false,
};
```
