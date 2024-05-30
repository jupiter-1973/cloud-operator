# k8s-yamls

kubernetes cluster를 구축 및 운영하면서 생성/사용되는 manifest를 참고하고자 만든 곳이다.
분류는 아래와 같다.


## MSA에 의한 분류
### 1. API Gateway / Ingress 
### 2. RuntimePlatform : Cluster Component & worker-load / Pod / Node
### 3. ServiceMesh : CNI & network & service & Ingress
### 4. CI/CD : Registry & Repository
### 5. Backing Service : MOM(Message Oriented Management) & Persistence & DB / Middleware
### 6. Telemetry : Monitoring & logging & Tracing


## General kubernetes cluster에 의한 분류
### 1.workload(controller)
### 1-1. deployment
### 1-2. statefulset 
### 1-3. daemonset
### 1-4. job
### 1-5. cronjab

## 2. ConfigMap

## 3. Secret

## 4. Service
### 4-1. ClusterIP
### 4-2. nodePort
### 4-3. LoadBalance

## 5. ingress

## 6. Backup & Restore

## 7. Volumes(persistent)

## 8. authentication & authorization & certification , Account

## 9. Kubernetes CRD & API Aggregation

