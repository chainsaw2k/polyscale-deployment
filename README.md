# polyscale-deployment

This repo has deployment yamls for running Polyscale's ntu-worker on Section.

First, fill in the URL to either the cache or the database. Then:

$ kubectl apply -f polyscale-deployment.yaml

In order to send metrics to Grafana Cloud, fill in your credentials and then:

$ kubectl apply -f grafana-loki-deployment.yaml

Learn how to get your Kubernetes API URL here:
https://www.section.io/docs/guides/kubernetes-ui/kubernetes-api/basics/
