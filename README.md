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

<div align="center">
  <img src="https://i.imgur.com/sEB4247.png" alt="Clonar repo y agregar README" style="width: 50%; height: auto;">
  <img src="https://i.imgur.com/CaWDvRC.png" alt="Commit y primer push" style="width: 50%; height: auto;">
</div>

## Gitignore y archivos privados

```
touch .gitignore
touch privado.txt
mkdir privada
git add.
git commit -m "Se creó archivo gitignore"
```
<div align="center">
  <img src="https://i.imgur.com/XO4TMPx.png" alt="Creando gitignore y archivos privados" style="width: 50%; height: auto;">
</div>

## Crear ficheros, crear rama v0.2 y subir los cambios

```
touch 1.txt
git checkout -b v0.2
touch 2.txt
git add .
git commit -m "Creación de rama v0.2 y ficheros"
```

<div align="center">
  <img src="https://i.imgur.com/zzgm5JP.png" alt="Crear ficheros, crear rama v0.2 y subir los cambios" style="width: 50%; height: auto;">
</div>

## Merge directo

```
git checkout main
git merge v0.2
git branch
git status
```

<div align="center">
  <img src="https://i.imgur.com/meWm0vz.png" alt="Merge directo" style="width: 50%; height: auto;">
</div>

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

<div align="center">
  <img src="https://i.imgur.com/27ookc3.png" alt="Merge con conflicto" style="width: 50%; height: auto;">
</div>

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
<div align="center">
  <img src="https://i.imgur.com/t6mf1qg.png" alt="Listado de ramas" style="width: 50%; height: auto;">
  <img src="https://i.imgur.com/lLZmjR6.png" alt="Arreglando conflictos" style="width: 50%; height: auto;">
  <img src="https://i.imgur.com/ecSsPPM.png" alt="Borrar rama" style="width: 50%; height: auto;">
</div>

## Listar cambios
```
git config --global alias.list 'log --oneline --decorate --graph --all'
git list
```
<div align="center">
  <img src="https://i.imgur.com/xXWshLl.png" alt="Listado de cambios" style="width: 50%; height: auto;">
</div>
------------------------------------------------

## Doble factor de autentificación

<div align="center">
  <img src="https://i.imgur.com/ANuDjn6.png" alt="doble autenticación" style="width: 50%; height: auto;">
  <img src="https://i.imgur.com/X30ZwuM.png" alt="doble autenticación" style="width: 50%; height: auto;">
</div>

## Crear una tabla 
| NOMBRE | GITHUB |
| --- | --- |
| Simón Santillán | [SimonSantillan](https://github.com/SimonSantillan) |
| Santiago Baliño| [Luvwen](https://github.com/Luvwen) |
| Valeria Zacarías| [valeriazacariasl](https://github.com/valeriazacariasl) |

## Colaboradores
<div align="center">
  <img src="https://i.imgur.com/stEQeEh.png" alt="Colaboradores" style="width: 100%; height: auto;">
</div>
