create role binding first
--------------------------------
kubectl create clusterrolebinding jenkins --clusterrole=cluster-admin --serviceaccount=jenkins:default
get password
-----------------
kubectl logs <jenkins_pod_name> -n jenkins
kubectl logs jenkins-5f46556b5c-5fx9b -n jenkins

gilab & youtube
---------------
https://gist.github.com/darinpope/67c297b3ccc04c17991b22e1422df45a
https://www.youtube.com/watch?v=ZXaorni-icg 


vm jenkins-master/slave setup
-----------------------------
https://www.linkedin.com/pulse/jenkins-masterslave-setup-prayag-sangode/