# odin-recipes

This is my first attempt at making a recipes collection page. WARNING! It will probably be the ugliest thing you've laid eyes on. Viewer discretion is advised.

## Skills I will have demonstrated once I'm done:

- Basic HTML elements
- Git command line

## Self-reflection:

I learned:

- That `git add .` starts at the current folder and works into each sub-folder as appropriate. But it does not go _up_
- `p >lorem` not `p{lorem}`
- I don't know how to use the command line to make duplicate copies of my original file and save it as two seperate files in the same directory.

Tried `cp simmered_fruit.html meat_and_mushroom_skewer.html basic_meaty_rice_balls.html`
Error `cp: target 'basic_meaty_rice_balls.html' is not a directory`.

Tried `cp simmered_fruit.html recipes/meat_and_mushroom_skewer.html recipes/basic_meaty_rice_balls.html`
Error `cp: target 'recipes/basic_meaty_rice_balls.html' is not a directory`.

Tried `cp simmered_fruit.html /recipes/meat_and_mushroom_skewer.html /recipes/basic_meaty_rice_balls.html`
Error `cp: target '/recipes/basic_meaty_rice_balls.html' is not a directory`.

I just used VScode to duplicate the file and proceeded from there.

I think my error is that I tried to do two things at once as `cp simmered_fruit.html test1.html && cp simmered_fruit.html test2.html` works fine. Next time, I'm copy one at a time.

- I was in a subdirectory when I added and committed so I Google and found that `git reset --soft HEAD~1` will undo that. Now I can `git add .` and commit again

## New hotkeys:

- Change all occurrences: ctrl + f2
