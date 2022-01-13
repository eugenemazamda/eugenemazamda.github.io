---
layout: post
title:  Kubernetes Cloud [Azure Kubernetes (AKS)]
date:   2020-11-11 15:01:35 +0300
image:  '/images/aks.png'
tags:   [kube, cloud, Linkbynet]
categorie: technique
---

> Qu'est-ce que Kubernetes (K8s) ?

C'est un système open source permettant d'automatiser le déploiement, la mise à l'échelle et la gestion des applications conteneurisées 

[ Documentation Source](https://kubernetes.io/fr/){:target="_blank"}

> Qu'est-ce que Azure Kubernetes (AKS) ?

C’est un orchestrateur de conteneur complètement managé, facilite le déploiement et la gestion d’applications conteneurisées. Il offre une expérience d’intégration continue et de livraison continue (CI/CD) Kubernetes serverless, ainsi qu’une sécurité et une gouvernance de classe entreprise. Il réunit les équipes dédiées aux déploiements et aux opérations sur une même plateforme pour rapidement créer, livrer et mettre à l’échelle des applications en toute confiance.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/kube.jpg" alt="Project">
  </div>
  <em>Architecture Kubernetes LbnPuzzle</em>
</div>

Kubernetes se base sur une image pour générer des conteneurs et ces images sont stockées dans un registre privé ou public.

- **Registre Images** : c’est une application qui permet de distribuer des images docker au sein d’un environnement. Une image docker est en quelque sorte une image disque qui contient l’arborescence d’une distribution Linux, Windows, le code source d’une application et des binaires capables de le faire tourner.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/registre.jpg" alt="Project">
  </div>
  <em>Architecture Déploiement d'images vers Kubernetes LbnPuzzle</em>
</div>

> Monter en compétences sur Kubernetes

Bien que le projet **LbnPuzzle** ait été arrêter, je continue à monter en compétence sur la technologie en autoformation et sur des projets personnel. 

- Aujourd'hui utilise beaucoup solution Kubernetes de Google Cloud (GKE) et celle d'Azure (AKS).

> Réalisation(s) associée(s)

<div class="gallery-box">
  <div class="gallery">
    <a href="https://eugenemazamda-cloud.com/projects/lbnpuzzle" target="_blank"><img src="/images/kubernetes.png" alt="Project"></a>
  </div>
</div>