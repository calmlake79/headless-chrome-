# headless-chrome
헤드리스 크롬 사용법
( 본 내용은 향후 변경이 가능하고 잘못된 부분이 있을 수 있음 )

# Ubuntu 에서 크롬 설치하기
```bash
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' | sudo tee /etc/apt/sources.list.d/google-chrome.list
apt update
apt install google-chrome-stable
```

# 터미널에서 아래와 같은 방법으로 사용
google-chrome --headless --screenshot --disable-gpu --window-size=1280,4000 "https://www.naver.com/"

# 이미지 파일이 출력됨
Node와 연결하는 방법은 추후 업데이트
