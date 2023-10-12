# PalletLoading Environment

This is a reinforcement learning environment for stacking rectangular boxes onto a single pallet floor.

## Action Space

An action is given as:

```
[ position_x, position_y, rotation ]
```

where:

- 'position_x' and 'position_y' should be given as normalized coordinates in [0, 1], representing the relative position on each x and y axis.
- 'rotation' is in {0, 1}. 0 means using the block as is, and 1 means placing the block after rotating it by 90 degrees. Default value is 0.
