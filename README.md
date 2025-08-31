# Aufgabe: v-if kennenlernen

Wir wollen eine Drawer- oder Collapsible-Komponente bauen.
Diese hat einen Titel, der immer sichtbar ist und ein body-teil, der ein- und ausgeblendet werden kann.

## Vorbereitung

```
npm create vue@latest aufgabe-vue-drawer
cd aufgabe-vue-drawer
npm install
npm run dev
```

Optional: Wähle TypeScript

## Drawer Komponente

1. Erstelle einen neuen Ordner `/src/components`
2. Lege eine neue Datei `/src/components/VueDrawer.vue` an

Vergiss nicht:

1. script-block mit lang="ts"
2. template-blocki
3. ref-Variable für den state
4. mit v-if elemente ein-/ausblenden
5. @click="funcName" um eine Funktion auszuführen

##HTML
Als Vorlage für das Template kannst du dieses HTML benutzen:

```HTML
<div>
    <h2>title</h2>
    <p>body</p>
</div>
```

## Style

Benutze dies für den Style-Block und benutze die CSS-Klassen

```css
.drawer {
    border: 1px solid #ccc;
    border-radius: 4px;
    margin: 1rem 0;
}

.drawer h2 {
    margin: 0;
    padding: 1rem;
    background: #f5f5f5;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
}

.drawer p {
    padding: 1rem;
    margin: 0;
}
```
