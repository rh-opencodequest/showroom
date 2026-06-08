# Quarkus OpenShift + OpenShift AI Workshop

Workshop Showroom pour apprendre à construire des applications cloud-native avec Quarkus, Red Hat OpenShift, et l'IA générative via OpenShift AI.

## Contenu du workshop

Ce workshop couvre :
- **Red Hat Developer Hub** : bootstrapping de microservices depuis des templates
- **Red Hat OpenShift Dev Spaces** : développement in-browser sans installation locale
- **Quarkus** : développement de microservices Java cloud-native
- **Hibernate ORM Panache** : ORM simplifié pour Quarkus
- **OpenAPI / Swagger UI** : documentation automatique d'API
- **GitOps / ArgoCD** : déploiements déclaratifs sur OpenShift
- **Tekton + Trusted Application Pipelines** : pipelines CI/CD sécurisés
- **Advanced Cluster Security** : scan CVE et vérification de politiques
- **Enterprise Contract** : vérification de provenance des images
- **Quarkus LangChain4j** : intégration LLM déclarative

## Structure du repository

```
content/
  antora.yml
  modules/ROOT/
    nav.adoc
    pages/
      index.adoc
      01-overview.adoc
      02-details.adoc
      03-module-01-web-application.adoc
      04-module-02-hero-microservice.adoc
      05-module-03-transactions-orm.adoc
      06-module-04-openapi.adoc
      07-module-05-git-to-openshift.adoc
      08-module-06-trusted-pipelines.adoc
      09-module-07-villain-microservice.adoc
      10-module-08-fight-microservice.adoc
      99-conclusion.adoc
    assets/images/
      (screenshots et diagrammes)
site.yml
```

## Contenu source

Ce workshop est basé sur le contenu original de :
https://github.com/cescoffier/quarkus-openshift-workshop

## Build local

```bash
# Installer Antora
npm install -g @antora/cli @antora/site-generator

# Générer le site
antora site.yml
```

## Déploiement

Le site est déployé automatiquement via GitHub Actions vers GitHub Pages.

## Contribution

Les contributions sont les bienvenues ! Ouvrez une issue ou une pull request.
