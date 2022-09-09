# Custom eslint plugin   

@injectable()과 동시에 readonly 없이 변수 선언하는건 방지해주는 eslint   

### 사용방법   
1. 패키지 설치
  npm install -D eslint-plugin-gzeromin

2. .eslintrc에 다음과 같이 설정해주기
```
{
  "plugins": [gzeromin],
  "rules": {
    "gzeromin/check-access-modifiers-injectable": "warn"  
  }
}
```