Deploy Monitoring using Helm
---------------------------
The following script is automating the deployment process for both Prometheus and Grafana using Helm

Add the Helm repos for both
Create namespace monitoring
Install Prometheus and Grafana
Wait for Pods to start
Get the URLs to access both of them
Reveal the URL and Open them in the browser
To Deploy Apps:
NOTE: Make sure Minkube in up and running before deploying

!IMPORTANT: Make sure the values.yaml are in the right Path otherwise update the following lines in the script.

--values="$PWD/Prometheus/values-prometheus.yaml"
--values="$PWD/Grafana/values-grafana.yaml"
Then proceed with the following:

chmod +x monitoring-deploy.sh
./monitoring-deploy.sh
To Delete Apps:
chmod +x delete-deployment.sh
./delete-deployment.sh
