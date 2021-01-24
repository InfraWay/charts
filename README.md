# Helm Charts
This repo contains useful helm2 charts

## 1. Helmfile

We really cannot talk about Helm Charts tools without mentioning  [Helmfile](https://github.com/roboll/helmfile). Developed by  [roboll](https://github.com/roboll), Helmfile handles the declarative spec for deploying Helm Charts. It is a tool that helps simplify the configuration of Kubernetes environment according to the specific needs of the apps or web services you want to run. It functions the way Autohelm does, but with additional specific features, which you may find useful.

## 2. Landscaper

[Landscaper](https://github.com/Eneco/landscaper/)  goes another step further with Helm by allowing you to specify a collection of Helm Charts to create your application landscape. You will have to add references with clear values to get Landscaper to work, but the rest is easy from there.

![Monacular](https://2wded2jn6ekmzt6b3ruvnh15-wpengine.netdna-ssl.com/wp-content/uploads/2018/12/images-1.png)

## 3. Monocular

Thinking about starting your own Helm Charts repository? Rather than doing it the old way and using a CLI, you can now use  [Monocular](https://github.com/helm/monocular). There are many reasons why setting up your own repository is a good idea, and Monocular certainly makes managing one easier, thanks to the web UI it uses.

## 4. Autohelm

The name says it all;  [Autohelm](https://github.com/reactiveops/autohelm)  is designed to automate the deployment of Helm Charts. The main difference between Autohelm and other similar tools is in the way it uses Python for the job. Autohelm also supports Git URLs as the source for Helm Charts. You can deploy community Charts in minutes with this tool.

![#bitnamicabin](https://2wded2jn6ekmzt6b3ruvnh15-wpengine.netdna-ssl.com/wp-content/uploads/2018/12/34656521.png)

## 5. Cabin

[Cabin](https://github.com/bitnami-labs/cabin)  is an interesting tool, but one that is absolutely necessary if you want to be able to manage your Kubernetes Helm on-the-go. The tool is actually a mobile app through which you can manage Kubernetes Pods and nodes using nothing but a smartphone.

![](https://caylentinc.wpengine.com/wp-content/uploads/2018/12/orcalogo.png)

## 6. Orca

[Orca](https://github.com/nuvo/orca)  is another one of my favorite Helm Charts tools. It is a tool designed to handle advanced continuous integration and continuous delivery with ease. While Orca may seem like a replacement for Helm on the outside, it actually complements Helm and Helm Charts like no other tool can. It even works with ChartMuseum.

![#Chartmuseum](https://2wded2jn6ekmzt6b3ruvnh15-wpengine.netdna-ssl.com/wp-content/uploads/2018/12/logo2.png)

## 7. ChartMuseum

Speaking of  [ChartMuseum](https://github.com/helm/chartmuseum), those who need a Helm Charts repository will certainly find ChartMuseum to be incredibly handy. It is a repository designed to work with popular Kubernetes environments and services, including the Microsoft Azure Blob Storage and Oracle Cloud Infrastructure Object Storage.

![#helmsman](https://2wded2jn6ekmzt6b3ruvnh15-wpengine.netdna-ssl.com/wp-content/uploads/2018/12/helmsman-1024x306.png)

## 8. Helmsman

Helmsman is a tool designed to make creating, installing, upgrading, migrating, and deleting Helm Charts much, MUCH easier. It also comes equipped with the ability to do all that from version controlled desired state files. You can find  [Helmsman](https://github.com/Praqma/helmsman)  on its GitHub page.

## 9. Helm-Backup

[Helm-backup](https://github.com/maorfr/helm-backup)  is more of an add-on than a tool, but it is a must-have add-on if you work with Helm Charts a lot. It handles backing up and restoring releases in a namespace. Rather than having to chore through manual backups regularly, you can use Helm-backup to simplify the whole thing.

## 10. Codefresh

[Codefresh](https://codefresh.io/)  is originally a CI/CD-oriented tool designed to make managing Kubernetes releases easier. It is very similar to Orca, but with the addition of a web-based UI and some extra tools. Codefresh now even has its own dashboard for managing Helm Charts and releases.

## 11. Helm Diff

The  [Helm Diff](https://github.com/databus23/helm-diff)  plugin offers one simple, yet very specific feature: It previews helm upgrades as a colored diff. That said, the simple feature brought by Helm Diff makes life as a Kubernetes and Helm user easier. You can avoid unnecessary errors and mistakes during upgrades with this tool.

## 12. Helm-GCS

It is not surprising to find tools and plugins designed to make using Kubernetes, Helm, and Google Cloud Services easier in collaboration. After all, Kubernetes was first developed by Google. The  [Helm-GCS](https://github.com/viglesiasce/helm-gcs)  plugin is exactly what you need if you use Helm Charts on GCS.

![](https://staging-caylent.com.s223939.gridserver.com/wp-content/uploads/2018/12/shipshiplogo-150x150.png)

## 13. Replicated Ship

[Replicated Ship](https://github.com/replicatedhq/ship)  is the next tool on our list. It simplifies the process of upgrading and integrating  [Kustomize](https://github.com/kubernetes-sigs/kustomize)  patches to Helm and Helm Charts. Replicated Ship can also be used for monitoring purposes, plus it automates many of the update and maintenance tasks for you.

## 14. Helm-Secrets

The  [Helm-Secrets](https://github.com/futuresimple/helm-secrets)  plugin guards passwords and access tokens to make infrastructure secure while making them easily accessible. The plugin also provides on the fly decryption and cleanup capabilities.

![#Keel](https://2wded2jn6ekmzt6b3ruvnh15-wpengine.netdna-ssl.com/wp-content/uploads/2018/05/35-kell-logo.png)

## 15. Keel.sh

The next tool you definitely need to check out is  [Keel.sh](https://keel.sh/), which is also designed for continuous delivery. It adds auto-updates and a long list of other features to Helm and the Helm Charts you use.

## 16. Flux Helm Operator

Update: A new addition to our tool list: this handy Helm operator handles Helm Chart releases adeptly. The tool monitors for any changes made to Custom Resources through Kubernetes Events and acts accordingly. It will then install, upgrade or delete a Chart release as required. For more information, visit Flux Helm Operator  [here](https://github.com/fluxcd/flux/tree/master/chart/flux).

There is no doubt that Helm completes Kubernetes in many ways. And these tools further complement the integration of Helm and Helm Charts in different situations and use cases.
