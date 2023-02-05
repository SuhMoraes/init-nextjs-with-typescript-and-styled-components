# Configuração para ser utilizadas em projetos NextJS com Typescript e Styled Components.

Configuração padrão, mas ensinarei como montar essa config, caso tenha interesse.

> Installing dependencies:
- react
- react-dom
- next
- @next/font
- typescript
- @types/react
- @types/node
- @types/react-dom
- eslint
- eslint-config-next

---------------------------
## Step by Step

 1. No terminal de sua escolha, entre na pasta do seu projeto e digite:
	  ` npx create-next-app `
	  
 2. Após rodar o comando, defina o padrão do seu projeto.
- ✔What is your project named? … config-next
- ✔ Would you like to use TypeScript with this project? … No / Yes
- ✔ Would you like to use ESLint with this project? … No / Yes
- ✔ Would you like to use `src/` directory with this project? … No / Yes
- ✔ Would you like to use experimental `app/` directory with this project? … No / Yes
- ✔ What import alias would you like configured? … @/*
	

>  *Essas foram as definições do meu projeto*
  

3. Rode o comando: `npm run dev`

  

 4. Editando o EditorConfig


    4.1 Instale a extension EditorConfig

    ![File, type, editorconfig Icon in vscode](data:image/png;base64,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)

    4.2 Na Raiz do projeto, cliquei do lado direito e escolha a opção *Generate .editorconfig*
	Será gerado na raiz do projeto  .editorconfig, com as configuração padrão
	
````
	# EditorConfig is awesome: https://EditorConfig.org

	# top-most EditorConfig file
	root = true

	  

	[*]
	indent_style = space
	indent_size = 4
	end_of_line = lf
	charset = utf-8
	trim_trailing_whitespace = true
	insert_final_newline = true
```````

