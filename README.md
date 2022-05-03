<h1 align="center">simpleTesterRepo</h1>


**NB:** This project is soley used to manually test a parser and a ESLint ruleplugin for a master's thesis at the IT University of Copenhagen and it should not be used for any other purpose 

## Installation

to install plugins parser and ruleset run:

```bash
npm i
```

## On changes to paser or rules:

### Parser
Any changes to the parser should be followed by the following:
inside the parser project run:
```bash
npm run build
```
this ensures that changes are reflected in the plugin 

inside this project run:
```bash
npm i
```

### Rules
Any changes to the terraform-rules project should be followed by the following:
inside the terraform-rules project run:

```bash
npm run build
```

this ensures that changes are reflected in the plugin 

inside this project run:

```bash
npm i
```
