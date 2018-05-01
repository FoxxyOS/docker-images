# foxxy
Official Foxxy Security image with basic tools.

## Install/Update from docker cloud
```docker pull foxxysec/foxxy```

## Install/Update from local Dockerfile
```docker build -t foxxy[:version] foxxy```

## Start with no persistence
changes are discarded on exit

public image from docker cloud
```docker run -ti --network host foxxysec/foxxy```

local image from Dockerfile
```docker run -ti -network host foxxy```

## Start with persistence
changes are preserved

public image from docker cloud
```docker run -ti -v foxxy:/ --network host foxxysec/foxxy```

local image from Dockerfile
```docker run -ti -v foxxy:/ --network host foxxy```





# foxxy-core
Official Foxxy Security Base system without tools.

## Install/Update from docker cloud
```docker pull foxxysec/foxxy-core```

## Install/Update from local Dockerfile
```docker build -t foxxy-core[:version] foxxy-core```

## Start with no persistence
changes are discarded on exit

public image from docker cloud
```docker run -ti --network host foxxysec/foxxy-core```

local image from Dockerfile
```docker run -ti -network host foxxy-core```

## Start with persistence
changes are preserved

public image from docker cloud
```docker run -ti -v foxxy-core:/ --network host foxxysec/foxxy-core```

local image from Dockerfile
```docker run -ti -v foxxy-core:/ --network host foxxy-core```



# metasploit
Foxxy Security Metasploit bundle

## Install/Update from docker cloud
```docker pull foxxysec/metasploit```

## Install/Update from local Dockerfile
```docker build -t metasploit[:version] metasploit```

## Start with no persistence
changes are discarded on exit

public image from docker cloud
```docker run -ti --network host foxxysec/metasploit```

local image from Dockerfile
```docker run -ti -network host metasploit```

## Start with persistence
changes are preserved

public image from docker cloud
```docker run -ti -v metasploit:/ --network host foxxysec/metasploit```

local image from Dockerfile
```docker run -ti -v metasploit:/ --network host metasploit```
