
```
# 빌드
docker build --tag "azp-agent:linux" .

# 태그 달기
docker tag 35fe50ebb800 sh95119/azp-agent:latest

# 허브로 업로드
docker push sh95119/azp-agent:latest
```
