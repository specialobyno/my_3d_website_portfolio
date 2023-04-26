yarn creat vite -- template react
yarn add tailwindcss
npx tailwindcss initi
yarn add --legacy-peer-deps @react-three/fiber @react-three/drei maath react-tilt react-vertical-timeline-component @emailjs/browser framer-motion react-router-dom three
zipped public folder
assets
components

find ./src/components -name "*.jsx" -exec sh -c 'mv "$0" "${0%.jsx}.tsx"' {} \;
find ./src/components -name "*.js" -exec sh -c 'mv "$0" "${0%.js}.ts"' {} \;

echo "# my_3d_website_portfolio" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/specialobyno/my_3d_website_portfolio.git
git push -u origin main