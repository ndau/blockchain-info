# blockchain-info
API for static/cached ndau blockchain queries

The standard ndau API provides live queries of the current state of the blockchain. Some
blockchain information isn't suitable for being provided in real time, either due to
performance concerns or the need for the state of the blockchain at a fixed point in
time. This separate API supports such queries, and is distinct from the ndau API to
avoid confusion and separate dependencies. This API supports queries against a database
that is periodically updated by separate tools, and the ndau API has no such database
requirement.
