## info

```luau
function info(string text)
```

This prints text to the console as information also known as Blue print

### Example
```luau
info("Hello, world!") -- Outputs blue print/information
```

## getconnection

```luau
<table<ConnectionObject>> getconnection(<RBXScriptSignal> signal, <number> index)
```

Returns a Connection object for index

### Example
```luau
local inputService = game:GetService("UserInputService")
local connection = getconnection(inputService.InputBegan, 1)

print(connection) -- should print the connection index
```
