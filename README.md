# ts-axios
Implement axios with Typescript 


## Features
- Use XMLHttpRequest Object in web browser
- Support Promise API 
- Support request and response interceptors 
- Support request and response tranformation 
- Support cancellation 
- Automatically tranform JSON data 
- Prevent XSS in client side

## Basic Usage
```
const axios = require('axios')

axios({
  method: 'post',
  url: '/user/12345',
  data: {
    firstName: 'test',
    lastName: 'axios'
  }
})
```

## Check this demo in browser
```npm run dev``` opens node.js server for examples
