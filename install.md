# Golang 설치하기

#### 다운로드

### 환경변수 설정하기

#### macOS
홈디렉토리에 go 디렉토리를 생성합니다.

	$ mkdir ~/go

홈디렉토리에 .bash_profile에 아래줄을 추가합니다.
파일이 없다면 .bash_profile을 생성하고 아래 내용을 추가합니다.

    export GOPATH=$HOME/go
	export GOBIN=$GOPATH/bin
	export PATH=$PATH:$GOBIN
