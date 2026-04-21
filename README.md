# roboshop-helm-v1

files: | 
{{ .Files.Get "files/sample.conf" | indent 4 }}



kubectl → sends YAML → Kubernetes API → EKS creates resources

helm    → generates YAML → Kubernetes API → EKS creates resources