# Uhok Deploy

## 원본 Repo

👉 https://github.com/uhoks-sonata/uhok-deploy.git

## 개요

이 레포는 프로젝트의 **배포 환경**(AWS EC2 (Ubuntu), Docker Compose, Nginx) 입니다.

※ [uhok-data](https://github.com/uhoks-sonata/uhok-data.git)는 이 배포 구성과 별도로 실행됩니다.

## 내가 한 일

- 서비스별 Docker Compose 구성 (Public / App / ML)
- Nginx 리버스 프록시 설정 (Frontend, Backend, ML 경로 라우팅)
- AWS EC2 배포 및 VPC, 보안 그룹 구성

## 클라우드 아키텍처

![클라우드 아키텍처](../images/architecture/UhokCloudArchitecture_merged.drawio.png)

## 담당자

- **강민혁**
