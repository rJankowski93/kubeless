Kubeless Event and Type Definitions 

# Package Overview

This package contain Ballerina type definitions used in Ballerina Kubeless integration.

## Compatibility
|                    |    Version     |  
|:------------------:|:--------------:|
| Ballerina Language |   0.981.0      |
| Kubeless Package   |   0.0.8        |


## Sample

```ballerina
import kubeless/kubeless;

public function echo(kubeless:Event event, kubeless:Context context) returns (string|error) {
    
    return <string>event.data;
}
```
