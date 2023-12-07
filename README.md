# vote-app-k8s


15  kubectl create -f ns.yml 

   16  kubectl create  -f postdb.yml 
   
   17  kubectl create -f postdbsvc.yml 
   
   18  kubectl create -f redis.yml 
   
   19  kubectl create -f redisvc.yml 
   
   20  kubectl create -f result.yml 
   
   21  kubectl create -f resultsvc.yml 
   
   22  kubectl create -f vote.yml
   
   23  kubectl create -f votesvc.yml 
   
   24  kubectl create -f worker.yml 
   
   25  kubectl get pod  -n vote
   
   26  kubectl get svc 
   
   27  kubectl get svc -n vote
   
   28  curl 10.105.4.105
   
   29  curl 10.105.4.105:5001                   svc ip and port no  of result svc
   
   30  curl 10.110.196.193:5000               svc ip and port no  of  vote svc
   
   31  kubectl get pod -o wide -n vote 
   
   32  kubectl get svc -o wide -n vote 
   
   33  kubectl get pod -n vote

