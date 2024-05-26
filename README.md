# microservices-istio-kubernetes
This project demonstrates a microservices architecture deployed on Kubernetes, with traffic management and observability enhanced using Istio.

## Technologies Used

- **Kubernetes**
- **Istio**
- **Docker**
- **Python** (Flask for the microservices)

## Project Structure
microservices-istio-kubernetes/
│
├── service-a/
│ ├── app.py
│ └── Dockerfile
│
├── service-b/
│ ├── app.py
│ └── Dockerfile
│
├── service-c/
│ ├── app.py
│ └── Dockerfile
│
└── k8s/
├── service-a.yaml
├── service-b.yaml
├── service-c.yaml
└── istio-gateway.yaml
