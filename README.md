# sapper-v3

Modified v2 sapper template to work with Svelte 3.

Note: Right now, sapper seems to expect a preload function to be exported from every route, it will still work without one but it will give you warnings. You can just `return` nothing from preload to silence it.

To clone it and get started:

```bash
npx degit pngwn/sapper-v3 my-app
cd my-app
npm install # or yarn!
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.

