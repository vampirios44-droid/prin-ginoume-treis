# Πριν γίνουμε τρεις
## Interactive Web-Book — GitHub → Netlify

### Repository structure
Όλα τα αρχεία του site βρίσκονται στη ρίζα του repository. Δεν υπάρχει build step.

### Production workflow

`development`
→ νέα έκδοση / δοκιμές
→ Netlify Branch Deploy ή Deploy Preview
→ έλεγχος σε desktop + iPhone Safari
→ merge στο `main`
→ Netlify production deploy
→ **ίδιο production URL**

### Netlify setup
1. Netlify → **Add new project** → **Import an existing project**.
2. Git provider: **GitHub**.
3. Επίλεξε αυτό το repository.
4. Production branch: `main`.
5. Build command: άδειο.
6. Publish directory: `.`.
7. Publish.

Το `netlify.toml` στη ρίζα δηλώνει ήδη `publish = "."`.

### Κάθε νέα έκδοση
Δεν κάνουμε νέο Netlify site και δεν αλλάζουμε link.
Ανεβάζουμε/κάνουμε commit τα νέα αρχεία στο GitHub:
- πρώτα στο `development` για δοκιμή,
- μετά merge στο `main`.

Το Netlify ανανεώνει αυτόματα το production site.

### iPhone
Το interactive βιβλίο πρέπει να ανοίγει από το HTTPS Netlify URL στο Safari.
Δεν χρησιμοποιούμε το local `.html` μέσω Files/Quick Look για λειτουργικό test.

Μετά:
Safari → Share → **Add to Home Screen**.

### Story Passport
Τα `.ogmstory` αρχεία παραμένουν φορητά και δεν εξαρτώνται από το Netlify URL.
Development branch test.
