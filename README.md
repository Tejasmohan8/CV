# CV
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
sudo curl -sO http://172.16.51.56:8080/jnlpJars/agent.jar
sudo java -jar agent.jar -jnlpUrl http://172.16.51.56:8080/manage/computer/Ubuntu%5F56/jenkins-agent.jnlp -secret df21274b4b75aafe6e76ed7c3205f13ff2fe4553f7fa38993872e6e80e1d08f2 -workDir "/home/msis/jenkins"


kubeadm join 172.16.51.56:6443 --token si3t4c.5fb8i0mgksxnscmk \
	--discovery-token-ca-cert-hash sha256:d6a9f8aa8a573d8fd1e0f786f40a31ff9aa37b4247dda6b5c36cbf9658a7cbb2 
