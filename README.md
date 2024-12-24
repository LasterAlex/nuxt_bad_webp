# Webp is slower than png in nuxt-image???

Just run `pnpm install && pnpm run dev`, open `Network` tab inside of the console, and look to the load time of
http://localhost:3000/_ipx/_/fractal.webp and http://localhost:3000/_ipx/_/fractal.png

And it's not like the server can't serve images faster, http://localhost:3000/fractal.webp works perfectly fine.
