# potion-shop

This is edited from Christine Pinto's potion shop.
Deployed at https://qe-at-cgi-fi.github.io/potion-shop/

## Add playwright agents and skills

npm init playwright@latest
npx playwright init-agents --loop=vscode

npx playwright-cli
playwright-cli install --skills

## Add agentic-qe-fleet

npm install -g agentic-qe
aqe init --auto --with-copilot
