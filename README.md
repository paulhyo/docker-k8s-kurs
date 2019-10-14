Docker und Kubernetes – Übersicht und Einsatz («DUK»)
-----------------------------------------------------

Container und die in darin bereitgestellten Microservices sind mittlerweile zu einem festen Bestandteil der neuen IT-Landschaft geworden. Orchestrierungslösungen wie Kubernetes ergänzen die Container um weitere Funktionen wie Skalierung.

### Inhalt

* Die neue Welt der Container und Microservices
* Container, Container-Plattformen, Basics und Konzepte
* Docker
* Container Security (https://docs.docker.com/engine/security/seccomp/)
* Die eigene Container Registry
* Weitere Container-Plattformen
* Container Cluster – Orchestrieren, Service Discovery ...

* Kubernetes (K8s) und Alternativen
* Verstehen und Verwalten von Ressourcen im K8s Cluster
* K8s GUIs/Monitoring: Cockpit, Dashboard und mehr
* K8s: Debugging, Rolling Upgrades
* Alternativen

### Key Learnings

* Grundkenntnisse zu Container, Cluster, Orchestratoren und Service Discovery, deren Nutzen, Einsatzmöglichkeiten und Einschränkungen
* Verstehen, Beurteilen und Einschätzen des Einsatzes von Container, Cluster, Orchestrierung und Service Discovery in Ihren Projekten
* Umsetzen von Container-Umgebungen


helm repo add coreos https://s3-eu-west-1.amazonaws.com/coreos-charts/stable/
helm install coreos/prometheus-operator --name prometheus-operator --namespace monitoring
helm install coreos/kube-prometheus --name kube-prometheus --namespace monitoring
helm install --name="kube-metrics" stable/kube-state-metrics --namespace=monitoring


kubectl get CustomResourceDefinition

URLs:
http://192.168.178.200:32526
http://192.168.178.200:32499
# docker-k8s-kurs
