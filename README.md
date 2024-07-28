# Apache, Tomcat 구성 실습(2024/08/29)

## Apache Template 설치

```bash
# 실습 경로 이동
cd /home/webwas/edu-webwas

# Apache 템플릿 압축 해제
tar xvf ...

# Apache 템플릿 설치 폴더 이동
cd /home/webwas/edu-webwas/...

# Apache 템플릿 설치
sh setup
```

## Apache Template 설치 내용

```bash
# 패키지 체크

# Apache 설치

# Tomcat Connector 설치

# Template, Shl 폴더 복사

# 보안 취약점 적용
```

## Apache 인스턴스 구성

```bash
# Apache servers 경로 이동
cd /software/apache/servers

# 인스턴스 생성
sh create_server.sh apacheServer11

# 인스턴스 설정 수정
cd /software/apache/servers/apacheServer11/conf
vi httpd.conf
vi ...
vi ...
```

## Tomcat Template 설치

```bash
# 실습 경로 이동
cd /home/webwas/edu-webwas

# Apache 템플릿 압축 해제
tar xvf ...

# Tomcat 템플릿을 /software 하위로 이동
mv tomcat /software/tomcat
```

## Tomcat 인스턴스 구성

```bash
# Tomcat servers 경로 이동
cd /software/tomcat/servers

# 인스턴스 생성
sh create_server.sh tomcatServer11

# 인스턴스 설정 수정
cd /software/apache/servers/tomcatServer11/shl
vi tomcat.env

```
