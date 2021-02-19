# CV

## Denys Ulvanskyi

I am 31 years programmer. I've learning coding since 2018 years. Since the time that I understand programing is more than hobby, I've learned main front-end technology and fundamental of backend (I mean node.js).
Also, I everyday hard work to stay better by readeng, wathing and listenin about programing.
I have couple of pet-project written by react.js and vanilla javascript.

##I work with
- JavaScipt
- CSS/SCSS
- ReactJS
- JS libraries
- NodeJS

## Example of code
```javascript
const express = require('express')
const app = express()
const mongoose = require('mongoose')
require('dotenv')
const bodyParser = require('body-parser')

app.use(bodyParser.json())

const mainRoute = require('./router/main')
const aboutRoute = require('./router/about')
const postRoute = require('./router/post')


app.use('/', mainRoute)
app.use('/about', aboutRoute)
app.use('/post', postRoute)


mongoose.connect('process.env.DB_CONNECTION',{
    useUnifiedTopology: true,
    useNewUrlParser: true
    }, ()=>{
    console.log('MongoDB is connected')
})

app.listen(3000, ()=> console.log(`Server runs on port 3000`))
```

## Experience

I've worked as a freelancer since 2017.

## English language
My English language level is upper-intermediate.


