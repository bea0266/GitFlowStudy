GIT FLOW 만들기

브랜치 목록
Master, Develop, Feature, Release, Hotfix

Master : 배포용 브랜치(실제 운용되는 코드)
Develop : feature에서 개발한 기능을 머지할 때 사용, 배포 시 master에 머지 
Feature : 단위 기능 개발 시 사용, develop에 머지
Release : Master에 붙이기 전 Qa할 때 용도로 사용, develop, master에 각각 머지
Hotfix : 배포 시 미쳐 고치지 못한 결함이 있을 때 사용, develop, master에 각각 ㅓ지
