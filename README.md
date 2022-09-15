# Grafana, Prometheus, Nexus LAB


## About the project

Lab/hands-on proposal on my study of Application Performance Monitoring (APM) tools. There is a pipeline to upload a .war file to java on the Nexus (hosted repository of maven2) to monitor it later. Then, with Grafana and Prometehus, metrics are placed to check the Nexus overhead.



## Tools

- [ ] [AWS - EC2](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)
- [ ] [Jenkins](https://www.jenkins.io/)
- [ ] [Grafana](https://grafana.com/)
- [ ] [Prometheus](https://prometheus.io/)
- [ ] [Nexus](https://www.ibm.com/garage/method/practices/deliver/tool_nexus/)


## Como usar?

Access these links that use the public ip of an EC2 and its respective ports

- [ ] [Amazon EC2](https://us-east-1.console.aws.amazon.com/ec2-instance-connect/ssh?connType=standard&instanceId=i-00c0b902e26190ac8&osUser=ubuntu&region=us-east-1&sshPort=22#/)
- [ ] [Jenkins](http://44.210.15.179:8080/job/eloise/)
- [ ] [Grafana](http://44.210.15.179:3000/)
- [ ] [Prometheus](http://44.210.15.179:9090/)
- [ ] [Nexus](http://44.210.15.179:8081/)

***
## Improvements

I accept code improvements.
To do this, request a pull request.
```
git remote add origin https://github.com/eloise-takami/monitoramento
git branch name_branch
git commit -am "first commit"
git push origin name_branch
```
