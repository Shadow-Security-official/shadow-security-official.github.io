# shadow-security-official.github.io

Site GitHub Pages de l'organisation **Shadow-Security-official**.

## Contenu

| Fichier | Rôle |
|---|---|
| `.well-known/shadow-registry.txt` | Attestation `SR-000008` : prouve que le domaine `shadow-security-official.github.io` appartient à Shadow-Security, pour le [registre officiel](https://registry.shadow-security.fr). Aucun enregistrement DNS n'est possible sous `github.io` : ce fichier remplace l'enregistrement `TXT _shadow-registry` des autres domaines. |
| `.nojekyll` | Désactive Jekyll, sans quoi GitHub Pages ignorerait le dossier `.well-known`. |

## À ne pas modifier

Modifier ou supprimer le fichier d'attestation fait échouer la vérification de ce domaine à la prochaine signature du registre.

Le miroir de l'autorité de certification est servi par un autre dépôt, sous [`/shadow-registry-trust/`](https://shadow-security-official.github.io/shadow-registry-trust/).

## Vérifier

[`/.well-known/shadow-registry.txt`](https://shadow-security-official.github.io/.well-known/shadow-registry.txt) doit afficher `SR-000008`.

## English

GitHub Pages site of the Shadow-Security-official organization. It only serves the attestation file proving that this host belongs to Shadow-Security, for the [official registry](https://registry.shadow-security.fr). Please do not edit or delete it.

## Contact et licence

contact@shadow-security.fr · Tous droits réservés, voir [LICENSE](LICENSE).
