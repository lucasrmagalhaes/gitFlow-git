**Git flow:** Um conjunto de extensões para o git que provê operações de alto-nível para repositórios usando o modelo de branches do Vicent Driessen.

```
git flow init
```

```
git flow feature start sum
```

```
touch sum
git add .
git commit -m "add sum"
```

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

[Git - git flow na prática](https://www.youtube.com/watch?v=wzxBR4pOTTs&ab_channel=AngeloLuz)