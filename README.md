# appdb

## Usage

``` js
const setupDatabase = require('appdb')

setupDatabase(config).then(db => {
    /*
       forma larga:
       **************************
       const Agent  = db.Agent
       const Metric = db.Metric
       
       forma corta:
       ****************************
       const { Agent, Metric } = db
    */
    const { Agent, Metric } = db
}).catch(err => console.error(err))
```