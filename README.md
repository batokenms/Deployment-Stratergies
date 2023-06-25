# Deployment-Strategies

# The three deployment strategies that we are going to cover are 

Bluegreen 

Canary 

Rolling-Update 

# Stopping the traffic reaching the pods 

kubectl scale deployment my-app-v2 --replicas=0 -n josh

# Starting the traffic reaching the pods 

kubectl scale deployment my-app-v2 --replicas=3 -n josh



