# idasec

IDA plugin for reverse-engineering and dynamic interactions with the Binsec platform

## Disclaimer

*IDAsec is prototype tool under development, some features are likely buggy and should be used with care.*

## Features

* Decoding an instruction (in DBA IR)
* Loading execution traces generated by **Pinsec**
* Triggering analyzes on Binsec and retrieving results

## Dependencies

* protobuf
* ZMQ
* capstone *(for trace disassembly)*
* PySide   *(because of IDA)*
* graphviz *(to draw dependency within a formula)*
* pyparsing
* plotly   *(optional)*

## Running Idasec

1. In IDA: Copy the `idasec` folder in the python directory of IDA and then load `idasec.py` with Ctrl+F7
2. As a standalone app, just run `./idasec.py` (no yet ready)

## Documentation

Yet to come..

## Screenshots

![idasec 1](https://raw.github.com/RobinDavid/idasec/master/screenshot/idasec1.png)

![idasec 2](https://raw.github.com/RobinDavid/idasec/master/screenshot/idasec2.png)

![idasec 3](https://raw.github.com/RobinDavid/idasec/master/screenshot/idasec3.png)

## TODO

Too much to be listed..