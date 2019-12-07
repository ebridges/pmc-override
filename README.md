# PMC Override

Overrides a ParkMyCloud Schedule and starts Resources from the command line.

## Usage

```
Usage: pmc-override [-h] -r {development,staging} [-d DURATION]

Arguments:
  -h, --help            show this help message and exit
  
  -r {development,staging}
  --resource {development,staging}
                        Name of the resource whose schedule to override
  
  -d DURATION
  --duration DURATION
                        Duration in hours to override schedule. Default: 2 hours

Configuration
  PMC_AUTH_KEY          ParkMyCloud Private Key
  PMC_AUTH_KEY_ID       ParkMyCloud Private Key ID
```

## Acknowledgements

Thanks to the fine folks at [ParkMyCloud, Inc.](https://www.parkmycloud.com/) for a fine service.

