## getconnections

```lua
<table<ConnectionObject>> getconnections(<RBXScriptSignal> signal)
```
Creates a list of Connection objects for the functions connected to signal.

### kaka

| Field | Type | Description |
| ----- | ---- | ----------- |
| `Enabled` | boolean | Whether the connection can receive events. |
| `ForeignState` | boolean | Whether the function was connected by a foreign Luau state (i.e. CoreScripts). |
| `LuaConnection` | boolean | Whether the connection was created in Luau code. |
| `Function` | function? | The function bound to this connection. Nil when ForeignState is true. |
| `Thread` | thread? | The thread that created the connection. Nil when ForeignState is true. |



## getconnection

```luau
<table<ConnectionObject>> getconnection(<RBXScriptSignal> signal, <number> index)
```

Returns a Connection object for index

