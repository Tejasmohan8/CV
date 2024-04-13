# CV
curl -sO http://172.16.51.56:8080/jnlpJars/agent.jar
java -jar agent.jar -jnlpUrl http://172.16.51.56:8080/manage/computer/U%5F69/jenkins-agent.jnlp -secret e15f59bd3ee976ada1c697c525df350645a4aab6d105ebd3aaf61f61ef31f9a2 -workDir "/home/msis/jenkins"

kubeadm join 172.16.51.56:6443 --token wn201o.tw41mawp4tohgr0d --discovery-token-ca-cert-hash sha256:3e53aa37415c564bad823bc3001d391945740ae8393d6843476e9c7f9a0ac655

