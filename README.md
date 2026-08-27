# Fundamentos de IA e LLMs para Programadores

Repositório de estudos da disciplina **Fundamentos de IA e LLMs para Programadores** (pós-graduação), com exemplos práticos.

## Estrutura

```
exemplo-00-template/   # Rede neural simples com TensorFlow.js
exemplo-01-template/   # Sistema de recomendações de e-commerce com TensorFlow.js
```

Cada exemplo é independente, com seu próprio `package.json`.

## Exemplo 00 — Template

Rede neural simples (usando [@tensorflow/tfjs](https://www.tensorflow.org/js)) que classifica uma pessoa em uma categoria (`premium`, `medium` ou `basic`) a partir de idade, cor e localização.

### Rodando o exemplo

```bash
cd exemplo-00-template
npm install
npm start
```

## Exemplo 01 — Recomendações de E-commerce

Sistema de recomendações que treina um modelo em tempo real no navegador (com [tfjs-vis](https://www.tensorflow.org/js) para visualizar precisão/erro do treinamento) a partir do perfil e histórico de compras do usuário.

### Rodando o exemplo

```bash
cd exemplo-01-template
npm install
npm start
```

Abre em `http://localhost:3000`.

## Requisitos

- Node.js
- npm
