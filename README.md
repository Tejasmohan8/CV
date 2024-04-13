# CV
sudo curl -sO http://172.16.51.56:8080/jnlpJars/agent.jar
sudo java -jar agent.jar -jnlpUrl http://172.16.51.56:8080/manage/computer/Ubuntu%5F56/jenkins-agent.jnlp -secret @secret-file -workDir "/home/msis/jenkins"

kubeadm join 172.16.51.56:6443 --token wn201o.tw41mawp4tohgr0d --discovery-token-ca-cert-hash sha256:3e53aa37415c564bad823bc3001d391945740ae8393d6843476e9c7f9a0ac655

