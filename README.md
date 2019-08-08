## 1. Certified Application Catalog [Tech Preview]

While there are many pre-packaged Helm charts available in the community today, developers want the ability to deploy custom applications leveraging their own Helm charts and values in multiple contexts and kubernetes infrastructures. This also must happen alongside custom application templates and be vetted by automations teams. With these complexities comes the next challenge of how to package applications into docker images, scan them for security constraints, productize them, and ship them via Helm or Operators via CICD. 

<p><a class="button-cta button-secondary" href="https://github.com/platform9/certified-apps/tree/master/charts" target="_blank" rel="noopener">See some of our charts here</a></p>

<img width="642" alt="Screen Shot 2019-08-07 at 4 39 26 PM" src="https://user-images.githubusercontent.com/34694236/62665382-e6503e80-b933-11e9-80d9-2a86adc1b7d3.png">

As experts in managed Kubernetes and SaaS, we are now spearheading a grass-roots movement to make "bring your app" a possibility; and we want to do so with out sacrificing quality or security. This means that these charts will be curated continously by our team of solutions experts who are working with kubernetes teams every day in the field. 

### Platform9's new "certified" applications catalog

* Easily adds additional custom templates either as Helm charts, YAML files, or Operators

* Pre-packages them in a way that is easy to deliver for operations, and simple to consume for developers

* Is free to use on your Kubernetes cluster even if you're not a Platform9 customer

* Allows you to commit your own helm charts to the repo, adding to the standard of excellence

* Bring the benefits of Helm, along with the new wave of "bring your own operator", into Kubernetes 1.14 and beyond

* Creates a production ready experience for application lifecycle management without much testing

* Is fully self-service and opensource  

## 2. Platform9 Community Application Catalog

* Hundreds of pre-built Kubernetes applications from existing Helm repos

* Ability to add your own repositories 

* One-click deployment of Helm charts 

* Full RBAC controls over deployments and access to namespaces 

* Leverages community Helm charts (google helm/stable, helm/incubator, etc...) 

![screen_applications-catalog2](https://user-images.githubusercontent.com/34694236/62586046-a6745300-b870-11e9-8add-03dca2576e9a.png)

Note: Certified App Catalog will be a Platform9 hosted repository on Github that specifically manages a set of highly selected helm charts along with the ability to edit values.yaml very easily. 

For enterprise grade SLAs and fully managed applications that follow the same philosophy, please continue reading below on our Managed Applications Solution which is currently GA and require a subscription license for a fully managed experience with 99.9% SLAs. This will be mostly based on curating, and contributing to, operators that are most commonly used in production on Kubernetes

## 3. Platform9 Fully Managed Applications

The industry’s only integrated, end-to-end 99.9% SLA spanning both the Kubernetes infrastructure and the application tier. Each managed app can be set up as a multi-tenant service across all clusters, or per specific clusters/namespaces.

Each new managed application introduced in the Managed Apps catalog will first be released in a “Beta” phase and will gradually progress to the “Fully-managed” level as it matures, and all supported capabilities graduate into production-readiness.

SLAs for the individual apps would be complementary to the SLA that Platform9 already provides for the Kubernetes infrastructure itself. Depending on the complexity of the managed application chosen, the SLA and fully-managed functionality may also cover additional capabilities–such as cross-geo disaster recovery for databases and advanced integrated services with other complementary managed applications offered, automatic backup/recover, auto-scaling, and more.

![mapps](https://user-images.githubusercontent.com/34694236/62586149-37e3c500-b871-11e9-95d2-e9e111abbed7.png)

In many of these cases, Platform9 will partner directly with various organizations behind specific applications or Kubernetes Operators, to advance the development and ongoing support for its customers. The first of such collaboration is with Percona, around its MySQL offering – enabling automatic backups, DR, zero-touch upgrades, support, and more.

### Managed Prometheus 

* The Prometheus stack and Alert Manager, with HA, persistent storage, DR, and more enabled 

* Provides one-click deployment for developers, with governance, security, visibility and scale 

* All handled automatically, with no need for Admin intervention via OLM and CRDS managed by Platform9

### Managed EFK: Fluentd, Elastic and Kibana

* Integrated logging and indexing service

### Managed MySQL

* The popular relational database for stateful Kubernetes applications is delivered via Percona’s MySQL offering.

....and many more coming soon!

## Platform9's Market Leading Opensource Contributions

<h3>etcdadm (etcd admin)</h3><p>Inspired by kubeadm, etcdadm is an open source command-line tool that allows users to easily configure, install and operate secure etdc clusters that can run anywhere &#8211; in the cloud, on-premises, as well as on air-gapped environments.</p><p><a class="button-cta button-secondary" href="https://github.com/kubernetes-sigs/etcdadm" target="_blank" rel="noopener">See Github</a></p><p>
  
<h3>Klusterkit</h3><p>Klusterkit is a set of 3 open source tools designed to simplify deployment and operations of highly-available, multi-master, production-grade Kubernetes clusters on on-premises, air-gapped environments.</p><p>Klusterkit is comprised of: cctl, etcdadm, and nodeadm.</p><p><a class="button-cta button-secondary" href="https://github.com/platform9/klusterkit" target="_blank" rel="noopener">See Github</a></p><p>
  
<h3>Decco</h3><p>Decco is a lightweight framework that simplifies the deployment of multi-tenant applications for Kubernetes by automating network configuration, and security hardening of Internet-facing applications.</p><p><a class="button-cta button-secondary" href="https://github.com/platform9/decco" target="_blank" rel="noopener">See Github</a></p><p>
