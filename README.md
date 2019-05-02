mahjong-format
==============

This project aims to standarize a set of schemas and protos for online mahjong games, with regard
to support multiple different mahjong rules. 

The schemas would be designed to be an exchangable format to describe mahjong replays and rule sets,
and aim to provide in multiple underlying data exchange formats (JSON, XML, protobuf, etc.).

The protos would be designed for online mahjong games to communicate in a client-server system,
and would be targetting protobuf only for performance considerations. Protocol would also standarize
the method for the server to generate random seeds to enforce a verifiable random behavior for the games.
