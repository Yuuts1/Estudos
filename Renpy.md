# Renpy Configuração e Comandos

### Comando de personagens

- Linha de código básica.

```
define e = character("name")

label start: 

  scene bgpark
  show name
  "Hello World"
  
  return
```

**define** = define um personagem

**character("name")** = define o nome do personagem

**label start** = indica o começo da linha de código

**scene** = define uma cena, background

**show** = define o personagem criado para execução no codigo

**""** = define as falas dos personagens

**return** = retorna a cena ou a linha de codigo inicial
