<h1>Snippets</h1>

<p>Para utilizar, coloque estas configurações dentro do arquivo aquivo global de snippets, que pode ser acessado da seguinte forma:</p>

```bash
Aperte CTRL + SHIFT + P para acessar a Paleta de Comandos
Busque por:

Snippets: Configurar Snippets de Usuário
Snippets: Configure User Snippets

Caso já tenha um arquivo global, basta adicionar o código abaixo a ele.
Caso não tenha, clique na segunda opção para criar um e cole o código abaixo.
```

```json
{
	"Criar função js/ts": {
		"prefix": "cfn",
		"scope": "javascript,typescript,javascriptreact,typescriptreact",
		"body": [
			"function ${1:nomeFuncao}() {",
			"\t${0:}",
			"}"
		],
		"description": "Criar nova função básica em javascript e/ou typescript"
	},

	"Criar função assíncrona js/ts": {
		"prefix": "cafn",
		"scope": "javascript,typescript,javascriptreact,typescriptreact",
		"body": [
			"async function ${1:nomeFuncao}() {",
			"\t${0:}",
			"}"
		],
		"description": "Criar nova função assíncrona em javascript e/ou typescript"
	},

	"criar função de controller do fastify": {
		"prefix": "ccff",
		"scope": "javascript,typescript",
		"body": [
			"export async function ${1:nome}(request: FastifyRequest, response: FastifyReply) {",
			"\t${0:}",
			"}"
		],
		"description": "Cria uma função assíncrona para um controller no Fastify"
	},

	"criar componente react": {
		"prefix": "ccp",
		"scope": "javascriptreact,typescriptreact",
		"body": [
			"export function ${1:nomeComponente}() {",
			"\treturn (",
			"\t\t${0:}",
			"\t)",
			"}"
		]
	},

	"criar page next": {
		"prefix": "cnp",
		"scope": "javascriptreact,typescriptreact",
		"body": [
			"export default function Page() {",
			"\treturn (",
			"\t\t<main>",
			"\t\t\t${0:}",
			"\t\t</main>",
			"\t)",
			"}"
		]
	},

	"criar media-queries": {
		"prefix": "cmq",
		"scope": "css,sass,scss,tailwindcss",
		"body": [
			"@media only screen and (max-width: ${1:size}px) {",
			"\t${0:}",
			"}"
		]
	},

	"criar useEffect": {
		"prefix": "cuf",
		"scope": "javascriptreact,typescriptreact",
		"body": [
			"useEffect(() => {",
			"\t${0:}",
			"}, [])"
		]
	}
}
```