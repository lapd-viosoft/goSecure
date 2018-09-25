# gosecure 
Simple command line secure tunneling tool.

## Usage
```
  -cert string
    	Certificate file
  -key string
    	Key file
  -local string
    	Where to listen on this machine [ip_address]:port
  -remote string
    	Where to connect to {ip_address | hostname}:port
```

## Build

After setting Go environment values 
([goenv.sh](https://github.com/diegohce/gosecure/blob/master/goenv.sh) might help), 
go to ```src``` directory and run from the command line:

```make```

That's it.
