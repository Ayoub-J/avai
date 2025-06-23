# Politique de contribution – Avai

Merci de votre intérêt pour contribuer au projet **Avai** !

## Branches principales

- `main` : branche de production — **aucun commit ou PR direct autorisé**
- `dev` : branche de préproduction — **seulement via PR depuis des branches de travail**

## Workflow de contribution

1. **Forkez** le dépôt (si externe)
2. **Créez une branche** à partir de `dev` :
   ```bash
   git checkout dev
   ```

**Crée une branche de travail** :
   - Utilise un nom explicite :  
     - `avai_numéro--DeTicket_nom-fonctionnalite`
     - `avai_numéro--DeTicket_bugfix/description-bug`
     - `avai_numéro--DeTicket_hotfix/correctif`
   
   ```bash
   git checkout -b avai_numéro--DeTicket_nom-de-votre-feature

3. **Ouvre une Pull Request vers `dev`**
   - Vérifie que les tests passent.
   - Demande une relecture (review) d'au moins 1 membre de l'équipe.

4. Une fois la PR approuvée et validée, elle pourra être mergée dans `dev`.

5. **Uniquement `dev` peut être mergée dans `main`** (par un membre autorisé, après validation).

---

## Bonnes pratiques

- Unité de travail claire par PR
- Messages de commit concis et utiles (`feat: ajout du module X`, `fix: correction du bug Y`)
- Code testé localement
- Suivi des règles de style et lint du projet

---

Merci pour votre rigueur 

