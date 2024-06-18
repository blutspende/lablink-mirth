# lablink-mirth
Integration of lablink and Mirth Connect

## Group templates
### lablink orders 1.0
Reads order files and sends the orders they contain to lablink.
> Requires the channel group `lablink tools 1.0`
#### Channels
* ll send orders to lablink

### lablink results 1.0
Checks lablink for new results and writes them to the results file.
> Requires the channel group `lablink tools 1.0`
#### Channels
* ll get results from lablink answer
* ll read results
* ll write results file
* ll set orderIds tags

### lablink tools 1.0
Different individual tool channels
#### Channels
* ll get token
* ll read analytes
* ll read institute locations
