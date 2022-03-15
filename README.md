**Git flow:** Um conjunto de extensões para o git que provê operações de alto-nível para repositórios usando o modelo de branches do Vicent Driessen.

**Inicializa o Git Flow:**
```
git flow init
```

**Inicializa uma nova Feature:**
```
git flow feature start nova-feature
```

```
touch arquivo
git add .
git commit -m "add arquivo"
```

**Finaliza a Feature:**
```
git flow feature finish nova-feature
```

**Homologação:**
```
git flow release start 0.1.0
```
```
git flow release finish 0.1.0
```

[Git - git flow na prática](https://www.youtube.com/watch?v=wzxBR4pOTTs&ab_channel=AngeloLuz)
