# Atividade: Pseudo-classes no formulário de contato
Nesta atividade você irá praticar um pouco os conceitos de **pseudo classes**.

Faça o clone deste repositório em sua máquina para que possa conhecer a estrutura e aplicar os conceitos.
        
## Passo a Passo

### Passo 1

Nesse primeiro passo vamos trabalhar os conceitos de **hover** em nosso formulário, para isso precisamos acessar a pseudo classe **placeholder** para replicar o efeito esperado.

#### Pseudo-classes utilizadas:

1. [Placeholder](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)
2. [Hover](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)

#### Propriedades css necessárias:

1. padding-left
2. [transition](https://www.w3schools.com/css/css3_transitions.asp)

#### Como aplicar:

```css
input:hover::placeholder {
    padding-left: 10px;
    -webkit-transition: all 0.4s;
    -o-transition: all 0.4s;
    transition: all 0.4s;
}
```

### Passo 2


Segundo passo, vamos trabalhar os conceitos de **focus** em nosso formulário, para isso precisamos acessar a pseudo classe **focus** para replicar o efeito esperado.

#### Pseudo-classes utilizadas:

1. [Focus](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus)
2. [Placeholder](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)

#### Propriedades css necessárias:

1. [Opacity](https://developer.mozilla.org/en-US/docs/Web/CSS/opacity)
2. [Transition](https://www.w3schools.com/css/css3_transitions.asp)

#### Tags onde aplicaremos:

1. Inputs
2. Textarea

### Passo 3

Terceiro passo, vamos trabalhar os conceitos de **valid** em nosso formulário, para isso precisamos acessar um elemento html para replicar o efeito esperado.

#### Pseudo-classes utilizadas:

1. [Valid](https://developer.mozilla.org/en-US/docs/Web/CSS/:valid)

#### Propriedades css necessárias:

1. background-color

#### Tags onde aplicaremos:

1. Inputs
