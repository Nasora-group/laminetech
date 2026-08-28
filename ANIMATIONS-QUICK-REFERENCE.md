# ⚡ Animations - Référence Rapide

## 🎬 Timeline des Animations au Chargement

```
0ms     : Page charge
│
├─ 100ms  : Nav glisse vers le bas (slideDown)
│
├─ 200ms  : Eyebrow s'affiche (fade-in-up)
│          Hero Card montée (fade-in-right)
│
├─ 300ms  : Titre se dessine (fade-in-up)
│          Description s'affiche (fade-in-up)
│
├─ 400ms  : Underline se déploie (expandWidth)
│          Boutons apparaissent (fade-in-up)
│
└─ 600ms  : Animation complète du héro

Durée totale : ~800ms (0.8 secondes) = très fluide
```

---

## 📍 Animations par Section

### 🏠 Navigation
| Élément | Animation | Durée | Trigger |
|---------|-----------|-------|---------|
| Nav bar | Slide down | 0.6s | Page load |
| Logo | Inclus dans nav | 0.6s | Page load |
| Menu links | Inclus dans nav | 0.6s | Page load |
| Buttons | Hover effect | 0.3s | Mouse enter |

---

### 🎯 Héro Section

| Élément | Animation | Durée | Délai | Trigger |
|---------|-----------|-------|-------|---------|
| Eyebrow | Fade-in-up | 0.8s | 0s | Load |
| H1 | Fade-in-up | 0.8s | 0.2s | Load |
| H1 span | Underline expand | 0.8s | 0.4s | Load |
| Description | Fade-in-up | 0.8s | 0.3s | Load |
| Buttons | Fade-in-up | 0.8s | 0.4s | Load |
| Hero Card | Fade-in-right | 0.8s | 0.2s | Load |
| Orbe arrière-plan | Float | 8s ∞ | - | Continu |

**Hover Effects:**
- Buttons : translateY(-2px) + glow
- Outline button : change de couleur

---

### 💼 Services Section

| Élément | Animation | Durée | Trigger |
|---------|-----------|-------|---------|
| Heading (h2) | Fade-in-up | 0.8s | Scroll reveal |
| Heading (p) | Fade-in-up | 0.8s | Scroll reveal (0.1s délai) |
| Carte 1 | Fade-in-up | 0.8s | Scroll (0.1s délai) |
| Carte 2 | Fade-in-up | 0.8s | Scroll (0.2s délai) |
| Carte 3 | Fade-in-up | 0.8s | Scroll (0.3s délai) |
| Carte 4 | Fade-in-up | 0.8s | Scroll (0.4s délai) |

**Hover Effects sur Cards:**
- Barre supérieure se déploie (scaleX 0→1)
- Élévation : translateY(-8px)
- Ombre augmente
- Bordure devient cyan
- Icon rotate(5deg) + scale(1.1)

---

### 🏆 Réalisations Section

| Élément | Animation | Durée | Trigger |
|---------|-----------|-------|---------|
| Heading (h2) | Fade-in-up | 0.8s | Scroll reveal |
| Heading (p) | Fade-in-up | 0.8s | Scroll reveal (0.1s délai) |
| Projet 1 | Fade-in-up | 0.8s | Scroll (0.1s délai) |
| Projet 2 | Fade-in-up | 0.8s | Scroll (0.2s délai) |
| Projet 3 | Fade-in-up | 0.8s | Scroll (0.3s délai) |

**Hover Effects sur Projects:**
- Élévation : translateY(-12px)
- Ombre forte : 0 25px 50px
- Bordure cyan
- Gloss effect sur projectTop

---

### 👥 À Propos Section

| Élément | Animation | Durée | Trigger |
|---------|-----------|-------|---------|
| Texte gauche | Fade-in-up | 0.8s | Scroll reveal |
| Heading | Fade-in-up | 0.8s | Scroll reveal |
| Paragraphes | Inclus | 0.8s | Scroll reveal |
| Feature 1 | Fade-in-up | 0.8s | Scroll (dans le texte) |
| Feature 2 | Fade-in-up | 0.8s | Scroll |
| Feature 3 | Fade-in-up | 0.8s | Scroll |
| Feature 4 | Fade-in-up | 0.8s | Scroll |
| Hero Card (droite) | Fade-in-up | 0.8s | Scroll reveal |
| Orbe arrière-plan | Float | 6s ∞ | Continu |

**Hover Effects sur Features:**
- Indent à droite : padding-left 20px → 28px
- Couleur cyan
- Arrow (✓) se rapproche

---

### 📞 Contact Section

| Élément | Animation | Durée | Trigger |
|---------|-----------|-------|---------|
| Contact Info (gauche) | Fade-in-up | 0.8s | Scroll reveal |
| Formulaire (droite) | Fade-in-up | 0.8s | Scroll reveal |
| Orbe arrière-plan | Float | 8s ∞ | Continu |

**Hover Effects:**
- Contact Info h2 : changement de couleur
- Links : underline qui se déploie

---

### 📋 Page Devis

| Élément | Animation | Durée | Délai | Trigger |
|---------|-----------|-------|-------|---------|
| Body (fade in global) | Fade in | 0.6s | 0s | Load |
| Top (logo + retour) | Slide down | 0.6s | 0s | Load |
| Box (formulaire) | Slide up | 0.6s | 0.2s | Load |
| Field 1 (name) | Fade-in-up | 0.6s | 0.1s | Load |
| Field 2 (email) | Fade-in-up | 0.6s | 0.2s | Load |
| Field 3 (phone) | Fade-in-up | 0.6s | 0.3s | Load |
| Field 4 (service) | Fade-in-up | 0.6s | 0.4s | Load |
| Field 5 (delay) | Fade-in-up | 0.6s | 0.5s | Load |
| Field 6 (budget) | Fade-in-up | 0.6s | 0.6s | Load |
| Field 7 (message) | Fade-in-up | 0.6s | 0.7s | Load |
| Actions (buttons) | Fade-in-up | 0.6s | 0.8s | Load |
| Note | Fade-in-up | 0.6s | 0.9s | Load |

**Hover Effects sur Inputs:**
- Focus : translateY(-2px) + glow cyan
- Border color cyan
- Box-shadow glow

**Hover Effects sur Budget Labels:**
- Background : #f8fafc → #e0f2fe
- Border cyan
- Text color → blue

---

## 🖱️ Animations Interactives

### Boutons (Tous)
```
Normal → Hover → Press
   ↓        ↓       ↓
  solid   glow +   active
          raise
```

**Dégradé inversé au hover** (effet "flip")
- Gradient initial : blue → cyan
- Gradient hover : cyan → blue
- Creates illusion of depth/push

### Liens
```
Normal   →   Hover
  |            |
text         text + underline qui pousse
             depuis la gauche
```

### Icônes (Services)
```
Normal  →  Hover
  |          |
size: 2rem  scale(1.1)
            rotate(5deg)
```

---

## 🎬 Scroll Reveal (Principal Magic ✨)

### Déclenchement
```javascript
if (elementTop < windowHeight * 0.85) {
  element.classList.add('active');
}
```
→ S'active quand l'élément entre dans 85% de la fenêtre

### Transformation
```css
.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}

.reveal.active {
  opacity: 1;
  transform: translateY(0);
}
```
→ L'élément monte et devient visible en 0.8s

### Stagger Effect
```css
.reveal-stagger.active > :nth-child(1) { transition-delay: 0.1s; }
.reveal-stagger.active > :nth-child(2) { transition-delay: 0.2s; }
.reveal-stagger.active > :nth-child(3) { transition-delay: 0.3s; }
.reveal-stagger.active > :nth-child(4) { transition-delay: 0.4s; }
```
→ Cascade progressif à l'écran

---

## 🔄 Animations Continues

### Float (Orbes en arrière-plan)
```
 0ms   →  3000ms  →  6000ms
  |         |         |
  ↑        ↓,→       ↑ (repeat)
high     middle    high

Dure 6-8 secondes, infini
```

### Bounce (WhatsApp Button)
```
 0ms   →  1000ms  →  2000ms
  |        |         |
  ↓       ↑         ↓ (repeat)
normal   raised    normal

Dure 2 secondes, infini
Arrête au hover
```

---

## 📊 Vue d'Ensemble (Timing Diagram)

```
                    HERO SECTION          SERVICES    PROJECTS    ABOUT/CONTACT
                    ════════════════      ════════    ════════    ═════════════
Load: 0ms           │
Load+100ms          ├─ Nav slide-down
Load+200ms          ├─ Eyebrow fade
                    ├─ Hero Card slide
Load+300ms          ├─ Title fade
                    ├─ Desc fade
Load+400ms          └─ Buttons fade
                        (section ready at 600-800ms)
                                                
Scroll to section...                    ↓
                                        All elements
                                        fade-in-up
                                        with 0.1-0.4s
                                        stagger
                                                        ↓
                                                    Same pattern:
                                                    fade-in-up
                                                    staggered

                                                            ↓
                                                        Same: fade-in-up
                                                        (left reveals first)
```

---

## ⚙️ Easing Functions Utilisées

| Function | Utilisation | Ressenti |
|----------|------------|----------|
| `ease-out` | Entrées (fade-in-up) | Naturel, rapide puis ralentit |
| `ease-in-out` | Boucles infinies (float) | Fluide, régulier |
| `cubic-bezier(0.23, 1, 0.32, 1)` | Scroll reveal (optionnel) | Super fluide, moderne |

---

## 🎯 Points Clés à Retenir

✅ **Au chargement** : Hero glisse/fade avec delais progressifs
✅ **Au scroll** : Sections révélées en cascade
✅ **Au hover** : Feedback immédiat (lift + glow)
✅ **En arrière-plan** : Orbes flottantes créent de l'ambiance
✅ **Total** : Expérience fluide, professionnelle, moderne

**Durée moyenne d'une animation** : 0.6s - 0.8s
**Responsive** : Oui, toutes les animations adaptées mobile
**Accessible** : Oui, respecte `prefers-reduced-motion`

---

Made with ✨ by Claude
