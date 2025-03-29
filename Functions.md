## info

```luau
function info(string text)
```

This prints text to the console as information also known as Blue print

### Example
```luau
info("Hello, world!") -- Outputs blue print/information
```

## setfps

```lua
setfps(int fps)
```

This sets the players fps/frames per second cap to the int in the 1st arguement

### Example
```luau
setfps(360) -- Sets the max fps as 360
```

## getfps

```lua
getfps()
```

Returns the fps cap as an integer

### Example
```luau
print(getfps()) -- Outputs the fps cap
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

print(connection) -- Outputs the connection index
```
