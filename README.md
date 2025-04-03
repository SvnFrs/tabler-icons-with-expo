# Somehow tabler icons react native does not work on my expo app

And the solution from [this repo](https://github.com/Foohx/tabler-icons-to-expo?tab=readme-ov-file) does not work for me.

So I copied the lastest *glyph-map.json* and *tabler-icons.ttf* from that repo and tried to fiddle with it.

## How to run

1. Install dependencies

   ```bash
   bun install
   ```

2. Start the app

   ```bash
    bun start
   ```

## How to use

Here is an example of how to use the icon component:
```
    <TablerIconComponent name="home" size={24} color="red" />
```
