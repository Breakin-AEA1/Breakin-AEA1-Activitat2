# 🧱 Breakin · Mini-joc Scrum

> Projecte de l'**AEA1 · Activitat 2 · Metodologies** (Mòdul 0487 – Entorns de desenvolupament).
> Simulació d'un Sprint de Scrum gestionat amb **GitHub Projects (Kanban)** a partir del disseny d'un mini-joc tipus *Breakout*.

---

## Descripció del joc

**Breakout** és un joc arcade clàssic, publicat originalment per Atari el 1976. El jugador controla una **pala** situada a la part inferior de la pantalla i l'ha de fer servir per fer rebotar una **pilota** cap amunt, on hi ha diverses files de **maons** de colors. Cada cop que la pilota toca un maó, aquest es destrueix i el jugador guanya punts.

L'objectiu és **destruir tots els maons del nivell** sense deixar que la pilota caigui per sota de la pala. Si la pilota cau, el jugador perd una vida; quan es queda sense vides, la partida s'acaba.

### Objectiu
Eliminar tots els maons de la pantalla amb el mínim de vides perdudes i aconseguir la puntuació més alta possible.

### Elements del joc

| Element | Descripció |
|---|---|
|  **Pala** | Barra horitzontal que controla el jugador. Només es mou a esquerra i dreta. |
|  **Pilota** | Es mou automàticament i rebota contra les parets, la pala i els maons. |
|  **Maons** | Blocs disposats en files a la part superior. Desapareixen en ser tocats. Cada color pot donar una puntuació diferent. |
|  **Marcador** | Mostra la puntuació actual i les vides restants. |
|  **Vides** | El jugador comença amb 3 vides. Se'n perd una cada cop que la pilota cau. |

### Mecàniques principals
- La pilota **rebota** contra les parets laterals i la superior.
- Si la pilota cau per la part inferior, **es perd una vida**.
- L'**angle de rebot** depèn del punt de la pala on impacta la pilota (al centre surt més recta, als extrems més inclinada).
- Quan es destrueixen **tots els maons**, el jugador guanya el nivell.
- Quan les vides arriben a **0**, apareix la pantalla de **Game Over**.

### Controls

| Tecla | Acció |
|---|---|
| `←` / `A` | Moure la pala a l'esquerra |
| `→` / `D` | Moure la pala a la dreta |
| `Espai` | Llançar la pilota / començar |
| `P` | Pausar la partida |

### Pantalles
1. **Pantalla d'inici** – títol del joc i botó *Start*.
2. **Pantalla de joc** – pala, pilota, maons i marcador.
3. **Pantalla de victòria** – quan s'eliminen tots els maons.
4. **Pantalla de Game Over** – quan s'acaben les vides, amb opció de tornar a jugar.

---

##  Equip i rols Scrum

| Rol | Membre | Responsabilitats |
|---|---|---|
| **Product Owner** | Daniel Francisco | Gestiona i prioritza el Product Backlog, defineix el valor del producte i dona feedback a la Sprint Review. |
| **Scrum Master** | Laia Carrillo| Facilita els esdeveniments Scrum, vetlla pel procés i elimina els impediments de l'equip. |
| **Developer** | Laia Marin | Transforma les User Stories en tasques i les porta fins a *Done*. |
| **Developer** | Sergi Lopez | Transforma les User Stories en tasques i les porta fins a *Done*. |

---

## 🔗 Enllaços

- 📌 **GitHub Project:** 
- 🎨 **Prototip visual:** 

---

## 🛠️ Eines utilitzades

- **GitHub** – organització, repositori, issues i Projects
- **Canva** – prototip visual del joc
- **Scrum** – marc de treball àgil

---

_Projecte acadèmic · Mòdul 0487 · Curs 2026-2027_
