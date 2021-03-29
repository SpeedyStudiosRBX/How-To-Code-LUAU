# How-To-Code-LUAU

In this site, I will teach you how to code Lua(Luau) which is used for roblox!

------------------------------------------------------------------------------------

Our First Lesson : PRINT code.

Print is a command that creates a message in Output.
Print Command always comes with these brackets '('    ')'

Example :
print("I Love Roblox")

Expected Output Message :
I Love Roblox


local is a code that refers to something. <-- you know what i mean

local example = "Hello There"

print(example)

Expected Output Message :
Hello There

You can also do this :
print(example..example)

Output Message :
Hello ThereHello There

print(example.." "..example)

Output Message : 
Hello There Hello There

Lesson 1(a)
Leaderstats

leaderstats are stats, we all know that. But how do we make it?

Enter a script in SERVER SCRIPT SERVICE (It won't work anywhere else!)

game.Players.PlayerAdded:Connect(function() <-- Checks if there are players added to the server, and connects it to a function
   local leaderstats = Instance.new("Folder",player) <--creates a folder in the player
   leaderstats.Name = "leaderstats" <-- name of the folder
   
   local money = Instance.new("IntValue",leaderstats) <-- creates an interger value (stat) in the leaderstats folder
   money.Name = "Cash" <-- name of the stat
   money.Value = 500 <-- starter cash
end)


Lesson 1(b)
This is important in coding! This is what i call Family Code

We all know the explorer looked like this :

⛄ Snowman Model  <-- this is Snowman Body's Parent!
    ⛄ Snowman Body <-- this is Snowman Face & Nose's Parent!
         ⛄ Snowman Face & Nose <-- this is Snowman Body's Child! 
        
        
You can use :
script.Parent
script.Parent.Child2Example
   

This is just lesson 1. I won't go that deep into coding. Lesson 2 soon
