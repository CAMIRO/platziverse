# platziverse-db

## Usage

``` js

const setupDataBase = require('plaztziverse-db')

setupDatabase(config).then(db => { 
    const { Agent, Metric } = db

}).catch(err => console.log(err))

```