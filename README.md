# Obsidian Git - Mobile Compatable
A fork / simplification of the project to bring the obsidian-git plugin to mobile. Based off of the **mobile** branch of [obsidian-git](https://github.com/denolehov/obsidian-git).

Currently, the mobile branch version does not appear to be actively worked on & requires some work to get it actually working on mobile.

In reality all I really did here was make some slight modifications to already existing code, but I think they are worth sharing so nobody else has to spend many hours scouring the internet for how to get this to work.

## Releases
**TODO**: Coming Soon

## Building
0) Install node, and run `npm i`.
1) Run `npm run build`. This will generate the `main.js` plugin script.
2) Manually create a plugin file in your vault called `obsidian-git-mobile`.
3) Copy over the generated `main.js` and `manifest.json` to the newly created plugin directory.