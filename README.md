# markov-research

~~A project destined to fail, but making it horrible and spectacular at the same time.~~

A repo that does basic word linking and then spits it out in another format.

## Requirements

Current requirements dicate that rethinkdb is used and a node version with import capability (this package uses the module typeset).

## Current limitations

This is currently bound by the nature that the windows file system behaves upon despite it being on an external database.

The next set of goals would be to:

- Detach from rethinkdb backend and move to either sqlite or static json.
- Define a higher efficency learning model.
- Provide an interface that other projects may use.