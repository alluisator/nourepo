---
title:
- Funcions en Python
autor:
- Lluís Giner
theme:
- Copenhagen
date:
- October 17, 2025

---

# FUNCIONS EN PYTHON

Imagina't que tens una tasca que has de fer repetidament, com ara sumar dos números, i vols una ma-nera fàcil de fer-ho sense haver d'escriure tot el codi cada vegada. Aquí és on entren en joc les funcions.

---
## Qué és una Funció

Les funcions són com petites màquines que construeixes per a fer una tasca específica. Un cop has creat una funció, pots utilitzar-la sempre que necessitis fer aquesta tasca. És com si escrivissis un llibre de receptes amb totes les instruccions per a fer diferents plats, i després només has de seguir aquestes instruccions cada vegada que vulgues cuinar.

---
## Funcions

### Exemple
1. **Crear la Funció:** Comences escrivint la "recepta". Això ho fas amb la paraula **def** (de definir), seguit del **nom** que li vols donar a la funció, i finalment, **entre parèntesis**, qualsevol ingredient (dades) que necessite la funció. Després, escrius les instruccions (codi) dins la funció (sense oblidar l'identació del seu bloc).

```python
def saludar(nom):
    print(f"Hola, {nom}!")
```
---
2. **Utilitzar la Funció:** Quan vols usar la funció, només has de cridar-la pel seu nom i donar-li els ingredients (dades) necessaris. És com agafar la recepta del llibre i seguir-la.

```python
saludar("Anna")** # Això imprimirà Anna a la terminal
```
---
3. **Avantatges:** La màgia de les funcions és que pots reutilitzar-les tantes vegades com vulguis sense haver de reescriure el mateix codi. Si vols saludar a algú altre, només cal donar-li un nou nom.

```python
saludar("Jordi") #Això imprimirà Jordi a la terminal
```
---
4. **Conclusió:** D'aquesta manera, les funcions ajuden a organitzar el codi i fan que siga més fàcil de llegir, mantenir i reutilitzar. És com tenir petites peces de Lego que pots combinar de diferents maneres per construir coses més grans i complexes. Això pot fer que el codi siga més eficaç i fàcil d'entendre.
   
---
### Exercicis de Funcions

1. Crear una funció que calcule l’àrea d’un rectangle donada la seua base i altura.
Ja caldria que coneguérem que l’àrea del rectangle es base per altura. Aleshores...

```python
def area_rectangle(base, alçada):
    print(f"Área del rectangle és: {base*alçada}")
# Quan volem calcular l'àrea...

area_rectangle(2,3)
Àrea del rectangle és: 6
```

---
2. Càlcul de la suma dels primers n nombres (naturals):

```python
def suma_nombres(n):
    return sum(range(1,n+1))

print(suma_nombres(5))
# I el resultat
15
```

