sos
===

Smalltalk-inspired debug tools for Ruby (aka Son of Smalltalk)


the plan
--------
Provide a browser-based UI (i.e. zero install) that houses the tools a Smalltalk developer would expect including:

1. *Inspectors*: introspect and modify objects
2. *Workspace:* a place to run code like the REPL
3. *Applications Browser*: see the loaded modules and classes / extensions they define
4. *Hierarchy Browser*: explore class hierarchies
5. *Debugger*: threads, call stacks, variables, stepping, and eventually the ability to modify code in place.

the pieces
----------
1. *jquery*: widgets to provide the basic UI bits and pieces
2. *opal*: for ruby -> javascript translation so the UI will be familiar to rubyists
3. *libmicrohttpd*: embedded http server to support REST queries from a running VM
