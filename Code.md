# Programm_Gui_Interface
local GUI = require("GUI")
local screen = require("Screen")
local workspace = GUI.workspace()
local object = workspace:addChild(GUI.object(3, 2, 50, 10))
workspace:draw()
workspace:start()
