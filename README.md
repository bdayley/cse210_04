# Greed

Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more!

## Rules

Gems (*) and rocks (o) randomly appear and fall from the top of the screen.
The player (#) can move left or right along the bottom of the screen.
If the player touches a gem they earn a point.
If the player touches a rock they lose a point.
Gems and rocks are removed when the player touches them.
The game continues until the player closes the window.

## Project Structure

- Director
  - Methods:
    - start_game()
    - get_inputs()
    - do_updates()
    - do_outputs()

- Actor
  - Methods:
    - get_color()
    - get_font_size()
    - get_position()
    - get_text()
    - get_velocity()
    - move_next()
    - set_color()
    - set_position()
    - set_font_size()
    - set_text()
    - set_velocity()

- Artifact (Actor)
  - Methods:
    - get_message()
    - set_message()

- Cast
  - Methods:
    - add_actor()
    - get_actors()
    - get_all_actors()
    - get_first_actor()
    - remove_actor()

- Keyboard Service
  - Methods:
    - get_direction()

- Video Service
  - Methods:
    - close_window()
    - clear_buffer()
    - draw_actor()
    - draw_actors()
    - flush_buffer()
    - get_cell_size()
    - get_height()
    - get_width()
    - is_window_open
    - open_window()
    - draw_grid()
    
- Color
  - Methods:
    - to_tuple()

- Point
  - Methods:
    - add()
    - equals()
    - get_x()
    - get_y()
    - scale()

## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors

Carina Aguero (agu21022@byui.edu)\
Rob Cox (cox21008@byui.edu)\
Brianna Dayley (col04002@byui.edu)\
Anamilena Casariego (cas21052@byui.edu)\
Eduardo Pulido (pul21010@byui.edu)