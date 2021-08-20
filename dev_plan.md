before 22.0.0
1. init fundamental infrastructure and determine components which should be used
    1. mongo/es cluster for hot data
    2. sql database cluster for cold data
    3. bigdata component for analyse
    4. a new control panel for game data api with rust
2. determine performance require 
    1. 80 million qps
    2. ap design system
    3. available for linux/unix os