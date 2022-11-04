# kubevproject
# Project architecture
  ![arch](https://user-images.githubusercontent.com/96655654/190453949-8024c9f8-47c2-45cd-8561-0d0099adb8b6.png)
  
  Clone the repository using git clone
  
    *Run kubectl create -f . or the path you have your manifest file.
    
    * In this project I have create 3 replicas of webapp and ! replica of rabbitmq,memcache and Database.
    If you want to change that you can customize in manifest file.
    
    * Also I have used secrets to pass the credentials . So you have to create your own credentials by encoding the values and store it in secret manifest
    You can refer the Documentation link : 
    https://kubernetes.io/docs/tasks/configmap-secret/managing-secret-using-config-file/
    
    * These are all the Important link that you can refer to undestand about the project.
       
       # Creating Services:
           https://kubernetes.io/docs/concepts/services-networking/service/
          
       # Creating replicasets:
          https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/
          
       # Creating Deployment:
          https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/
        
       # Creating Volumes: 
         https://kubernetes.io/docs/concepts/storage/volumes/
        
       # Creating Secrets:
         https://kubernetes.io/docs/concepts/configuration/secret/
