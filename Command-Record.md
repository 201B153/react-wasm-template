### Command ran on CLI to make the template working.

- For full description see the article @![How to create wasm-pack with react](ARTICLE_LINK)

 445  npx create-react-app react-wasm-tutorial
 446  cd react-wasm-tutorial 
 447  npm start
 450  cargo new wasm-lib --lib
 453  cargo test
 457  wasm-pack --version
 459  npm run build:wasm
 462  npm install ./wasm-lib/pkg