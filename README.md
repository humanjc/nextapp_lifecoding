# youtube 생활코딩 X NEXT.js 강좌

https://www.youtube.com/playlist?list=PLuHgQVnccGMCwxXsQuEoG-JJ7RlwtNdwJ


# 현재 폴더에 앱 설치

```
npx create-next-app@latest .
```

npx create-next-app@latest .
√ Would you like to use TypeScript? ... <span style="color:red">No</span> / Yes  
√ Would you like to use ESLint? ... No / <span style="color:red">Yes</span>  
√ Would you like to use Tailwind CSS? ... No / <span style="color:red">Yes</span>  
√ Would you like your code inside a `src/` directory? ... No / <span style="color:red">Yes</span>  
√ Would you like to use App Router? (recommended) ... No / <span style="color:red">Yes</span>  
√ Would you like to use Turbopack for `next dev`? ... No / <span style="color:red">Yes</span>  
√ Would you like to customize the import alias (`@/*` by default)? ... No / <span style="color:red">Yes</span>  
Creating a new Next.js app in [folder]\nextapp.

Using npm.

Initializing project with template: app-tw 


Installing dependencies:
- react
- react-dom
- next

Installing devDependencies:
- @tailwindcss/postcss
- tailwindcss
- eslint
- eslint-config-next
- @eslint/eslintrc


added 399 packages, and audited 400 packages in 32s

166 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Initialized a git repository.

Success! Created nextapp at [folder]\nextapp

# DB 파일 생성

```
db.json
```

{
  "topics": [
    {"id": 1, "title": "html", "body": "html is ..."},
    {"id": 2, "title": "css", "body": "css is ..."}
  ]
}

# DB 서버 실행

```
npx json-server --port 9999 --watch db.json
```
