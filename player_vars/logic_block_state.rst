(logic_block)_state
===================

*MPF player variable*

A dictionary that stores the internal state of the logic block
with the name (logic_block). (In other words, a logic block called
*mode1_hit_counter* will store its state in a player variable called
``mode1_hit_counter_state``).

The state that's stored in this variable include whether the logic
block is enabled and whether it's complete.

The actual value of the logic block is stored in another player
variable whose name you can specify via the ``player_variable:``
setting in the individual logic block config.

