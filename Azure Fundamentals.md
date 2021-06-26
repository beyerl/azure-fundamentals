---


---

<h1 id="azure-fundamentals">Azure Fundamentals</h1>
<h1 id="einführung-in-azure-grundlagen">Einführung in Azure-Grundlagen</h1>
<h2 id="was-ist-cloud-computing">Was ist Cloud Computing?</h2>
<p>Cloudcomputing ist die Übermittlung von Computingdiensten über das Internet, z.B.Server, Speicher, Datenbanken, Netzwerke, Software, Analysen und Informationen.</p>
<h3 id="warum-ist-cloud-computing-in-der-regel-günstiger">Warum ist Cloud Computing in der Regel günstiger?</h3>
<p>Nutzungsbasiertes Preismodell (Betriebskostene statt Investitionskosten)</p>
<h3 id="wieso-sollte-ich-in-die-cloud-migrieren">Wieso sollte ich in die Cloud migrieren?</h3>
<p>Skalierbarkeit der Infrastruktur -&gt; Anschaffung von Hardware blockiert nicht die Releasezeiträume</p>
<h2 id="was-ist-azure">Was ist Azure?</h2>
<p>Azure ist ein Portfolio mit Clouddiensten.</p>
<h3 id="leistungsumfang-von-azure">Leistungsumfang von Azure</h3>
<ul>
<li>Unterstützung vieler Programmiersprachen und Open Source Lösungen</li>
<li>Hybridlösungen (Public/Private-Cloud)</li>
<li>Sicherheit</li>
</ul>
<h3 id="welche-möglichkeiten-bietet-azure">Welche Möglichkeiten bietet Azure?</h3>
<p>In Azure stehen Ihnen mehr als 100 Dienste zur Verfügung</p>
<h3 id="was-ist-das-azure-portal">Was ist das Azure-Portal?</h3>
<p>Das Azure-Portal ist eine webbasierte, zentrale grafische Benutzeroberfläche, die eine Alternative zu Befehlszeilentools darstellt. Das Azure-Portal ist auf Resilienz und fortlaufende Verfügbarkeit ausgelegt.</p>
<h3 id="was-ist-azure-marketplace">Was ist Azure Marketplace?</h3>
<p>Im Azure Marketplace können Kunden Anwendungen und Dienste von Hunderten führenden Dienstanbietern suchen, testen, erwerben und bereitstellen.</p>
<h2 id="tour-durch-die-azure-dienste">Tour durch die Azure-Dienste</h2>
<ol>
<li>Compute: Rechenleistung (Azure-VMs, Azure Kubernetes Service, Azure Container Instances, Azure-Funktionen)</li>
<li>Networking: Virtuelle Netzwerke (Azure Virtual Network, Azure Load Balancer, Azure VPN Gateway, Azure DDoS Protection, Azure Traffic Manager)</li>
<li>Storage: Online Speicher (Azure Blob Storage, Azure File Storage, Azure Queue Storage, Azure-Tabellenspeicher (NoSQL))</li>
<li>Mobile: Cross-Plattform und Native Apps für Mobile Endgeräte</li>
<li>Databases: z.B. SQL und NoSQL Datenbanken (Azure Cosmos DB, SQL Datenbanken, Azure Synapse Analytics, Azure Database Migration Service)</li>
<li>Web: Webanwendungen, APIs (Azure App Service, Azure Notification Hubs, Azure API Management)</li>
<li>IoT: Sensordatenanalyse (IoT Central, Azure IoT Hub, IoT Edge)</li>
<li>Big Data: Analytics über große Datenmengen (Azure Synapse Analytics, Azure HDInsight, Azure Databricks)</li>
<li>AI: Vorhersage zukünftigen Verhaltens auf Basis vorhandener Daten (Azure Machine Learning-Dienst, Azure ML Studio, Cognitive Services)</li>
<li>DevOps: CI/CD (Azure DevOps, Azure DevTest Labs)</li>
</ol>
<h1 id="grundlegende-konzepte-von-azure">Grundlegende Konzepte von Azure</h1>
<h2 id="erörtern-verschiedener-cloudmodelltypen">Erörtern verschiedener Cloudmodelltypen</h2>
<ul>
<li><strong>Öffentliche Cloud</strong>: Alle Dienste werden vom Cloudprovider gehostet</li>
<li><strong>Private Cloud</strong>: Alle Dienste werden vom Unternehmen gehostet</li>
<li><strong>Hybrid Cloud</strong>: Mischung aus öffentlicher und privater Cloud</li>
<li></li>
</ul>
<h3 id="öffentliche-cloud">Öffentliche Cloud</h3>
<ul>
<li>Keine hochzuskalierenden Investitionskosten.</li>
<li>Anwendungen können schnell bereitgestellt und außer Betrieb genommen werden.</li>
<li>Organisationen zahlen nur für das, was sie nutzen.</li>
<li></li>
</ul>
<h3 id="private-cloud">Private Cloud</h3>
<ul>
<li>Hardware muss für die Inbetriebnahme erworben und gewartet werden.</li>
<li>Organisationen haben vollständige Kontrolle über Ressourcen und Sicherheit.</li>
<li>Organisationen sind für Hardwarewartung und -erneuerung verantwortlich.</li>
<li></li>
</ul>
<h3 id="hybrid-cloud">Hybrid Cloud</h3>
<ul>
<li>Bietet die größte Flexibilität.</li>
<li>Organisationen bestimmen, wo ihre Anwendungen ausgeführt werden.</li>
<li>Organisationen kontrollieren Sicherheits-, Compliance- oder rechtliche Anforderungen.</li>
</ul>
<h2 id="beschreiben-der-vorteile-und-überlegungen-zur-verwendung-von-clouddiensten">Beschreiben der Vorteile und Überlegungen zur Verwendung von Clouddiensten</h2>
<h3 id="was-sind-einige-der-vorteile-von-cloud-computing">Was sind einige der Vorteile von Cloud Computing?</h3>
<ul>
<li><strong>Hochverfügbarkeit</strong></li>
<li><strong>Skalierbarkeit</strong>: Apps in der Cloud können  <em>vertikal</em>  und  <em>horizontal</em>  skaliert werden:<br>
-  Durch vertikales Skalieren kann die Computekapazität erhöht werden, indem RAM oder CPUs zu einer VM hinzugefügt werden.<br>
-  Durch horizontales Skalieren kann die Computekapazität erhöht werden, indem Ressourceninstanzen hinzugefügt werden.</li>
<li><strong>Elastizität</strong>: automatischen Skalierung</li>
<li><strong>Flexibilität</strong></li>
<li><strong>Geografische Verteilung</strong></li>
<li><strong>Notfallwiederherstellung</strong></li>
</ul>
<h3 id="kapitalkosten-und-betriebskosten">Kapitalkosten und Betriebskosten</h3>
<p>Zwei verschiedene Arten von Ausgaben:</p>
<ul>
<li><strong>Investitionsausgaben (CapEx)</strong> beschreiben die im Voraus anfallenden Ausgaben für die Anschaffung physischer Infrastruktur, die dann im Lauf der Zeit abgeschrieben werden</li>
<li><strong>Betriebskosten (OpEx)</strong>  sind Kosten für aktuelle Dienste oder Produkte, die sofort abgerechnet werden. Diese Ausgaben können Sie im gleichen Jahr abschreiben, in dem sie anfallen. Es gibt keine Anschaffungskosten. Sie zahlen für Dienste und Produkte dann, wenn Sie sie nutzen.</li>
</ul>
<h3 id="cloud-computing-ein-nutzungsbasiertes-modell">Cloud Computing: ein nutzungsbasiertes Modell</h3>
<p>Cloud-Dienstanbieter arbeiten mit einem <em>nutzungsbasierten Modell</em>.</p>
<h2 id="beschreiben-unterschiedlicher-clouddienste">Beschreiben unterschiedlicher Clouddienste</h2>
<ul>
<li><strong>IaaS</strong> <em>Infrastructure-as-a-Service</em>: Cloudanbieter kümmert sich um Hardware, Cloudmandant um alles vom Betriebssystem aufwärts</li>
<li><strong>PaaS</strong> <em>Platform-as-a-Service</em>: Cloudanbieter verwaltet virtuelle Computer und Netzwerkressourcen, Cloudmandant stellt App bereit</li>
<li><strong>SaaS</strong> <em>Software-as-a-Service</em>: Cloudanbieter verwaltet komplette Inrastruktur und stellt Anwendung bereit, Cloudanbieter nutzt Anwendung und stellt Anwendungsdaten bereit</li>
</ul>
<p><img src="https://docs.microsoft.com/de-de/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-575a09e9.png#lightbox" alt="Clouddienstmodelle"></p>

