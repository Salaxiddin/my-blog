
<a id="readme-top"></a>

<br />
<div align="center">
  
  <h3 align="center">My-blog</h3>
</div>

## Getting Started

You should instaled all dependensivs

### Installation

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install 
  ```

### Conection
1. Get a free Mongo DB [https://cloud.mongodb.com](https://cloud.mongodb.com)

### In server/index.js you most paste your mongo db 

2. Enter your API in `config.js`
   ```js
   mongoose.connect( #HERE YOU MONGO DB URL ).then(() => console.log('saccess conecting to Data Base!')).catch(err => console.log('DB error :', err))
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

