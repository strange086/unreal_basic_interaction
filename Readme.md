**Simple Interactive Door (Blueprint-Based)**

In this project, I created a basic door interaction system using only Blueprints in Unreal Engine—no coding needed!

When the player walks near the door, a trigger detects them and smoothly opens the door using a timeline animation. If they walk away or interact again, the door closes. I used a Lerp node inside a Timeline to handle the smooth rotation, and some simple logic to check if the door is already open or closed.

It’s simple, responsive, and a great starting point for more advanced interactions!

**How the Interactive Door Works**
The door setup uses Unreal Engine’s Blueprint system—a visual scripting tool. Here's how each part works:

->Trigger Box: Placed near the door, it detects when the player enters or exits.

->Timeline Node: Animates a smooth door movement over time.

->Lerp (Linear Interpolation): Used inside the Timeline to gradually rotate the door between closed and open positions.

->Bool Variable: Tracks whether the door is open or closed, so the system knows which action to perform.
