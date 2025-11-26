# AI 코딩 교육 9차수 (11.27~11.28)
2일차 자료 및 정보

# 프로그램 설치 및 환경 확인
<파이썬 3.10 이상>  
3.14 이상은 pip 오류 발생으로, 낮은버전으로 재설치   
  
python --version (WIN)  
python3 --version (MAC)  

pip --version (WIN)  
pip3 --version (MAC)  

<node.js 18.0 이상>  
node --version  
npm --version  
npx --version  

버전이 모두 출력되어야 정상

# MCP 설정

```
{
  "mcpServers": {
    "context7": {
      "url": "https://mcp.context7.com/mcp",
      "headers": {
        "CONTEXT7_API_KEY": "YOUR_API_KEYS"
      }
    }
  }
}

```


# 실습자료 제출 
   [https://form.jotform.com/252988672307470  ](https://form.jotform.com/253277059630460)

# 기타 참고 자료

https://docs.cursor.com/ko/guides/working-with-context  
https://github.com/PatrickJS/awesome-cursorrules  
https://www.commits.world/p/12-ways-to-properly-use-cursor  


# Python Openai ssl 오류 우회 방법

import httpx  

http_client = httpx.Client(verify=False)  
client = OpenAI(api_key=api_key, http_client=http_client)  
