<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/105825058/169174485-2f0666e4-d66a-43ef-865d-01ec5be1640f.png"/>
<h3 align="center" >THE MAGIC VUE 3 + VITE APP STARTER TEMPLATE IS A KICKSTARTER BOILERPLATE APPLICATION THAT SAVES TIME AND MONEY BY EXPEDITING DEVELOPMENT AND ELIMINATING IMPEDIMENTS</h3>
<img align="center" src="https://raw.githubusercontent.com/4dboard/proxy-yxorp/master/assets/logo.gif"/>  
</p>

# THE MAGIC VUE 3 + VITE APP

![image](https://user-images.githubusercontent.com/105825058/169175599-528fa64f-d8a0-4bc3-8c1f-cecb3117f628.png)

Using this template, getting started with Vue 3 in Vite should not provide too many obstacles. To calculate the total number of hovering occurrences, we employ a basic "magic" hover effect in conjunction with a hard feedback loop event counter.


![image](https://user-images.githubusercontent.com/105825058/169172279-0f1c19c0-e20c-448c-96c3-7fdfe20d8d02.png)


The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

![image](https://user-images.githubusercontent.com/105825058/169175709-e51df33c-5ae0-47e4-94bd-c12da7bbe1cd.png)

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

TypeScript and Vue coexist Static analysis in a type system like TypeScript may discover a variety of typical development issues. As a consequence, we may rewrite code in large-scale systems with more confidence and lower chance of runtime errors. TypScript's type-based auto-completion enhances the ergonomics of integrated development environments for developers significantly (IDEs). Vue is a TypeScript-based framework that fully supports TypeScript. All official Vue packages should provide type declarations that work right away. Vite and TypeScript can now be used to build Vue using an official project scaffolding tool. 

Create-Vue# Project Setup Overview The dev server and bundler in a Vite-based system just do compilation and no type verification. The use of TypeScript on the Vite development server improves its performance. To gain rapid feedback on type problems while creating, we recommend utilizing a high-quality Integrated Development Environment (IDE) (IDE). When employing SFCs, use the vue-tsc tool for command-line type checking and type declaration construction. 

The TypeScript command line interface is wrapped by vue-tsc. It is similar to tsc in that it supports TypeScript and Vue SFC files. Vue-tsc does not currently support Watch mode, but it will do so shortly. Meanwhile, use vite-plugin-checker to validate the type of your dev command. Vue CLI also supports TypeScript, however its use is no longer recommended. Notes are provided below. Because of its outstanding TypeScript support out of the box, Visual Studio Code (VSCode) comes highly recommended. TypeScript support for Vue SFCs is also given. Volar is a certified VSCode extension with a slew of additional noteworthy features. TIP Volar has taken the position of Vetur, the previous official VSCode plugin for Vue 2. Vetur must be disabled if it is already installed before Vue 3 can be utilized. Type support for *.vue imports inside TS files is also provided by the TypeScript Vue Plugin. TypeScript and Vue are pre-integrated in WebStorm. 

Their usage is allowed through a free plugin or as a built-in feature in other JetBrains integrated development environments (IDEs). tsconfig.json# The tsconfig.json configuration for Create-Vue-Scaffolded applications is preset. A configuration abstraction is provided by @vue/tsconfig. We use Project References to ensure that code executed in several contexts is of the right type (e.g. app vs. test). When manually configuring tsconfig.json, the following arguments are available: compilerOptions.isolated Modules is set to True due to esbuild's constraints on single-file TypeScript transpilation. CompilerOptions.strict must be enabled (or at least activated). compilerOptions.noImplicit When the Options API is used with component options, this element of the strict flag facilitates type verification. As a result, this case will be treated in the same manner as any other. Set resolver aliases for TypeScript using compilerOptions.paths if your build tool already has them specified, such as the alias that comes with a create-vue project.
 
## Who maintains Vue?

![image](https://user-images.githubusercontent.com/105825058/169175868-ef9cc58c-364e-4be6-9c11-db3f934fe111.png)

Vue is a community-driven, open-source software project that is self-funded. In 2014, Evan You began working on it as a personal side project in his free time. Vue is now being maintained by a diverse group of individuals from all around the world, both as paid employees and as unpaid volunteers. Evan is in charge of supervising the project. In this video, the history of Vue is broken down into its component parts and analyzed in further detail.

Since 2016, Vue has been able to sustain its own financial health mostly because to the assistance of its sponsors, who have allowed the organization to expand its activities. If you or your organization feel Vue will be important in the future, please consider contributing to its continuous development.
