# privatsky-oppgave

## argo-cd release

Team x har anskaffet en app som er tilgjengeliggjort på https://hub.docker.com/r/havardelnan/wonderapp . Denne ønsker de å deploye vha argocd.

Det er vedlagt utsnitt av dokumentasjonen for publisering på vår plattform: [publisering.md](./publisering.md)

### Oppgave
1. Lag et git-repo med deploymentkode for applikasjonen som kan benyttes av Argo-cd.
2. Applikasjonen skal eksponeres mot internett med produksjonssertifikat fra lets-encrypt på wonderapp.sky.nhn.no.

### Om applikasjonen
Applikasjonen tilgengeliggjør en http-tjeneste på port 8080.
