--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 67 | Scripts: 13 | Modules: 6 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["Enabled"] = false;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.Script
G2L["2"] = Instance.new("Script", G2L["1"]);



-- StarterGui.ScreenGui.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.ScreenGui.Data
G2L["4"] = Instance.new("LocalScript", G2L["1"]);
G2L["4"]["Name"] = [[Data]];


-- StarterGui.ScreenGui.Data.Start
G2L["5"] = Instance.new("ModuleScript", G2L["4"]);
G2L["5"]["Name"] = [[Start]];


-- StarterGui.ScreenGui.drag
G2L["6"] = Instance.new("Frame", G2L["1"]);
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["Size"] = UDim2.new(0, 597, 0, 39);
G2L["6"]["Position"] = UDim2.new(0.08333, 0, 0.09814, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(214, 214, 214);
G2L["6"]["Name"] = [[drag]];


-- StarterGui.ScreenGui.drag.Drag Gui Script
G2L["7"] = Instance.new("LocalScript", G2L["6"]);
G2L["7"]["Name"] = [[Drag Gui Script]];


-- StarterGui.ScreenGui.drag.ImageLabel
G2L["8"] = Instance.new("ImageLabel", G2L["6"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Image"] = [[rbxassetid://74930866373729]];
G2L["8"]["Size"] = UDim2.new(0.02765, 15, 0.24385, 15);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Position"] = UDim2.new(0.011, 0, 0.2, 0);


-- StarterGui.ScreenGui.drag.ImageLabel.UIAspectRatioConstraint
G2L["9"] = Instance.new("UIAspectRatioConstraint", G2L["8"]);



-- StarterGui.ScreenGui.drag.TextLabel
G2L["a"] = Instance.new("TextLabel", G2L["6"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 14;
G2L["a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Size"] = UDim2.new(0, 200, 0, 25);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Text"] = [[Project SnoopDogg]];
G2L["a"]["Position"] = UDim2.new(0.06341, 0, 0.17, 0);


-- StarterGui.ScreenGui.drag.TextButton
G2L["b"] = Instance.new("TextButton", G2L["6"]);
G2L["b"]["TextWrapped"] = true;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 14;
G2L["b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["Size"] = UDim2.new(0, 44, 0, 24);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[_]];
G2L["b"]["Position"] = UDim2.new(0.81207, 0, 0, 0);


-- StarterGui.ScreenGui.drag.TextButton.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.drag.Gui
G2L["d"] = Instance.new("Frame", G2L["6"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0, 11, 0, 15);
G2L["d"]["Position"] = UDim2.new(0, 0, 1.09, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Name"] = [[Gui]];


-- StarterGui.ScreenGui.drag.Gui.Exe
G2L["e"] = Instance.new("Frame", G2L["d"]);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(248, 248, 248);
G2L["e"]["Size"] = UDim2.new(0, 597, 0, 411);
G2L["e"]["Position"] = UDim2.new(0, 0, -0.2, 0);
G2L["e"]["BorderColor3"] = Color3.fromRGB(214, 214, 214);
G2L["e"]["Name"] = [[Exe]];


-- StarterGui.ScreenGui.drag.Gui.Exe.Frame
G2L["f"] = Instance.new("Frame", G2L["e"]);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["Size"] = UDim2.new(0, 572, 0, 370);
G2L["f"]["Position"] = UDim2.new(0.01968, 0, 0.07751, 0);
G2L["f"]["BorderColor3"] = Color3.fromRGB(214, 214, 214);


-- StarterGui.ScreenGui.drag.Gui.Exe.ScrollingFrame
G2L["10"] = Instance.new("ScrollingFrame", G2L["e"]);
G2L["10"]["Active"] = true;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["10"]["Size"] = UDim2.new(0, 556, 0, 77);
G2L["10"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Position"] = UDim2.new(0.04651, 0, 0.73255, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["10"]["ScrollBarThickness"] = 0;


-- StarterGui.ScreenGui.drag.Gui.Exe.ScrollingFrame.TextLabel
G2L["11"] = Instance.new("TextLabel", G2L["10"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["11"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Size"] = UDim2.new(0, 556, 0, 760);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[LOG]];


-- StarterGui.ScreenGui.drag.Gui.Exe.ScrollingFrame.TextLabel.LOG
G2L["12"] = Instance.new("LocalScript", G2L["11"]);
G2L["12"]["Name"] = [[LOG]];


-- StarterGui.ScreenGui.drag.Gui.Exe.Field
G2L["13"] = Instance.new("TextBox", G2L["e"]);
G2L["13"]["Name"] = [[Field]];
G2L["13"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["13"]["TextWrapped"] = true;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["ClearTextOnFocus"] = false;
G2L["13"]["PlaceholderText"] = [[print("FeBypassed")]];
G2L["13"]["Size"] = UDim2.new(0, 448, 0, 244);
G2L["13"]["Position"] = UDim2.new(0.04651, 0, 0.10417, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["13"]["Text"] = [[]];


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton
G2L["14"] = Instance.new("TextButton", G2L["e"]);
G2L["14"]["TextSize"] = 12;
G2L["14"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["Size"] = UDim2.new(0.01, 58, -0, 20);
G2L["14"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["14"]["Text"] = [[HIDE TEXT]];
G2L["14"]["Position"] = UDim2.new(0.75296, 0, 0.0173, 0);


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
G2L["15"] = Instance.new("LocalScript", G2L["14"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Script
G2L["16"] = Instance.new("Script", G2L["14"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Stroke
G2L["17"] = Instance.new("UIStroke", G2L["14"]);
G2L["17"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["17"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["17"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton
G2L["18"] = Instance.new("TextButton", G2L["e"]);
G2L["18"]["TextSize"] = 14;
G2L["18"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["18"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["18"]["Size"] = UDim2.new(0.01, 24, -0, 20);
G2L["18"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["18"]["Text"] = [[R6]];
G2L["18"]["Position"] = UDim2.new(0.92833, 0, 0.0173, 0);


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
G2L["19"] = Instance.new("LocalScript", G2L["18"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Script
G2L["1a"] = Instance.new("Script", G2L["18"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Stroke
G2L["1b"] = Instance.new("UIStroke", G2L["18"]);
G2L["1b"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["1b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1b"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton
G2L["1c"] = Instance.new("TextButton", G2L["e"]);
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["Size"] = UDim2.new(0.01, 24, -0, 20);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["1c"]["Text"] = [[RE]];
G2L["1c"]["Position"] = UDim2.new(0.8711, 0, 0.0173, 0);


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
G2L["1d"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript.RE
G2L["1e"] = Instance.new("ModuleScript", G2L["1d"]);
G2L["1e"]["Name"] = [[RE]];


-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Script
G2L["1f"] = Instance.new("Script", G2L["1c"]);



-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.Stroke
G2L["20"] = Instance.new("UIStroke", G2L["1c"]);
G2L["20"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["20"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["20"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.Gui.Exe.TextLabel
G2L["21"] = Instance.new("TextLabel", G2L["e"]);
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 14;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["Size"] = UDim2.new(0, 21, 0, 18);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[>]];
G2L["21"]["Position"] = UDim2.new(0.0483, 0, 0.93645, 0);


-- StarterGui.ScreenGui.drag.Gui.Exe.TextBox
G2L["22"] = Instance.new("TextBox", G2L["e"]);
G2L["22"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["22"]["TextWrapped"] = true;
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["Size"] = UDim2.new(0, 534, 0, 18);
G2L["22"]["Position"] = UDim2.new(0.08407, 0, 0.93645, 0);
G2L["22"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["22"]["Text"] = [[]];


-- StarterGui.ScreenGui.drag.Gui.Frame
G2L["23"] = Instance.new("Frame", G2L["d"]);
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["Size"] = UDim2.new(0.03, 90, 0.02, 247);
G2L["23"]["Position"] = UDim2.new(44.08998, 0, 2.6, 0);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.ScreenGui.drag.Gui.Frame.EXE
G2L["24"] = Instance.new("TextButton", G2L["23"]);
G2L["24"]["TextSize"] = 14;
G2L["24"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["24"]["Size"] = UDim2.new(0, 93, 0, 81);
G2L["24"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["24"]["Text"] = [[EXECUTE]];
G2L["24"]["Name"] = [[EXE]];
G2L["24"]["Position"] = UDim2.new(-0.03139, 0, 0.36656, 0);


-- StarterGui.ScreenGui.drag.Gui.Frame.EXE.LocalScript
G2L["25"] = Instance.new("LocalScript", G2L["24"]);



-- StarterGui.ScreenGui.drag.Gui.Frame.EXE.LocalScript.LauU
G2L["26"] = Instance.new("ModuleScript", G2L["25"]);
G2L["26"]["Name"] = [[LauU]];


-- StarterGui.ScreenGui.drag.Gui.Frame.EXE.Stroke
G2L["27"] = Instance.new("UIStroke", G2L["24"]);
G2L["27"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["27"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["27"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton
G2L["28"] = Instance.new("TextButton", G2L["23"]);
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["Size"] = UDim2.new(0, 93, 0, 81);
G2L["28"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["28"]["Text"] = [[CLEAR]];
G2L["28"]["Position"] = UDim2.new(-0.03139, 0, 0.69737, 0);


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Script
G2L["29"] = Instance.new("Script", G2L["28"]);



-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript
G2L["2a"] = Instance.new("LocalScript", G2L["28"]);



-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript.Clear
G2L["2b"] = Instance.new("ModuleScript", G2L["2a"]);
G2L["2b"]["Name"] = [[Clear]];


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Stroke
G2L["2c"] = Instance.new("UIStroke", G2L["28"]);
G2L["2c"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["2c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2c"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.Gui.Frame.UIListLayout
G2L["2d"] = Instance.new("UIListLayout", G2L["23"]);
G2L["2d"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["2d"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["2d"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton
G2L["2e"] = Instance.new("TextButton", G2L["23"]);
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextColor3"] = Color3.fromRGB(39, 39, 39);
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(239, 239, 239);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["Size"] = UDim2.new(0, 93, 0, 81);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(128, 132, 132);
G2L["2e"]["Text"] = [[INJECT]];
G2L["2e"]["Position"] = UDim2.new(-0.03139, 0, 1.02818, 0);


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Script
G2L["2f"] = Instance.new("Script", G2L["2e"]);



-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript.Inject
G2L["31"] = Instance.new("ModuleScript", G2L["30"]);
G2L["31"]["Name"] = [[Inject]];


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript.Inject.Notifactions
G2L["32"] = Instance.new("ModuleScript", G2L["31"]);
G2L["32"]["Name"] = [[Notifactions]];


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Click
G2L["33"] = Instance.new("UIGradient", G2L["2e"]);
G2L["33"]["Enabled"] = false;
G2L["33"]["Rotation"] = 90;
G2L["33"]["Name"] = [[Click]];
G2L["33"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(173, 231, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(173, 231, 255))};


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Normal
G2L["34"] = Instance.new("UIGradient", G2L["2e"]);
G2L["34"]["Rotation"] = 90;
G2L["34"]["Name"] = [[Normal]];
G2L["34"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.452, Color3.fromRGB(254, 254, 254)),ColorSequenceKeypoint.new(0.531, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(255, 255, 255))};


-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.Stroke
G2L["35"] = Instance.new("UIStroke", G2L["2e"]);
G2L["35"]["Color"] = Color3.fromRGB(191, 191, 191);
G2L["35"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["35"]["Name"] = [[Stroke]];


-- StarterGui.ScreenGui.drag.min
G2L["36"] = Instance.new("TextButton", G2L["6"]);
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextSize"] = 14;
G2L["36"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["AnchorPoint"] = Vector2.new(1, 0);
G2L["36"]["BackgroundTransparency"] = 1;
G2L["36"]["Size"] = UDim2.new(0, 39, 0, 32);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[]];
G2L["36"]["Name"] = [[min]];
G2L["36"]["Position"] = UDim2.new(1.06501, -120, 0, 0);


-- StarterGui.ScreenGui.drag.min.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["36"]);



-- StarterGui.ScreenGui.drag.min.frame
G2L["38"] = Instance.new("Frame", G2L["36"]);
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Name"] = [[frame]];


-- StarterGui.ScreenGui.drag.min.ImageLabel
G2L["39"] = Instance.new("ImageLabel", G2L["36"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["39"]["Image"] = [[http://www.roblox.com/asset/?id=14953689987]];
G2L["39"]["Size"] = UDim2.new(0, 12, 0, 12);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["BackgroundTransparency"] = 1;
G2L["39"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.drag.max
G2L["3a"] = Instance.new("TextButton", G2L["6"]);
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["AnchorPoint"] = Vector2.new(1, 0);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["Size"] = UDim2.new(0, 37, 0, 32);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[]];
G2L["3a"]["Name"] = [[max]];
G2L["3a"]["Position"] = UDim2.new(1.02648, -60, 0, 0);


-- StarterGui.ScreenGui.drag.max.frame
G2L["3b"] = Instance.new("Frame", G2L["3a"]);
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["Name"] = [[frame]];


-- StarterGui.ScreenGui.drag.max.ImageLabel
G2L["3c"] = Instance.new("ImageLabel", G2L["3a"]);
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["ImageColor3"] = Color3.fromRGB(208, 208, 208);
G2L["3c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3c"]["Image"] = [[http://www.roblox.com/asset/?id=14953690282]];
G2L["3c"]["Size"] = UDim2.new(0, 12, 0, 12);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["BackgroundTransparency"] = 1;
G2L["3c"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.drag.close
G2L["3d"] = Instance.new("TextButton", G2L["6"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["AnchorPoint"] = Vector2.new(1, 0);
G2L["3d"]["BackgroundTransparency"] = 1;
G2L["3d"]["Size"] = UDim2.new(0, 44, 0, 32);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[]];
G2L["3d"]["Name"] = [[close]];
G2L["3d"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.ScreenGui.drag.close.LocalScript
G2L["3e"] = Instance.new("LocalScript", G2L["3d"]);



-- StarterGui.ScreenGui.drag.close.frame
G2L["3f"] = Instance.new("Frame", G2L["3d"]);
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["Size"] = UDim2.new(1, 0, 0.95908, 0);
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Name"] = [[frame]];


-- StarterGui.ScreenGui.drag.close.frame.noround
G2L["40"] = Instance.new("Frame", G2L["3f"]);
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["Size"] = UDim2.new(0.5, 0, 1, 0);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Name"] = [[noround]];


-- StarterGui.ScreenGui.drag.close.frame.noround
G2L["41"] = Instance.new("Frame", G2L["3f"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Size"] = UDim2.new(1, 0, 0.5, 0);
G2L["41"]["Position"] = UDim2.new(0, 0, 0.5, 0);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Name"] = [[noround]];


-- StarterGui.ScreenGui.drag.close.ImageLabel
G2L["42"] = Instance.new("ImageLabel", G2L["3d"]);
G2L["42"]["BorderSizePixel"] = 0;
G2L["42"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["42"]["ImageColor3"] = Color3.fromRGB(113, 113, 113);
G2L["42"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["42"]["Image"] = [[http://www.roblox.com/asset/?id=274958830]];
G2L["42"]["Size"] = UDim2.new(0, 12, 0, 12);
G2L["42"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["42"]["BackgroundTransparency"] = 1;
G2L["42"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.TEXT
G2L["43"] = Instance.new("TextLabel", G2L["1"]);
G2L["43"]["TextWrapped"] = true;
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["TextSize"] = 14;
G2L["43"]["TextScaled"] = true;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["FontFace"] = Font.new([[rbxasset://fonts/families/PressStart2P.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["43"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["43"]["BackgroundTransparency"] = 1;
G2L["43"]["Size"] = UDim2.new(0, 407, 0, 80);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Text"] = [[INJECT!]];
G2L["43"]["Name"] = [[TEXT]];
G2L["43"]["Position"] = UDim2.new(0.347, 0, -0.999, 0);


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["5"]] = {
Closure = function()
    local script = G2L["5"];local M = {}

function M.Start()
	local msg = Instance.new("Message", game.Workspace)
	msg.Text = "Wait Until SnoopDogg Inject"
	
	wait(7)
	script.Parent.Parent.Enabled = true
	msg:Destroy()
end

return M
end;
};
G2L_MODULES[G2L["1e"]] = {
Closure = function()
    local script = G2L["1e"];local CharacterUtils = {}


function CharacterUtils.KillCharacter(player)
	local Players = game:GetService("Players")
	local targetPlayer

	
	if typeof(player) == "string" then
		targetPlayer = Players:FindFirstChild(player)
	elseif player:IsA("Player") then
		targetPlayer = player
	else
		warn("KillCharacter: Invalid player parameter")
		return
	end

	if not targetPlayer then
		warn("KillCharacter: Player not found")
		return
	end

	local character = targetPlayer.Character
	if not character then
		warn("KillCharacter: Player has no character")
		return
	end

	local humanoid = character:FindFirstChildOfClass("Humanoid")
	if humanoid and humanoid.Health > 0 then
		humanoid.Health = 0
	end
end

function CharacterUtils.LoadCharacter(player)
	local Players = game:GetService("Players")
	local targetPlayer

	if typeof(player) == "string" then
		targetPlayer = Players:FindFirstChild(player)
	elseif player:IsA("Player") then
		targetPlayer = player
	else
		warn("LoadCharacter: Invalid player parameter")
		return
	end

	if not targetPlayer then
		warn("LoadCharacter: Player not found")
		return
	end


	targetPlayer:LoadCharacter()
end

return CharacterUtils
end;
};
G2L_MODULES[G2L["26"]] = {
Closure = function()
    local script = G2L["26"];local Lua = {}

function Lua.execute(code)
	local Success, err = pcall(function()
		loadstring(code)()
	end)
	
	if Success then
		print("OK")
	else
		warn("loadstring not availabe", tostring(err))
	end
end

return Lua
end;
};
G2L_MODULES[G2L["2b"]] = {
Closure = function()
    local script = G2L["2b"];local M = {}

function M.Clear()
	script.Parent.Parent.Parent.Parent.Exe.Field.Text = ""
end

return M
end;
};
G2L_MODULES[G2L["31"]] = {
Closure = function()
    local script = G2L["31"];local Injection = {}

function Injection.Inject(Name, parent)
	local injected = false
	
	local remoteF = Instance.new("RemoteFunction")
	remoteF.Parent = parent
	remoteF.Name = Name
	
	
	
	local N = require(script.Notifactions)
	if remoteF then
			N.SendN("SnoopDog Says", game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId).Name.." Was  Already Infected", 5)
		else
			N.SendN("SnoopDog Says", game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId).Name.." Was Infected", 5)
    end
end

return Injection
end;
};
G2L_MODULES[G2L["32"]] = {
Closure = function()
    local script = G2L["32"];local Injected = {}

function Injected.SendN(Title, Message, duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title;
		Text = Message;
		Icon = "rbxassetid://74930866373729";
		Duration = duration; 
	})
end

return Injected
end;
};
-- StarterGui.ScreenGui.LocalScript
local function C_3()
local script = G2L["3"];
	print(
		[[ 	
	██████████████████████████████████████████████▀█████▀████████████████████████████████████████
	█─▄▄▄▄█▄─▀█▄─▄█─▄▄─█─▄▄─█▄─▄▄─█▄─▄▄▀█─▄▄─█─▄▄▄▄█─▄▄▄▄███─▄▄▄▄██▀▄─██▄─▄█▄─▄▄▀███▄─▀█▄─▄█─▄▄─█
	█▄▄▄▄─██─█▄▀─██─██─█─██─██─▄▄▄██─██─█─██─█─██▄─█─██▄─███▄▄▄▄─██─▀─███─███─██─████─█▄▀─██─██─█
	▀▄▄▄▄▄▀▄▄▄▀▀▄▄▀▄▄▄▄▀▄▄▄▄▀▄▄▄▀▀▀▄▄▄▄▀▀▄▄▄▄▀▄▄▄▄▄▀▄▄▄▄▄▀▀▀▄▄▄▄▄▀▄▄▀▄▄▀▄▄▄▀▄▄▄▄▀▀▀▀▄▄▄▀▀▄▄▀▄▄▄▄▀
		]]
	)
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Data
local function C_4()
local script = G2L["4"];
	require(script.Start).Start()
end;
task.spawn(C_4);
-- StarterGui.ScreenGui.drag.Drag Gui Script
local function C_7()
local script = G2L["7"];
	function dragify(Main)
	dragToggle = nil
	dragSpeed = 0.95 -- You can edit this.
	dragInput = nil
	dragStart = nil
	dragPos = nil
	
	function updateInput(input)
	Delta = input.Position - dragStart
	Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	game:GetService("TweenService"):Create(Main, TweenInfo.new(.25), {Position = Position}):Play()
	end
	
	Main.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
	dragToggle = true
	dragStart = input.Position
	startPos = Main.Position
	input.Changed:Connect(function()
	if (input.UserInputState == Enum.UserInputState.End) then
	dragToggle = false
	end
	end)
	end
	end)
	
	Main.InputChanged:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
	dragInput = input
	end
	end)
	
	game:GetService("UserInputService").InputChanged:Connect(function(input)
	if (input == dragInput and dragToggle) then
	updateInput(input)
	end
	end)
	end
	
	dragify(script.Parent)
end;
task.spawn(C_7);
-- StarterGui.ScreenGui.drag.TextButton.LocalScript
local function C_c()
local script = G2L["c"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Frame.Visible = not script.Parent.Parent.Frame.Visible
	end)
end;
task.spawn(C_c);
-- StarterGui.ScreenGui.drag.Gui.Exe.ScrollingFrame.TextLabel.LOG
local function C_12()
local script = G2L["12"];
	local logLabel = script.Parent  
	local logMessages = {}  
	
	logLabel.RichText = true
	logLabel.Text = ""  
	
	print("SnoopDog Said No")
	
	local function addLogMessage(messageType, message)
		local formattedMessage = ""
	
		if messageType == "Output" then
			formattedMessage = string.format('<font color="rgb(0, 0, 0)">[Output] %s</font>', message)  
		elseif messageType == "Information" then
			formattedMessage = string.format('<font color="rgb(0, 0, 0)">[Info] %s</font>', message)  
		elseif messageType == "Warning" then
			formattedMessage = string.format('<font color="rgb(0, 0, 0)">[Warning] %s</font>', message)  
		elseif messageType == "Error" then
			formattedMessage = string.format('<font color="rgb(0, 0, 0)">[Error] %s</font>', message)  
		end
	
	
		table.insert(logMessages, 1, formattedMessage)
	
	
		logLabel.Text = table.concat(logMessages, "\n")
	end
	
	
	game:GetService("LogService").MessageOut:Connect(function(message, messageType)
		local messageTypeText
		if messageType == Enum.MessageType.MessageOutput then
			messageTypeText = "Output"
		elseif messageType == Enum.MessageType.MessageInfo then
			messageTypeText = "Information"
		elseif messageType == Enum.MessageType.MessageWarning then
			messageTypeText = "Warning"
		elseif messageType == Enum.MessageType.MessageError then
			messageTypeText = "Error"
		end
	
		addLogMessage(messageTypeText, message)
	end)
end;
task.spawn(C_12);
-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
local function C_15()
local script = G2L["15"];
	local text = script.Parent.Parent.Field
	local hidden = false
	script.Parent.MouseButton1Click:Connect(function()
	if hidden == false then
	
	
			text.TextTransparency = 0.1
			wait()
			text.TextTransparency = 0.2
			wait()
			text.TextTransparency = 0.3
			wait()
			text.TextTransparency = 0.4
			wait()
			text.TextTransparency = 0.5
			wait()
			text.TextTransparency = 0.6
			wait()
			text.TextTransparency = 0.7
			wait()
			text.TextTransparency = 0.8
			wait()
			text.TextTransparency = 0.9
			wait()
			text.TextTransparency = 1
		hidden = true
	else
		hidden = false
			text.TextTransparency = 0.9
			wait()
			text.TextTransparency = 0.8
			wait()
			text.TextTransparency = 0.7
			wait()
			text.TextTransparency = 0.6
			wait()
			text.TextTransparency = 0.5
			wait()
			text.TextTransparency = 0.4
			wait()
			text.TextTransparency = 0.3
			wait()
			text.TextTransparency = 0.2
			wait()
			text.TextTransparency = 0.1
			wait()
			text.TextTransparency = 0
	end	
	end)
	
end;
task.spawn(C_15);
-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
local function C_19()
local script = G2L["19"];
	script.Parent.MouseButton1Click:Connect(function()
		function oof()
			local Players = game:GetService("Players")
			local plr = Players.LocalPlayer
			local char = plr.Character or plr.CharacterAdded:Wait()
	
			-- by OutMoon R15 → R6
			if char:FindFirstChild("Humanoid") and char.Humanoid.RigType == Enum.HumanoidRigType.R15 then
				local desc = Players:GetHumanoidDescriptionFromUserId(plr.CharacterAppearanceId)
				local newChar = Players:CreateHumanoidModelFromDescription(desc, Enum.HumanoidRigType.R6)
				newChar.Name = plr.Name
	
				if not newChar.PrimaryPart and newChar:FindFirstChild("HumanoidRootPart") then
					newChar.PrimaryPart = newChar:FindFirstChild("HumanoidRootPart")
				end
				if newChar.PrimaryPart and char:FindFirstChild("HumanoidRootPart") then
					newChar:SetPrimaryPartCFrame(char.PrimaryPart.CFrame)
				end
	
				char:Destroy()
				newChar.Parent = workspace
				plr.Character = newChar
	
				local cam = workspace.CurrentCamera
				cam.CameraSubject = newChar:WaitForChild("Humanoid")
				cam.CameraType = Enum.CameraType.Custom
			end
	
			local c = workspace:WaitForChild(plr.Name)
			local Humanoid = c:WaitForChild("Humanoid")
			local pose = "Standing"
			local currentAnimTrack = nil
			local currentAnimSpeed = 1.0
	
			-- Animation assets R6
			local anims = {
				idle = "http://www.roblox.com/asset/?id=180435571",
				walk = "http://www.roblox.com/asset/?id=180426354",
				jump = "http://www.roblox.com/asset/?id=125750702",
				fall = "http://www.roblox.com/asset/?id=180436148"
			}
	
			-- Animation
			local function playAnim(animId, speed)
				if currentAnimTrack then
					currentAnimTrack:Stop()
					currentAnimTrack:Destroy()
				end
				local anim = Instance.new("Animation")
				anim.AnimationId = animId
				currentAnimTrack = Humanoid:LoadAnimation(anim)
				currentAnimTrack.Priority = Enum.AnimationPriority.Core
				currentAnimTrack:Play(0.1)
				if speed then
					currentAnimTrack:AdjustSpeed(speed)
				else
					currentAnimTrack:AdjustSpeed(1.0)
				end
			end
	
			-- Event functions
			Humanoid.Running:Connect(function(speed)
				if speed > 0.01 then
					playAnim(anims.walk, speed / Humanoid.WalkSpeed)
					pose = "Running"
				else
					playAnim(anims.idle)
					pose = "Standing"
				end
			end)
	
			Humanoid.Jumping:Connect(function()
				playAnim(anims.jump)
				pose = "Jumping"
			end)
	
			Humanoid.FreeFalling:Connect(function()
				if pose ~= "Jumping" then
					playAnim(anims.fall)
					pose = "FreeFall"
				end
			end)
	
			Humanoid.Died:Connect(function()
				pose = "Dead"
			end)
	
			-- Initialize idle
			playAnim(anims.idle)
			pose = "Standing"
		end
	
		oof()
	
		local UIS = game:GetService("UserInputService")
		local plr = game.Players.LocalPlayer
		local deathPos = nil
	
		plr.CharacterAdded:Connect(function(char)
			local hrp = char:WaitForChild("HumanoidRootPart")
			if deathPos then
				hrp.CFrame = deathPos
			end
		end)
	
		while true do wait(0.1)
			local char = plr.Character
			if char and char:FindFirstChild("Humanoid") then
				if char.Humanoid.Health <= 0 then
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if hrp then
						deathPos = hrp.CFrame
					end
				end
			end
		end
	
		UIS.InputBegan:Connect(function(input)
			if input.KeyCode == Enum.KeyCode.Insert and deathPos then
				local char = plr.Character
				if char and char:FindFirstChild("HumanoidRootPart") then
					char.HumanoidRootPart.CFrame = deathPos
				end
			end
		end)
	end)
end;
task.spawn(C_19);
-- StarterGui.ScreenGui.drag.Gui.Exe.TextButton.LocalScript
local function C_1d()
local script = G2L["1d"];
	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local ok = require(script.RE)
		ok.KillCharacter(player)
	end)
end;
task.spawn(C_1d);
-- StarterGui.ScreenGui.drag.Gui.Frame.EXE.LocalScript
local function C_25()
local script = G2L["25"];
	script.Parent.MouseButton1Click:Connect(function()
		local code = script.Parent.Parent.Parent.Exe.Field.Text
		local luaU = require(script.LauU)
		luaU.execute(code)
	end)
end;
task.spawn(C_25);
-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript
local function C_2a()
local script = G2L["2a"];
	script.Parent.MouseButton1Click:Connect(function()
		local clear = require(script.Clear)
		clear.Clear()
	end)
end;
task.spawn(C_2a);
-- StarterGui.ScreenGui.drag.Gui.Frame.TextButton.LocalScript
local function C_30()
local script = G2L["30"];
	script.Parent.MouseButton1Click:Connect(function()
		local ok = require(script.Inject)
		ok.Inject("SnoopyDooggy", game.ReplicatedStorage)
	end)
end;
task.spawn(C_30);
-- StarterGui.ScreenGui.drag.min.LocalScript
local function C_37()
local script = G2L["37"];
	local gui = script.Parent.Parent.Gui
	
	script.Parent.MouseButton1Click:Connect(function()
		gui.Visible = not gui.Visible
	end)
end;
task.spawn(C_37);
-- StarterGui.ScreenGui.drag.close.LocalScript
local function C_3e()
local script = G2L["3e"];
	local drag = script.Parent.Parent.drag
	
	script.Parent.MouseButton1Click:Connect(function()
		drag.Visible = false
	end)
end;
task.spawn(C_3e);

return G2L["1"], require;
