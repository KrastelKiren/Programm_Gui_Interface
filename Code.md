# Programm_Gui_Interface
local GUI = require("GUI")
local screen = require("Screen")
local workspace = GUI.workspace()
workspace:addChild(GUI.panel(1, 1, workspace.width, workspace.height, 0x2D2D2D))
local actionButtonsRegular = workspace:addChild(GUI.actionButtons(3, 2, false))
local actionButtonsFat = workspace:addChild(GUI.actionButtons(3, 4, true))
actionButtonsRegular.close.onTouch = function()
end
workspace:draw()
workspace:start()
