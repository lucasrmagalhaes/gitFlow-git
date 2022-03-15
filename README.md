**Git flow:** Um conjunto de extensões para o git que provê operações de alto-nível para repositórios usando o modelo de branches do Vicent Driessen.

**Inicializa o Git Flow:**
```
git flow init
```

**Inicializa uma nova Feature:**
```
git flow feature start sum
```

```
touch sum
git add .
git commit -m "add sum"
```

**Finaliza a Feature:**
```
git flow feature finish sum
```

```
git flow feature start sub
```

```
touch sub
git add .
git commit -m "add sub"
```

```
git flow feature finish sub
```

**Homologação:**
```
git flow release start 0.1.0
```

[Git - git flow na prática](https://www.youtube.com/watch?v=wzxBR4pOTTs&ab_channel=AngeloLuz)