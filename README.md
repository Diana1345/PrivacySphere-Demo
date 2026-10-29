# PrivacySphere

**Legea 195/2024 Compliance Suite**

PrivacySphere este o interfață enterprise, în limba română, pentru organizarea registrelor de conformitate GDPR și Legea 195/2024. Acest MVP rulează fără server și persistă datele în `localStorage`, fiind potrivit pentru prototipare și demonstrații locale.

## Rulare locală

Deschide `index.html` în browser sau servește directorul cu orice server static:

```bash
python3 -m http.server 8080
```

Accesează apoi `http://localhost:8080`.

După activarea GitHub Pages, aplicația poate fi accesată la:
`https://diana1345.github.io/PrivacySphere/`

## Module

- Registrul ROPA
- Jurnal de acces & audit
- Incidente de securitate, cu termen de 72 de ore
- Cereri DSAR, cu termen de 30 de zile
- Setări & administrare companie și utilizatori

Formularele din ROPA, Incidente și DSAR permit introducerea datelor și păstrează înregistrările în browserul utilizatorului (`localStorage`). Pentru utilizare multi-utilizator și date reale este necesar backend-ul descris mai jos.

> Pentru producție, autentificarea, RBAC-ul, sincronizarea în timp real și jurnalul imutabil trebuie conectate la un backend securizat, cu criptare, politici de retenție și audit extern.
PrivacySphere — suită de conformitate GDPR și Legea 195/2024 privind protecția datelor cu caracter personal.
