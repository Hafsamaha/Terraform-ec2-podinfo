###
# Terraform: EC2 Instanz mit Terraform erstellen
###

Hallo,
bitte erstelle mit Terraform eine EC2 Instanz in einem (auch mit TF erstellten) VPC mit einem public Subnet. Die EC2 Instanz soll eine public IP-Adresse bekommen und über Terraform so konfiguriert werden, dass der Podfinfo Docker Container (https://github.com/stefanprodan/podinfo) auf der Instanz läuft und die Weboberfläche des Containers über die IP abrufbar ist.

Nutze dafür die Terraform AWS Module VPC & EC2

Bitte einen Link zu dem Repo mit den Terraform Files und ein Screenshot der laufenden Anwendung (inkl. der IP in der Browserleiste)
Denke bitte daran, nach Beendigung der Aufgabe die Ressourcen wieder zu löschen.