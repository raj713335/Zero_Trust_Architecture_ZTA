<h1 align="center">Zero Trust Architecture (ZTA)</h1>

Zero Trust Architecture (ZTA) implementation with a focus on a secure user interface, outline that emphasizes verification for every request. This includes multi-factor authentication (MFA), continuous monitoring, and robust authorization mechanisms.


<p align="center">
  <img src="data/Desired_Architecture.png" />
</p> 

## 1. Project Architecture

<p align="center">
  <img src="data/zta.png" />
</p> 

# Kong Docker Setup

## 1. Getting Started With The Fast API Application

```sh
$ git clone https://github.com/raj713335/Zero_Trust_Architecture_ZTA.git
$ cd Zero_Trust_Architecture_ZTA
$ pip install -r requirements.txt
$ python main.py
```

## Run & Go
For easy installation and setup run a single command below.
```docker-compose
 docker-compose up -d --build
```

----------

## 2. Keycloak for SSO

Keycloak is an open-source identity and access management (IAM) solution designed to help developers and administrators manage authentication, authorization, and user identities across applications. It simplifies and secures access to applications and services by centralizing user authentication and integrating with multiple authentication providers. Keycloak is widely used in enterprise environments for implementing single sign-on (SSO), multi-factor authentication (MFA), and other security protocols across various applications.

Key Features of Keycloak

- Single Sign-On (SSO): Users can log in once and access multiple applications without having to authenticate again, enhancing user convenience and security.

- Multi-Factor Authentication (MFA): Keycloak supports various MFA methods, such as one-time passwords (OTP) via mobile apps or email, SMS, and other custom mechanisms to improve account security.


<p align="center">
  <img src="data/Keycloak/1.png" width="400" />
  <img src="data/Keycloak/2.png" width="400" />
  <img src="data/Keycloak/3.png" width="400" />
  <img src="data/Keycloak/4.png" width="400" />
</p> 

## 3. Real-time  API monitoring </h3>

- Kong API Gateway
- Zipkin 
- Prometheus
- Grafana
- Logstash
- Elasticsearch
- Kibana

<p align="center">
  <img src="data/API_Management/1.png" width="400" />
  <img src="data/API_Management/2.png" width="400" />
  <img src="data/API_Management/3.png" width="400" />
  <img src="data/API_Management/4.png" width="400" />
  <img src="data/API_Management/5.png" width="400" />
  <img src="data/API_Management/6.png" width="400" />
</p> 

