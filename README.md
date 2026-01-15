[![Promo](https://brightdata.co.kr/static/github_promo_15.png?md5=105367-daeb786e)](https://brightdata.co.kr/?promo=github15) 

# proxy_scrape_go
프록시 서버를 사용하여 Colly, GOquery, Selenium으로 Web스크레이핑을 수행하는 방법을 시연하는 기본 API sergo 프로그램입니다

이 리포지토리에는 두 개의 브랜치가 포함되어 있습니다:

- `basic` 브랜치에는 문서 [Go Proxy Servers](https://brightdata.co.kr/blog/how-tos/go-proxy-servers)에서 수정될 기본 코드가 포함되어 있습니다.

- `main` 브랜치는 해당 문서 튜토리얼의 결과물입니다.

이 프로젝트는 [Web Scraping in Go](https://brightdata.co.kr/blog/how-tos/web-scraping-go)에서 프록시 서버를 설정하는 방법을 시연합니다. 프록시는 Web스크레이핑 중 자신의 IP 주소를 사용하여 디지털 신원을 보호하고, IP 차단 및 지역 차단(geoblocking)을 우회하는 데 도움이 됩니다.

## Installation
이 프로젝트를 사용하려면 머신에 Go가 설치되어 있어야 합니다. 공식 웹사이트에서 Go를 다운로드하여 설치할 수 있습니다: [https://golang.org/](https://golang.org/)

## Getting Started
1. 리포지토리를 클론합니다:

    ```shell
    git clone https://github.com/shacharbd/proxy-scrape-go.git
    ```
2. 프로젝트 디렉터리로 이동합니다:

    ```shell
    cd proxy-scrape-go
    ```
3. 의존성을 설치합니다:

    ```shell
    go mod download
    ```
## Usage
이 프로젝트는 Go에서 프록시 서버를 사용하여 Web스크레이핑을 수행하는 방법을 시연합니다. 다음 라이브러리를 활용합니다:
- [Colly](https://github.com/gocolly/colly) - Go용 스크레이핑 프레임워크입니다
- [Goquery](https://github.com/PuerkitoBio/goquery) - Go에서 HTML을 파싱하기 위한 라이브러리입니다
- [Selenium](https://github.com/tebeka/selenium) - 브라우저 자동화 도구입니다

프로젝트를 실행하려면 유효한 프록시 서버가 있는지 확인하십시오. [Bright Data](https://brightdata.co.kr/)와 같은 제공업체로부터 프록시 서버 정보를 얻을 수 있습니다. 프록시 서버 정보를 확보한 후, 적절한 프록시 구성으로 `main.go` 파일을 업데이트하십시오.

## Contributing
기여는 환영합니다! 문제를 발견했거나 개선 제안이 있으시면 이슈를 열거나 pull request를 제출해 주십시오.

## License
이 프로젝트는 MIT License에 따라 라이선스가 부여됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하십시오.