# Storage
This Repository consists of code to gain knowledge about storage data in memory and storage data in disk.

# To Run server.js
`node server.js`

# To store 'POST' data in memory '/memory/foo' path
`curl localhost:3001/memory/foo --header 'Content-Type: application/json' --data '{"data": "This is some data in memory."}'`

# To retrieve 'GET' data from memory 'memory/foo' path
`curl localhost:3001/memory/foo -w "\n"`
<img width="226" alt="image" src="https://github.com/MukeshPullabhatla/Storage/assets/71534604/16c02211-3a63-41cc-9eba-ee0d97853dfc">

# To store 'POST' data in disk '/disk/foo' path
`curl localhost:3001/disk/foo --header 'Content-Type: application/json' --data '{"data": "This is some data in disk."}'`

# To retrieve 'GET' data from disk '/disk/foo' path
`curl localhost:3001/disk/foo -w "\n"`
<img width="215" alt="image" src="https://github.com/MukeshPullabhatla/Storage/assets/71534604/30dcf3c2-f826-47fa-9ea8-aa4ca56eee18">
<img width="305" alt="image" src="https://github.com/MukeshPullabhatla/Storage/assets/71534604/d72b9bce-d3c1-4e42-a3a0-5f78c21fb1ea">

