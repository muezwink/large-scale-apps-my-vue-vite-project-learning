# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur

- Use [vue-tsc](https://github.com/vuejs/language-tools/tree/master/packages/tsc) for performing the same type checking from the command line, or for generating d.ts files for SFCs.

#Chapter 1 - Setting Up The Project
C:\projects>git clone https://github.com/muezwink/large-scale-apps-my-vue-vite-project-learning.git
Cloning into 'large-scale-apps-my-vue-vite-project-learning'...
warning: You appear to have cloned an empty repository.

C:\projects>cd large-scale-apps-my-vue-vite-project-learning

C:\projects\large-scale-apps-my-vue-vite-project-learning>dir
 C 드라이브의 볼륨에는 이름이 없습니다.
 볼륨 일련 번호: 5C34-94D3

 C:\projects\large-scale-apps-my-vue-vite-project-learning 디렉터리

2024-04-19  오후 03:14    <DIR>          .
2024-04-19  오후 03:14    <DIR>          ..
               0개 파일                   0 바이트
               2개 디렉터리  808,947,847,168 바이트 남음

C:\projects\large-scale-apps-my-vue-vite-project-learning>git init
Reinitialized existing Git repository in C:/projects/large-scale-apps-my-vue-vite-project-learning/.git/

C:\projects\large-scale-apps-my-vue-vite-project-learning>git branch -M main

C:\projects\large-scale-apps-my-vue-vite-project-learning>git remote add origin https://github.com/muezwink/large-scale-apps-my-vue-vite-project-learning.git
error: remote origin already exists.

C:\projects\large-scale-apps-my-vue-vite-project-learning>code .

C:\projects\large-scale-apps-my-vue-vite-project-learning>npm init vite@latest
√ Project name: ... vite-project
√ Select a framework: » Vue
√ Select a variant: » TypeScript

Scaffolding project in C:\projects\large-scale-apps-my-vue-vite-project-learning\vite-project...

Done. Now run:

  cd vite-project
  npm install
  npm run dev


C:\projects\large-scale-apps-my-vue-vite-project-learning>cd vite-project

C:\projects\large-scale-apps-my-vue-vite-project-learning\vite-project>npm install

added 45 packages, and audited 46 packages in 9s

5 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\projects\large-scale-apps-my-vue-vite-project-learning\vite-project>

#Chapter 2 - Your First Component
