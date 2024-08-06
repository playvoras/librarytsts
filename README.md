```
local smoll = loadstring(game:HttpGet('https://raw.githubusercontent.com/playvoras/librarytsts/main/souce.lua'))()
local idk = smoll.SetupUI({
	Title = "THIS! IS! title :>"
})

local againidk = idk.CreateTabs({
	Text = "THIS! IS! tabs :>"
})

againidk.CreateToggle({
	Text = "THIS! IS! toggle :>",
	Callback = (function(a)
		print(a)
	end),
})

againidk.CreateSlider({
	Text = "THIS! IS! slider :>",
	Minimum = 0,
	Maximum = 1,
	Default = 0.5,
	Precise = true,
	Callback = (function(a)
		print(a)
	end),
})
-- too lazy to implemented refresh dropdown sowwy :<<
againidk.CreateDropdown({
	Text = "Select Something rAndOm",
	TableList = {"sus","hayayaya","lol","bruh","heh?","oaoaosjdhdf","kys"},
	Callback = (function(a)
		print(a)
	end),
	
})
againidk.CreateButtons({
	Text = "kick your mom",
	Callback = (function()
		print("succesfully kick your mom")
	end),
})
againidk.CreateLabel("CENTER TEXT", Enum.TextXAlignment.Center)
againidk.CreateLabel("LEFT TEXT", Enum.TextXAlignment.Left)
``
