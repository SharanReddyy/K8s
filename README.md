# Convert the java code using maven
Do it using the following command:

    mvn clean package

# Write a dockerfile and build docker image in the primary directory
Write a docker file in the primary directory using:

    docker build -t javaimage:latest
Push it to docker hub and pull using kubernetes yaml file.
# Run minikube 

    minikube start

# Run deployments and services:

    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml

# Get minikube ip:
 Make sure to write the correct port number in the format <ip_address:port_number>
    minikube ip

# The output looks like:
![Screenshot from 2024-03-07 17-47-14](https://github.com/SharanReddyy/K8s/assets/78129496/29b4cd6b-8e5b-4414-8542-e18e1e6bdf28)


    
