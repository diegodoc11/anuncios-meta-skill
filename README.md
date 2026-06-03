# 🎯 Skill: Anuncios para Meta (guiones de video ads)

Una **skill para Claude Code** que genera bancos completos de **guiones de anuncios en video para Meta Ads (Facebook/Instagram)** — listos para grabar y pautar.

A partir de tu **oferta** y tu **avatar/cliente ideal**, crea **30 anuncios**, cada uno con:
- **4 variantes de gancho** para test A/B
- **cuerpo** persuasivo con elementos rotados (resultado soñado, pesadilla, causa de fracasos, etc.)
- **CTA** que cierra con el dolor o el sueño

Cubre los **5 niveles de conciencia**, rota fórmulas de gancho, y calibra la duración de cada anuncio a una velocidad real de habla (~187 palabras/min). Funciona para **cualquier nicho**: negocios, IA, estética/belleza, salud, seducción, coaching, e-commerce, servicios locales, etc.

> Creada por **Diego Osorio**.

---

## ✅ Requisito

Tener instalado **Claude Code** (la herramienta de terminal de Anthropic). Si aún no lo tienes, instálalo desde la web oficial de Anthropic y vuelve aquí.

---

## 📥 Cómo instalar la skill (paso a paso)

### Opción A — Descargar el ZIP (la más fácil, sin saber de programación)

1. En esta página de GitHub, haz clic en el botón verde **`Code`** ▸ **`Download ZIP`**.
2. **Descomprime** el archivo descargado.
3. Adentro vas a ver una carpeta llamada **`anuncios-meta`**. Cópiala completa.
4. Pégala dentro de tu carpeta de skills de Claude Code:
   - **Windows:** `C:\Users\TU_USUARIO\.claude\skills\`
   - **Mac / Linux:** `~/.claude/skills/`

   > 💡 Si la carpeta `.claude\skills` (o `~/.claude/skills`) no existe, créala. La carpeta `.claude` puede estar oculta: en Windows activa "Elementos ocultos" en el Explorador; en Mac usa `Cmd + Shift + .` para verla.

5. Al final debe quedar así:
   - **Windows:** `C:\Users\TU_USUARIO\.claude\skills\anuncios-meta\SKILL.md`
   - **Mac / Linux:** `~/.claude/skills/anuncios-meta/SKILL.md`
6. **Cierra y vuelve a abrir Claude Code.** ¡Listo!

### Opción B — Con Git (si sabes usar la terminal)

```bash
# Windows (PowerShell)
git clone https://github.com/diegodoc11/anuncios-meta-skill.git
Copy-Item -Recurse .\anuncios-meta-skill\anuncios-meta "$env:USERPROFILE\.claude\skills\anuncios-meta"

# Mac / Linux
git clone https://github.com/diegodoc11/anuncios-meta-skill.git
cp -r ./anuncios-meta-skill/anuncios-meta ~/.claude/skills/anuncios-meta
```

Reinicia Claude Code después de copiarla.

---

## 🚀 Cómo usarla

Abre Claude Code y simplemente pídele algo como:

> *"Créame anuncios para Meta de mi negocio."*
> *"Necesito guiones de video ads para [tu producto/servicio]."*

La skill se activa sola y te irá pidiendo lo que necesita:

1. **La oferta** — qué vendes y tu diferencial.
2. **El avatar** — tu cliente ideal con todos sus dolores, miedos y sueños (entre más detalle, mejores anuncios).
3. **El CTA** — a dónde lleva el botón (ver un video, agendar, registrarse, WhatsApp…). *Siempre te lo pregunta.*
4. **Marca y contexto** — nombre, y si es un negocio local, la ciudad.

Y te entrega el banco completo de 30 anuncios, listos para grabar.

> 💡 Consejo: mientras más crudo y específico sea el avatar (frases textuales que diría tu cliente, sus miedos reales, lo que ya intentó y no le funcionó), más potentes salen los anuncios.

---

## 📂 Qué incluye

```
anuncios-meta/
├── SKILL.md                          # El cerebro: flujo, reglas y calibración
└── references/
    ├── documento-base.md             # Metodología completa
    ├── banco-de-ganchos.md           # Librería de fórmulas de gancho + hooks virales
    ├── ejemplo-avatares-y-dolores.md # Ejemplo de avatar bien capturado
    ├── ejemplo-anuncios-ia.md        # 30 anuncios de ejemplo (negocios/IA)
    ├── ejemplo-anuncios-criolipolisis.md  # 30 anuncios de ejemplo (estética)
    └── ejemplo-anuncios-seduccion.md      # 30 anuncios de ejemplo (seducción)
```

---

## ❓ Problemas comunes

- **"No se activa la skill":** revisa que la ruta sea exactamente `.../.claude/skills/anuncios-meta/SKILL.md` y reinicia Claude Code.
- **"No veo la carpeta `.claude`":** está oculta. Actívala (Windows: ver "Elementos ocultos"; Mac: `Cmd + Shift + .`).

---

*Hecho con ❤️ para crear anuncios que venden.*
