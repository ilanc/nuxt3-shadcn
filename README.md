# shadcn-vue + nuxt3

- guillaume duhan
    - [video 1](https://www.youtube.com/watch?v=azs0ov_SbOA&list=PL8HkCX2C5h0VHLeRYfYBmwNAEctlpIp4x)
    - [code](https://github.com/guillaumeduhan/nuxt3-shadcn)
- shadcn-vue mail example
    - [demo](https://www.shadcn-vue.com/examples/mail.html)
    - [code](https://github.com/radix-vue/shadcn-vue/tree/dev/apps/www/src/examples/mail)

added shadcn-vue mail example to guillaume app

```
cp -a /code/shadcn-vue/shadcn-vue/apps/www/src/examples/mail ./pages
cp -a /code/shadcn-vue/shadcn-vue/apps/www/src/lib/registry/ ./lib
cp -a /code/shadcn-vue/shadcn-vue/apps/www/src/lib/utils.ts ./lib
cp -a /code/shadcn-vue/shadcn-vue/apps/www/src/public/examples/ ./public/

yarn dev &
xdg-open http://localhost:3000/mail
```
