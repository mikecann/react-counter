# Modern React Counter

This was created to demonstrate how simple a modern React with TS app can be in response to @renatoathaydes's post: https://renato.athaydes.com/posts/comparing-jvm-alternatives-to-js.html

## Try It Out

Clone it then fire up your console and 

`yarn` or `npm install`

Then to start development just `yarn start` or `npm run start`

For an IDE I prefer VSCode.

## Method

I just fired open the console and typed

```
yarn create react-app my-app --typescript
```

Deleted some of the CSS and ts files for clarity.

Then started developing with 

```
yarn start
```

It has hot reload right out of the box (make a change and see)

When ready for production just 

```
yarn build
```

Follow the instructions if you want to serve.

Its 18 lines of code, when built its 36kb (gzipped) and scores a close to perfect score in lighthouse.