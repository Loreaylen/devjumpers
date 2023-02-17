# GIT - GITHUB: Ejercitación final  

## Crear y clonar repositorio

```
git clone https://github.com/Loreaylen/devjumpers.git
cd devjumpers
```

## README, commit y push inicial

```
touch README.md
git status
git add .
git commit -m "commit inicial"
git push origin main
```

## Gitignore y archivos privados

```
touch .gitignore
touch privado.txt
mkdir privada
git add.
git commit -m "Se creó archivo gitignore"
```

## Crear ficheros, crear rama v0.2 y subir los cambios

```
touch 1.txt
git checkout -b v0.2
touch 2.txt
git add .
git commit -m "Creación de rama v0.2 y ficheros"
```

## Merge directo

```
git checkout main
git merge v0.2
git branch
git status
```

## Merge con conflicto

```
echo "hola" > 1.txt
git add .
git commit -m "Se agregó 'hola' a 1.txt"
git checkout v0.2
echo "adiós" > 1.txt
git add .
git commit -m "Se agregó 'adiós' a 1.txt"
git checkout main
git merge v0.2
```

## Listar ramas, areglar conflicto y borrar rama v0.2

```
git branch --merged
git branch --no-merged
code .
git status
git add .
git commit -m "Arreglando conflictos"
git status
git push origin main
git branch -d v0.2
git branch
```

## Listar cambios
```
git config --global alias.list 'log --oneline --decorate --graph --all'
git list
```
------------------------------------------------

## Doble factor de autentificación

## Crear una tabla 
| NOMBRE | GITHUB |
| --- | --- |
| Simón Santillán | [SimonSantillan](https://github.com/SimonSantillan) |
| Santiago Baliño| [Luvwen](https://github.com/Luvwen) |
| Valeria Zacarías| [valeriazacariasl](https://github.com/valeriazacariasl) |

## Colaboradores
