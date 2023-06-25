# Deployment-Strategies

# The three deployment strategies that we are going to cover are 

Bluegreen 

Canary 

Rolling-Update 

# Stopping the traffic reaching the pods 

kubectl scale deployment my-app-v2 --replicas=0 -n josh

# Starting the traffic reaching the pods 

kubectl scale deployment my-app-v2 --replicas=3 -n josh

# Rolling update 

![image](https://github.com/joshking1/Deployment-Stratergies/assets/88409463/0e20e562-cc05-4da5-8442-cdf4e0a667df)




