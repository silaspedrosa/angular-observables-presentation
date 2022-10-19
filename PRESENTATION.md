# Angular && Observables

## Introduction

Performance &
Elegância &
Possibilidades &
Matemática &
Mini-prova

### History

Do clááássico Gang of Four:
![GoF Cover](./presentation-assets/gof-cover.jpg)

![GoF](./presentation-assets/observer-pattern-gof.png)

[The Reactive Manifesto (2014)](https://www.reactivemanifesto.org/):
![reac](./presentation-assets/reactive-manifesto-complete.png)

![ReactiveX Project](./presentation-assets/reactivex.png)

![ReactiveX Project](./presentation-assets/reactivex-stuff-1.png)

![alt](./presentation-assets/iterator-pattern.png)

![ReactiveX Project](./presentation-assets/reactivex-stuff-2.png)

### Where is it used?

![Companies](./presentation-assets/where-used.png)

![Angular](./presentation-assets/angular.png)

### What Angular has to do with it?

![Angular & RxJS](./presentation-assets/rxjs-angular.png)

## Observables big picture

Streams?
Observables?

---

Tipo escalar, de boinha, normal e
tal:

```typescript
const x: 🍬 = 🍫
```

---

---

Array:

```typescript
const x: Array<🍬> = [🍫, 🍫, 🍫]
```

---

---

Stream?

```typescript
const x: Stream<🍬> = ❓
```

---

👯‍♂️ _Experimento paçoquita_ 👯‍♂️

### Analogias

Rio
![Rio péssima imagem](./presentation-assets/river.jpg)

- Intermitentes/Perenes
- Afluentes
- Precisa de uma nascente/fonte

---

Encanamento, Caixa d'água, pias
![Encanamento](./presentation-assets/encanamento.png)

- Consumers/Subscriptions
- Elemento central distribuidor
- Torneiras fechadas -> zero água
- Torneiras abertas e caixa d'água vazia -> zero fluxo
- async!

### Basic working

1. Source (`interval`, `of`, `from`)
1. Operators (`map`, `filter`, `take`, `skip`, `delay`, `debounce`, `tap`)
1. Consumer (`subscribe`)

## Experiment

### number -> even/odd -> filter odd (joke 13/22)

### boring

### number -> even/odd -> filter odd <= 13

### impossible

### number -> filter <= 13 -> even/odd

### boring, but ok

### number -> tap -> filter <= 13 -> even/odd

### number -> filter <= 13 tap -> -> even/odd

### number -> filter <= 13 -> even/odd -> tap

### (all with some fit person)

## Playground

## Login Form with Observables