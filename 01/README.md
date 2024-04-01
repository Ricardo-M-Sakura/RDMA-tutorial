Complier library：`libibverbs `
How to Compile:gcc <filename>  -o service  -libverbs
How to run：
1. IB support：
       server：./service
       client：./service server IP
 2. ROCE support:
       server：./service   -g  0
       client：./service -g 0  server IP
