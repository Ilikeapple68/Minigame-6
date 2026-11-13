# MG6

1. I think the loop will happen once per update because update method run every frame, which means code inside the update method will run every when updated is called every frame. I think if a loop is too long it will make the game lag because the update method run every frame.

2. When player is jumping on platform it will teleports the player on mid way through. This is because when the player is still in mid air it makes the player's y velocity equals to 0. The code disables player's collider when y velocity is great than 0. Therefore when the player is in mid air, y velocity will goes back to 0 and enables the player's collider again which makes the player collide with the platform and teleports the player.
