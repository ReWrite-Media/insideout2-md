### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Build Your Joy

## Step 1
Help Riley by instructing the Mind Worker to collect each item that brings her joy. Use the ``||agent.agent move()||`` block to navigate the Mind Worker around. Make sure the Mind Worker walks through each of the three items.

#### ~ tutorialhint 
The most direct path involves moving the Mind Worker ``||agent.forward 2||``, ``||agent.left 3||``, ``||agent.forward 4||``, and ``||agent.right 2||``.


```ghost
    agent.move()
    agent.turn()
```
```template
    agent.move(FORWARD, 1)
    agent.move(LEFT, 1)
    agent.move(FORWARD, 1)
    agent.move(RIGHT, 1)
```