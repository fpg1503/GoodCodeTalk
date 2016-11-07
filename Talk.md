![fit inline](logo-cocoa-heads.gif)

# CocoaHeads Conf

## *Francesco Perrotti-Garcia*

---

#[fit] *What's* good code*?*

# *and*

#[fit] **How do I write it**

---

![left](gravatar.jpg)
#[fit] *Francesco* 
#[fit] *Perrotti-Garcia*
#[fit] iOS Developer
#[fit] **_@fpg1503_**

---

# TODO: Intro

---

#[fit] 2 tipos

---

#[fit] > isolado

---

#[fit] > integrado

---

# TODO: Isolado

---

#[fit] > integrado

---

#[fit] Protocolos

---

#[fit] `protocol`s

---

#[fit] Protocolos

---

#[fit] Protocolo
#[fit] grego: `πρωτόκολλον`
#[fit] latim: `Protocollum`

---

#[fit] >> 😂😂 <<

---

#[fit] Wikipedia

---

## `- Etiqueta`
## `- Diplomacia`
## `- Política`

---

## `- Ciência`
## `- Medicina`
## `- Comunicações`
## `- Criptografia`

---

#[fit] Protocolo
#[fit] **social**

---

#[fit] Estabelecimento
#[fit] de canal

---

#[fit] >> 👷🏻‍♀️🎅🏿 <<

---

#[fit] >> 🗣💬 <<

---

## > 👷🏻‍♀️: `Oi`
## > 🎅🏿: `Oi`

---

## > 👷🏻‍♀️: `Tudo bem?`

---

#[fit] 🎅🏿💭

---

#[fit] 🚸🎁 🇨🇳

---

#[fit] 💵⛽️📈

---

#[fit] 💸😰🎄

---

#[fit] 🤔🤔🤔
 
---

## > 🎅🏿: `Tudo ótimo!`
## > `E você?`

---

## > 👷🏻‍♀️: `Também!`
## > 🎅🏿: `Que bom!`

---

## > 👷🏻‍♀️: `<Fim>`
## > 🎅🏿: `<Fim>`

---

#[fit] Estabelecimento
#[fit] de canal

---

#[fit] O que é um
#[fit] **protocolo**?

---

#[fit] Acordo

---

#[fit] Conjunto de
#[fit] **Regras**

---

#[fit] **Facilitar**
#[fit] as coisas

---

#[fit] >> 🐥 

---

#[fit] `(Sim, isso é um pato)`

---

#[fit] Eu quero
#[fit] **um pato**!

---

#[fit] Para que?

---

#[fit] **Purpose**?

---

# TODO: Gif Purpose

---

#[fit] Para que
#[fit] um **pato**?

---

#[fit] Patos fazem
#[fit] **quack**

---

#[fit] Você **não** quer
#[fit] um pato!

---

#[fit] Algo que faça
#[fit] **quack**

---

#[fit] Modelando
#[fit] meu **pato**

---

#[fit] Abordagem
#[fit] *"clássica"*

---

```swift
class Duck: Animal {
	func quack() {
		print("Quack, quack!")
	}
}
```

---

```swift
let myDuck = Duck(...)
myDuck.quack()
```

---

#[fit] Quackable

---

```swift
protocol Quackable {
	func quack()
}
```

---

```swift
let myQuackable = ...
myQuackable.quack()
```

---

#[fit] **S**OLID

---

(...)
# TODO: Desacoplamento usando protocolos
# TODO: Todo ViewController deveria ter um `delegate`

---

(...) Teste

---

#[fit] `public`
#[fit] **deve** ser testada

---

#[fit] Cobertura de teste
#[fit] **deve** ser 100%

---

#[fit] Componentes conversam
#[fit] pela interfaces

---

#[fit] SOLI**D**

---

#[fit] What is
#[fit] **code coverage**?

---

#[fit] Code Coverage

^ In computer science, code coverage is a measure used to describe the degree to which the source code of a program is executed when a particular test suite runs.

---

#[fit] De duas uma:

---

#[fit] Falta teste

---

#[fit] Sobrou código

---

#[fit] Falta teste:
#[fit] Adicionar mais testes

---

#[fit] Sobrou código:
#[fit] Apagar código inútil

---

#[fit] 🚨 **Não** 🚨
#[fit] saia apagando
#[fit] qualquer coisa!

---

#[fit] Partial functions

---

#[fit] Matt Gallagher
#[fit] @cocoawithlove

---

#[fit] TL;DR

---

#[fit] Go

---

#[fit] go-proverbs.github.io
#[fit] @rob_pike 

---

#[fit] The **bigger** the interface,
#[fit] the *weaker* the abstraction.

---

#[fit] Quanto **maior** o
#[fit] **`protocol`**
#[fit] *menor* a abstração

---

#[fit] SOL**I**D

---

#[fit] optional 
#[fit] protocol
#[fit] requirements

---

#[fit] opcional
#[fit] ==
#[fit] facultativo

---

#[fit] > Swift tem um **bug**!

---

#[fit] > `@objc`

---

#[fit] 👎👎🏿👎🏻👎🏾👎🏼👎🏽

---

#[fit] Se é **opcional**
#[fit] deveria fazer parte
#[fit] do protocolo?

---

#[fit] `interface{}` 
#[fit] says **nothing**.

---

#[fit] `protocol<>` 
#[fit] não diz **nada**.

---

#[fit] `protocol<>`
#[fit] ==
#[fit] `Any`

---

#[fit] Protocolos estão
#[fit] no core de Swift

---

#[fit] Types matter

---

#[fit] Type safety
