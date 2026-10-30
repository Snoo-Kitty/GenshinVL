# GenshinVL
The compilation of genshin character's voicelines included in the "Voice lines" section of the character menu ingame. Sourced from the genshin wiki.
# Format
```typescript
interface data {
    character: string,
    sections: {
        Story: {[dialogueAbout: string]: string},
        Combat: {[dialogueAbout: string]: string | string[]},
    }
}
```