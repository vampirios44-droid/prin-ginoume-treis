# Changelog

## v0.16 — Motion & Memory Audit

### Continuity / memory audit
- Έγινε δεύτερος έλεγχος του `index.html` απέναντι στο αρχικό Choice & Consequence Map.
- Διαπιστώθηκε ότι το hidden state ήταν σωστό, αλλά αρκετά long-term echoes δεν είχαν ορατό λογοτεχνικό callback.
- Προστέθηκαν 16 choice-dependent memory hooks χωρίς να εμφανίζονται A/B/C ή scores.
- Τα callbacks εμφανίζονται ως διακριτικό «Κάτι που έμεινε».
- Διατηρούνται τα υπάρχοντα unresolved-household και grandmother delayed echoes.
- Δεν αλλάζουν Choice IDs, effects, branch logic, Story Passport ή save schema.

### Motion & microinteractions
- Soft scene fade/slide σε κάθε αλλαγή οθόνης.
- Πολύ αργό cinematic settling στα chapter hero visuals.
- Staggered είσοδος των τριών choice cards.
- Branch reveal animation μετά την επιλογή.
- Micro-press feedback σε buttons/cards.
- Ομαλότερη κίνηση της progress line.
- Motion σε memory echoes, ending και Reflection Mirror.
- Πλήρης υποστήριξη `prefers-reduced-motion`.
- PWA cache bump σε `v0160`.
