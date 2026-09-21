# 김종언
### Cloud & DevOps Engineer

> AWS와 컨테이너 환경의 변경을 IaC와 검증 흐름으로 관리합니다.  
> 배포 이후의 상태를 관측하고, 재현 가능한 운영 기준을 만드는 데 관심이 있습니다.

[이력서 및 포트폴리오 PDF 보기 →](./documents/%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%A9%E1%86%BC%E1%84%8B%E1%85%A5%E1%86%AB_%E1%84%8B%E1%85%B5%E1%84%85%E1%85%A7%E1%86%A8%E1%84%89%E1%85%A5%26%E1%84%91%E1%85%A9%E1%84%90%E1%85%B3%E1%84%91%E1%85%A9%E1%86%AF%E1%84%85%E1%85%B5%E1%84%8B%E1%85%A9.pdf)

<br />

## Focus

| Infrastructure as Code | Container Platform | Delivery & Validation |
| :---: | :---: | :---: |
| Terraform으로 변경을 검토 가능한 단위로 관리 | Docker, Kubernetes/EKS 환경 구성과 상태 확인 | GitHub Actions, OIDC, GitOps 기반 배포와 검증 |

<br />

## Selected Projects

### 01. BADA — AWS 기반 임금체불 증거 패키징 서비스
**AWS Cloud School 최종 프로젝트 · 2026.05–07 · 5인 팀 ·**

- 인프라, CI/CD, IaC를 맡아 Terraform과 GitHub Actions 워크플로를 구성했습니다.
- `Plan → PR 검토 → 수동 Apply → AWS·HTTP 상태 확인` 흐름으로 변경을 통제했습니다.
- 팀은 비동기 AI 작업을 SQS와 DLQ로 분리하고, 민감 데이터 보호와 관측을 고려한 AWS 환경을 설계했습니다.

**Stack** · AWS · Terraform · GitHub Actions · OIDC · ECS · SQS · RDS · S3 · CloudWatch  
[프로젝트 저장소 보기 →](https://github.com/Kjjedd/BADA)

<br />

### 02. Multi-Region EKS GitOps — Osaka Staging
**AWS Cloud School 프로젝트 · 2026.03–04 · 3인 팀**

- Osaka Staging 구축과 검증의 첫 담당자로 참여했습니다.
- `eksctl` 기반 구성과 검증, Kustomize staging overlay, Argo CD Application을 직접 작성했습니다.
- `kubectl` 검증 절차와 이슈 문서를 남겨 팀이 재사용할 수 있는 기준 환경을 정리했습니다.

**Stack** · AWS EKS · Kubernetes · Argo CD · Kustomize · GitHub Actions · Bash  
[프로젝트 저장소 보기 →](https://github.com/Kjjedd/multi-region-eks-gitops)

<br />

### 03. Docker Swarm Auto Scaling
**AWS Cloud School 프로젝트 · 2026.02–03 · 3인 팀**

- CI/CD, Shell·Prometheus 자동화, 실험 설계와 수행을 담당했습니다.
- EC2 3대 환경에서 Shell·Prometheus와 CloudWatch·SNS 기반 scale-out 방식의 반응과 운영상 trade-off를 비교했습니다.
- 4개 조건을 각 10회씩 반복해 관측 결과를 확인했습니다.

**Stack** · Docker Swarm · Prometheus · Grafana · CloudWatch · SNS · GitHub Actions  
[프로젝트 저장소 보기 →](https://github.com/Kjjedd/docker-swarm-autoscale)

<br />

## Skills

`AWS` `Terraform` `GitHub Actions` `OIDC` `Docker` `Kubernetes` `EKS` `Argo CD` `Kustomize` `Linux` `Bash` `Python` `Prometheus` `Grafana` `CloudWatch`

<br />

## Education & Certification

- **AWS Cloud School 13기** — 1,050시간 교육과정 수료, 2025.12–2026.07
- **AWS Certified Solutions Architect – Associate (SAA-C03)** — 2026.06 취득
- **한양대학교 ERICA 컴퓨터학부** — 클라우드운영 마이크로전공 병행, 2026.08 졸업

<br />

<sub>계정 식별자, 접근 정보, 운영 중인 서비스의 민감한 세부 사항은 공개하지 않습니다.</sub>
