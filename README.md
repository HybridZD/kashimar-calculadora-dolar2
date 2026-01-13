# Asegúrate de estar en tu proyecto
cd /home/z/my-project

# Inicia git
git init

# Crea .gitignore si no existe
cat > .gitignore << 'EOF'
# dependencies
/node_modules
/.pnp
.pnp.js

# testing
/coverage

# next.js
/.next/
/out/

# production
/build

# misc
.DS_Store
*.pem

# debug
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# local env files
.env*.local

# vercel
.vercel

# typescript
*.tsbuildinfo
next-env.d.ts
EOF

# Agrega todo
git add .

# Commit inicial
git commit -m "Kamashir - Calculadora Dólar Oficial Venezuela"
