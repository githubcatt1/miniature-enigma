# miniature-enigma
npm install -g typescript
npm install -g lerna
git clone git@github.com:howdyai/botkit.git
cd botkit
npm install
lerna bootstrap --hoist
lerna run build
lerna run build-docs
